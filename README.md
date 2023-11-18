# Lab Cilium BGP

A simple reproduction of the lab presented [here](https://www.youtube.com/watch?v=AXTKS0WCXjE) to be able to test some complementary things.

## Pre-requisites

You should have the following tools installed (make sure to also check their pre-requisites):
- [docker](https://docs.docker.com/engine/install/)
- [containerlab](https://containerlab.dev/)
- [kind](https://kind.sigs.k8s.io/)
- [cilium-cli](https://docs.cilium.io/en/stable/gettingstarted/k8s-install-default/#install-the-cilium-cli)

## How to use

All the steps are described in the `Makefile`, just type `make` to initialize the lab.

When you're done, use `make clean` to remove the lab.
