---
description: >-
  This page explains which networks are supported by Snapshot and how to add a
  new one.
---

# Add a network

## EVM-based networks

Snapshot supports EVM-based networks. You can explore them at [**https://snapshot.org**](https://snapshot.org) by selecting the `Networks` filter:

<figure><img src="../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>

You can also follow this link directly: [https://snapshot.org/#/?filter=networks](https://snapshot.org/#/?filter=networks).

## Add a new network

If you can't see the network you are looking for on the list or you want to add your custom network, fill in the form linked below to include it within Snapshot.

#### Requirements

* Pay to support your network by clicking [here](https://snapshot.org/#/payment/network)
* New network must be **EVM**-based
* RPC node must be an **archive node**
* RPC node's url must use **`https`**&#x20;
* Multicall contract must be **verified and published**&#x20;
* The node should accept **minimum payload and have higher gas caps** (at least **500** addresses into a multicall)
* Logo has to be stored on **IPFS**

{% embed url="https://tally.so/r/31ApGb" %}

It's now in the hands of the Snapshot team to review your changes and apply them to [https://snapshot.org](https://snapshot.org).&#x20;

The average time to add a new network is 7 days, so please be patient! 😉

**Once added, we will tag you in the PR on Github.**
