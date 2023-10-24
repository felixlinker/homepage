---
title: "2 days, 2 bugs - OpenID for Verifiable Presentations over BLE"
date: 2023-08-31T18:01:11+02:00
draft: true
---

# 2 Days, 2 Issues

Recently, I was approached whether I was interested in conducting a formal analysis on the *OpenID for Verifiable Presentations over BLE* specification.
While the specification looks simple, it is not entirely straight-forward, and thus a worthy candidate for formal analysis.

This post is a story about how I found two issues with the specification using our research group's protocol verification tool Tamarin, and how formal methods can help you in the development of systems without requiring tons of work.

A brief overview of the protocol.

- A *verifier* advertises that they would like to see a verifiable presentation using a BLE beacon or a QR code
- A *wallet* uses this advertisement to establish a secure BLE channel with the verifier
- The verifier sends a signed request to the wallet that specifies which credential they would like to receive
- The wallet verifies the request and shares the credential with the verifier

Now, as we with many protocols, you might wonder: What could go wrong?
But to answer that question, we must first understand the protocols security requirements.
This is not straightforward as the specification does not define any!

So I thought: Let's go with the easiest one.
Verifiers don't want to get bamboozled, so there should be some authentication property.
Non-injective agreement will do.
Wallets don't want to leak tokens, so some privacy property would be great.
Because no one likes observational equivalence, a good old secrecy property will do.

Also, because I'm short on time: No one cares about how we set up a secure channel (@Kenny 👀), so lets abstract that baby away.
Also, the spec doesn't mention how we should verify the signature, so let's throw that baby away as well!
Now we really wonder: *What* should go wrong?

Well, as it turns out... Many things!
Both injective agreement and secrecy do not hold.
Why?
Because a PITM can simply establish a channel with a verifier and a wallet and forward all messages.
Thereby, they will receive the token, and the verifier thinks that it was the attacker that shared the token with them.

The mitigation is easy: The verifier could include a hash of the established channel's key material in the request.
This way, the wallet can detect the attacker.
