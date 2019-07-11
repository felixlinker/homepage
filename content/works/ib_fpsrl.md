---
title: "Industrial Benchmark for Fuzzy Particle Swarm Reinforcement Learning"
date: 2019-01-30
---

In January of 2019 I implemented a project to benchmark the approach to controller policy optimization proposed by *Hein et al., 2017* called *Fuzzy Particle Swarm Reinforcement Learning* (FPSRL).
In that paper, the authors propose a method to generate *interpretable* policies for industrial controllers that are as performant as non-interpretable policies by using neural networks and particle swarm optimization.

I applied the *Industrial Benchmark* (IB) to that approach thereby following a methodology the authors themselves used to benchmark a similar approach in *Hein, Udluft, Runkler, 2018* which followed the same idea but used genetic programming instead of particle swarm optimization.
I wrote the code to benchmark that approach in python.

[*Link to the github repository (with references)*](https://github.com/felixlinker/IB_FPSRL)

[*Results paper*](/doc/ib_fpsrl.pdf)
