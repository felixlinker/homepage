---
title: "About"
date: 2017-12-17T16:14:04+01:00
draft: false
---

{{< figure class="avatar" src="/img/avatar.jpg" alt="avatar" >}}

## About Me

I am Felix Linker, a postdoc in the [Information Security group](https://infsec.ethz.ch/) at ETH Zurich, independent consultant, and one of the leading experts for the [Tamarin prover](https://tamarin-prover.com/), a state-of-the-art protocol verifier.
I obtained my Doctorate in that same research group in 2025.

I develop security critical systems, and I conduct formal analyses to prove security guarantees of such systems.
Not only does formal analysis enhance the confidence in a system's security, formal analysis also requires explicit adversary assumptions and desired security guarantees, which can often times be as valuable as the security proofs.

Please [reach out](/contact) if you are interested in a collaboration!
Next to the design and formal analysis of security critical systems, I offer Tamarin training and have hosted many workshops on the tool.

## Projects

### Formal Analysis of iMessage PQ3

In 2024, Apple announced their update of the iMessage message encryption protocol to [iMessage PQ3](https://security.apple.com/blog/imessage-pq3/), adding protecting against quantum attackers to the protocol.
Prior to release, Apple shared the protocol specification with us, and we formally proved iMessage PQ3's security against a quantum attacker using the Tamarin prover, something that was previously believed to be impossible.
You can find more details in our [paper](https://eprint.iacr.org/2024/1395).

### Digital Emblems

I help the [International Committee of the Red Cross (ICRC)](https://www.icrc.org/en) with the requirements engineering, development, and standardization of [ADEM](https://cyber-trust.org/projects/internet-arch/adem/), a proposal for a *Digital Emblem*.
I represent the ICRC from a technical point of view, for example, at the [IETF](https://datatracker.ietf.org/wg/diem/about/).

A Digital Emblem marks digital assets, for example web servers, as protected under International Humanitarian Law - just like the physical emblems of the Red Cross, Red Crescent, and Red Crystal do in the physical world.
This work started as a research project during my Doctoral studies and is now transitioning to adoption.

### Key Transparency

I am a co-author of a [key transparency draft](https://datatracker.ietf.org/doc/draft-ietf-keytrans-protocol/) that is being standardized at the IETF.
We currently work on the formal analysis of the draft using the program verifier [Gobra](https://github.com/viperproject/gobra).

### SecureDrop

I help [Freedom of the Press Foundation](https://freedom.press/) with the requirements engineering, design, and formal analysis of an end-to-end encrypted version of the [SecureDrop protocol](https://github.com/freedomofpress/securedrop).
SecureDrop is a whisteblowing platform that has been deployed at the New York Times, The Guardian, The Washington Post, and many more news outlets.
I previously helped supervise a [Masters thesis](https://www.research-collection.ethz.ch/handle/20.500.11850/718325) on the formal analysis of SecureDrop, and we currently continue to enhance the design.

### Cyclic Induction for the Tamarin Prover

We developed and implemented a new induction scheme for the Tamarin prover in the paper "Looping for Good: Cyclic Proofs for Security Protocols."
This induction scheme exploits recurring patterns in Tamarin's constraint systems and allows us to prove the Signal protocol secure without using any auxiliary lemmas and almost fully automatically.
Our work opens an exciting new research area where automatic induction helps scale security protocol verification, as we provide a fundamentally new and general induction mechanism, and we plan to further enhance Tamarin's proof automation using this work in the future.

## Publications

* Linker F., Sprenger C., Cremers C., Basin D. **Looping for Good: Cyclic Proofs for Security Protocols**. To appear: Conference on Computer and Communications Security (CCS). 2025. ([pre-publication](https://doi.org/10.3929/ethz-c-000783356))
* Linker F. **Protocol Design and Analysis in the Symbolic Model**. Doctoral Thesis. 2025. ([pdf](/doc/phd_thesis.pdf)|[electronic version](https://doi.org/20.500.11850/784312))
* Linker F., Sasse R., Basin D. **A Formal Analysis of Apple's iMessage PQ3 Protocol**. 34th USENIX Security Symposium, (USENIX Security). 2025. ([eprint](https://eprint.iacr.org/2024/1395)|[USENIX](https://www.usenix.org/conference/usenixsecurity25/presentation/linker)|[Apple Blog](https://security.apple.com/blog/imessage-pq3/))
* Linker F., Basin D. **SOAP: A Social Authentication Protocol**. 33rd USENIX Security Symposium (USENIX Security). 2024. ([pdf](https://www.usenix.org/system/files/sec24summer-prepub-1083-linker.pdf)|[USENIX](https://www.usenix.org/conference/usenixsecurity24/presentation/linker))
* Linker F., Basin D. **ADEM: An Authentic Digital EMblem**. Conference on Computer and Communications Security (CCS). 2023. ([pdf](/doc/adem.pdf)|[doi](https://doi.org/10.1145/3576915.3616578))
* Baumann R., Linker F. **AGM Meets Abstract Argumentation: Contraction for Dung Frameworks**. In: *Logics in Artificial Intelligence*. JELIA 2019. ([pdf](https://www.researchgate.net/profile/Ringo-Baumann/publication/332211310_AGM_Meets_Abstract_Argumentation_Contraction_for_Dung_Frameworks/links/5ca658184585157bd322dbfd/AGM-Meets-Abstract-Argumentation-Contraction-for-Dung-Frameworks.pdf)|[doi](https://doi.org/10.1007/978-3-030-19570-0_3))
