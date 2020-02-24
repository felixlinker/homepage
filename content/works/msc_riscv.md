---
title: "Master's thesis: Formal verification of an instruction set architecture"
date: 2019-07-11
draft: false
---

I started writing on my master's thesis for Computer Science in May of 2019.
This thesis links to my internship at Arm in the winter of 2018.
In this thesis, I develop a minimal, [RISC-V](https://riscv.org/)-inspired architecture and use the model checker [nuXmv](https://nuxmv.fbk.eu/) to either find vulnerabilities in the instruction set specification itself or to establish rules for programmers of the architecture.

This is the thesis's abstract:

> This thesis proposes an approach to formally verifying instruction set architectures (ISAs) against higher-level properties using the model checker nuXmv.
This was first proposed by [Rei17].
We use nuXmv to perform information flow tracking at architecture level.
Thus, the higher-level properties will be given by information flow properties.
The concepts behind information flow tracking stem from [Fer+17] where information flow control (IFC) was applied to hardware description languages (HDLs).
>
> The threat model that is assumed in this thesis is that user-mode is adversarial to machine-mode and wholly compromised.
In this scenario, we consider whether a) user-mode can gain access to confidential data held by machine-mode and b) user-mode can gain control over machine-mode.
Timing channels are excluded.
>
> We develop a simplified version of the RISC-V architecture, the MINRV8 architecture, to which the aforementioned approach will be applied.
Three information flow properties applying to this architecture will be developed and verified using nuXmv.
The result of this are eight assumptions that grant the absence of any information flow property violation by any program running on the MINRV8 architecture.
These results are tested by showing that our approach can detect the cache poisoning [WR09] and SYSRET vulnerabilities [12a,Dun12] applying to the x86 architecture without any manual intervention besides the implementation of the vulnerabilities.

[*Link to the github repository*](https://github.com/felixlinker/ifc-rv-thesis/)

[*Link to the thesis*](/doc/msc_thesis.pdf)
