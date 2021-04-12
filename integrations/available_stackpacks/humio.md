---
title: Manual Topology
kind: documentation
---

# Humio

## Manual Topology


{% hint style="warning" %}
**This page describes StackState version 4.0.**

The StackState 4.0 version range is End of Life (EOL) and **no longer supported**. We encourage customers still running the 4.0 version range to upgrade to a more recent release.

Go to the [documentation for the latest StackState release](https://docs.stackstate.com/).
{% endhint %}

## Humio

### What is the Humio StackPack?

The Humio StackPack allows you to access your logs stored in Humio.

Using this StackPack, you can:

* Jump straight to your container logs in Humio using a Quick Action on docker container components running in Kubernetes

### Prerequisites

* A Humio cloud account
* The Humio Kubernetes agent, see the [Humio Kubernetes platform integration](https://docs.humio.com/integrations/platforms/kubernetes/)
* Logging from each Kubernetes cluster must be stored in a **repository with the same name as your cluster** in Humio

### Using the Humio StackPack

Navigate to your Kubernetes cluster in StackState and use a Quick Action on one of the containers to jump into your logs.
