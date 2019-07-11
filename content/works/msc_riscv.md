---
title: "Master's thesis: Formal verification of an instruction set architecture"
date: 2019-07-11
draft: false
---

I started writing on my master's thesis for Computer Science in May of 2019.
This thesis links to my internship at Arm in the winter of 2018.
In this thesis, I develop a minimal, [RISC-V](https://riscv.org/)-inspired architecture and try to use the model checker [nuXmv](https://nuxmv.fbk.eu/) to either find vulnerabilities in the instruction set specification itself or to establish rules for programmers of the architecture.

I program nuXmv in such a way that it automatically generates me traces of instructions that violate certain security properties.
These security properties are expressed in LTL and implement information flow policies.

[*Link to the github repository*](https://github.com/felixlinker/ifc-rv-thesis/)
