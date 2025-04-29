---
title: "About"
date: 2017-12-17T16:14:04+01:00
draft: false
---

{{< figure class="avatar" src="/img/avatar.jpg" alt="avatar" >}}

## About Me

I am Felix Linker, a Doctoral student in the [Information Security group](https://infsec.ethz.ch/) at ETH Zurich, independent consultant, and one of the leading experts for the [Tamarin prover](https://tamarin-prover.com/), a state-of-the-art protocol verifier.

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
I represent the ICRC from a technical point of view, for example, at the IETF.

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

Recently, we developed and implemented a new induction scheme for the Tamarin prover.
This induction scheme allowed us to prove the Signal protocol secure without using any auxiliary lemmas and almost fully automatically.
This work is currently under submission for scientific publication.

## Publications

* Basin D., Linker F., Sasse R. (2024) Report title: **A Formal Analysis of the iMessage PQ3 Messaging Protocol**. Apple Security Research Blog. ([Blog post](https://security.apple.com/blog/imessage-pq3/)|[Research Paper](https://eprint.iacr.org/2024/1395))
* Linker F., Basin D. (2024) **SOAP: A Social Authentication Protocol**. To appear in 33rd USENIX Security Symposium, USENIX Security 2024, Philadelphia, PA, USA, August 14-16, 2024. USENIX Association. ([pdf](https://www.usenix.org/system/files/sec24summer-prepub-1083-linker.pdf)|[USENIX](https://www.usenix.org/conference/usenixsecurity24/presentation/linker))
* Linker F., Basin D. (2023) **ADEM: An Authentic Digital EMblem**. In Proceedings of the 2023 ACM SIGSAC Conference on Computer and Communications Security (CCS '23). Association for Computing Machinery, New York, NY, USA, 2815–2829. ([pdf](/doc/adem.pdf)|[doi](https://doi.org/10.1145/3576915.3616578))
* Baumann R., Linker F. (2019) **AGM Meets Abstract Argumentation: Contraction for Dung Frameworks**. In: Calimeri F., Leone N., Manna M. (eds) *Logics in Artificial Intelligence*. JELIA 2019. Lecture Notes in Computer Science, vol 11468. Springer, Cham. ([pdf](https://www.researchgate.net/profile/Ringo-Baumann/publication/332211310_AGM_Meets_Abstract_Argumentation_Contraction_for_Dung_Frameworks/links/5ca658184585157bd322dbfd/AGM-Meets-Abstract-Argumentation-Contraction-for-Dung-Frameworks.pdf)|[doi](https://doi.org/10.1007/978-3-030-19570-0_3))
