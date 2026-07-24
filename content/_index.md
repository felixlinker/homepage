---
title: "About"
date: 2017-12-17T16:14:04+01:00
draft: false
---

<style>
li:has(.publication-anchor:target) {
    background-color: rgba(220, 53, 69, 0.12);
    border-radius: 0.2rem;
    box-shadow: 0 0 0 0.35rem rgba(220, 53, 69, 0.12);
}
</style>

{{< figure class="avatar" src="/img/avatar2.jpg" alt="avatar" >}}

## About Me

I am Felix Linker, a postdoc in the [Information Security](https://infsec.ethz.ch/) and [Network Security](https://netsec.ethz.ch/) groups at ETH Zurich, independent consultant, and one of the leading experts for the [Tamarin prover](https://tamarin-prover.com/), a state-of-the-art protocol verifier.
I obtained my Doctorate in that same research group in 2025.

I develop security critical systems, and I conduct formal analyses to prove security guarantees of such systems.
Not only does formal analysis enhance the confidence in a system's security, formal analysis also requires explicit adversary assumptions and desired security guarantees, which can often times be as valuable as the security proofs.

Please [reach out](/contact) if you are interested in a collaboration!
Next to the design and formal analysis of security critical systems, I offer Tamarin training and have hosted many workshops on the tool.

## Projects

### Formal Analysis of iMessage PQ3

In 2024, Apple announced their update of the iMessage message encryption protocol to [iMessage PQ3](https://security.apple.com/blog/imessage-pq3/), adding protecting against quantum attackers to the protocol.
Prior to release, Apple shared the protocol specification with us, and we formally proved iMessage PQ3's security against a quantum attacker using the Tamarin prover, something that was previously believed to be impossible.

See the [publication and presentations](#pub-imessage) for more details.

### Digital Emblems

I help the [International Committee of the Red Cross (ICRC)](https://www.icrc.org/en) with the development and standardization of a *Digital Emblem*.
A Digital Emblem is the digital equivalent to the physical emblems recognized under International Humanitarian Law (IHL), in particular, the Red Cross, Red Crescent, and Red Crystal.
It serves to signal that a digital asset enjoys a special status under IHL and should respected and protected.
I advise the ICRC, for example, at the [IETF](https://datatracker.ietf.org/wg/diem/about/).

Our collaboration started with the development of ADEM: An Authentic Digital Emblem (see the respective [publication](#pub-adem) and [GitHub](https://github.com/adem-wg/)).
ADEM has since then been selected as the official prototype for a Digital Emblem by the ICRC, and was featured in the ICRC's report on [Digitalizing the Red Cross, Red Crescent and Red Crystal Emblems](https://www.icrc.org/en/document/icrc-digital-emblems-report).
In July 2026, the ICRC launched Phase II of the Digital Emblem project, at which ADEM was also demoed.
You can learn more about the Digital Emblem project [here](https://www.icrc.org/en/article/icrc-digital-emblem-project).

### Key Transparency

I am a co-author of a [key transparency draft](https://datatracker.ietf.org/doc/draft-ietf-keytrans-protocol/) that is being standardized at the IETF.
We currently work on the formal analysis of the draft using the program verifier [Gobra](https://github.com/viperproject/gobra).

### SecureDrop

I helped [Freedom of the Press Foundation](https://freedom.press/) with the requirements engineering, design, and formal analysis of an end-to-end encrypted version of the [SecureDrop protocol](https://github.com/freedomofpress/securedrop).
SecureDrop is a whisteblowing platform that has been deployed at the New York Times, The Guardian, The Washington Post, and many more news outlets.
Previously, SecureDrop relied on a secure deployment, e.g., on premises.
The new SecureDrop protocol is an end-to-end encryption protocol that removes trust assumptions from the deployment so that it can also be deployed in the cloud, for example.

See the [publication and presentations](#pub-securedrop) for more details.

### Cyclic Induction for the Tamarin Prover

We developed and implemented a new induction scheme for the Tamarin prover in the paper "Looping for Good: Cyclic Proofs for Security Protocols."
This induction scheme exploits recurring patterns in Tamarin's constraint systems and allows us to prove the Signal protocol secure without using any auxiliary lemmas and almost fully automatically.
Our work opens an exciting new research area where automatic induction helps scale security protocol verification, as we provide a fundamentally new and general induction mechanism, and we plan to further enhance Tamarin's proof automation using this work in the future.

This work received a Distinguished Paper Award at CCS 2025.
See the [publication](#pub-cyclic) for more details.

## Publications

* {{< anchor id="pub-securedrop" >}}Berra G., Linker F., Maier L., Myers C., Paterson K., Shane R., Veitch S. **The SecureDrop Protocol: End-to-End Encrypted Whistleblowing for All**. Conference on Computer and Communications Security (CCS). 2026. ([full version](https://eprint.iacr.org/2026/1484e))

  Presented at [Real World Crypto 2026](https://youtu.be/E6tHeIxWSlA?si=Ld9xBAzaVPX5RHAM) and [IETF UFMRG](https://youtu.be/i0lVleC87G0?si=pYPrnEufD619MMIo&t=2034)
* Linker F. **Rule Variant Restrictions for the Tamarin Prover**. Preprint. 2026. ([eprint](https://eprint.iacr.org/2026/230))
* {{< anchor id="pub-cyclc" >}} Linker F., Sprenger C., Cremers C., Basin D. **Looping for Good: Cyclic Proofs for Security Protocols**. Conference on Computer and Communications Security (CCS). 2025. ([full version](https://doi.org/10.3929/ethz-c-000783356)|[publisher version](https://dl.acm.org/doi/10.1145/3719027.3765131))

  Received **Distinguished Paper Award at CCS 2025** ([reference](https://www.sigsac.org/ccs/CCS2025/awards/))
* Linker F. **Protocol Design and Analysis in the Symbolic Model**. Doctoral Thesis. 2025. ([pdf](/doc/phd_thesis.pdf)|[electronic version](https://doi.org/20.500.11850/784312))

  Received **[Medal of ETH Zurich](https://inf.ethz.ch/news-and-events/spotlights/infk-news-channel/2025/11/outstanding-doctoral-theses-2025.html)** as an outstanding doctoral thesis
* {{< anchor id="pub-imessage" >}} Linker F., Sasse R., Basin D. **A Formal Analysis of Apple's iMessage PQ3 Protocol**. 34th USENIX Security Symposium, (USENIX Security). 2025. ([eprint](https://eprint.iacr.org/2024/1395)|[USENIX](https://www.usenix.org/conference/usenixsecurity25/presentation/linker)|[Apple Blog](https://security.apple.com/blog/imessage-pq3/))

  Presented at [Microsoft Research](https://youtu.be/5WPYQ9amgrE?si=vabKahbgnEZZo5cK) and [IETF UFMRG](https://youtu.be/FOiuDqhqLJY?si=TU3JHWuRhz6LxDv7&t=3346)
* Linker F., Basin D. **SOAP: A Social Authentication Protocol**. 33rd USENIX Security Symposium (USENIX Security). 2024. ([pdf](https://www.usenix.org/system/files/sec24summer-prepub-1083-linker.pdf)|[USENIX](https://www.usenix.org/conference/usenixsecurity24/presentation/linker))
* {{< anchor id="pub-adem" >}} Linker F., Basin D. **ADEM: An Authentic Digital EMblem**. Conference on Computer and Communications Security (CCS). 2023. ([pdf](/doc/adem.pdf)|[doi](https://doi.org/10.1145/3576915.3616578))
* Baumann R., Linker F. **AGM Meets Abstract Argumentation: Contraction for Dung Frameworks**. In: *Logics in Artificial Intelligence*. JELIA 2019. ([pdf](https://www.researchgate.net/profile/Ringo-Baumann/publication/332211310_AGM_Meets_Abstract_Argumentation_Contraction_for_Dung_Frameworks/links/5ca658184585157bd322dbfd/AGM-Meets-Abstract-Argumentation-Contraction-for-Dung-Frameworks.pdf)|[doi](https://doi.org/10.1007/978-3-030-19570-0_3))
