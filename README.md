# RewardGuard

Sybil protection for protocol rewards and airdrops using proof of machinehood | Powered by TEEs

## Table of Contents

1. [Links](#links)
2. [Introduction](#introduction)
3. [Background ](#background)
4. [Proposed Solution](#proposed-solution)
5. [Technical Implementation](#technical-implementaion)
6. [Why TEEs and Proof of Machinehood?](#why-tees-and-proof-of-machinehood)
7. [Team](#team)

## Links

- [Presentation](https://www.canva.com/design/DAGJ81kfe-g/rXTxKIttpU6PKiZJdraQSQ/view)
- [Demo Video]()

## Introduction

- This proposal outlines the implementation of a Sybil-resistant system for distributing protocol rewards and airdrops.

- By utilizing proof of machinehood within a Trusted Execution Environment (TEE), we aim to ensure that only legitimate participants receive rewards, thereby enhancing the security and fairness of the process.

## Background

- Sybil Attacks lead to unfair distribution of rewards, reduced trust, and compromised network security.

- Current solutions are resource-intensive, inconvenient for users, and not entirely foolproof.

## Proposed Solution

- Using Trusted Execution Environmets(TEEs) to enable secure execution and hardware level attestations for proof of on-chain activity.

- Proofs can be settled on Automata Network to ensure integrity of the participating machines.

- Later, we can cross-verify machinehood proofs using multiple TEEs to ensure robustness and filter sybils.

## Technical Implementation

![image](/images/architecture.png)

## Why TEEs and Proof of Machinehood?

- **_Fair Distribution_** : Using PoM, RewardGuard ensures that only legitimate participants receive rewards, preventing Sybil attackers from gaining an unfair advantage.

- **_Scalability & Low cost_** : TEEs provide a scalable and low cost solution that can handle a large number of participants and verifications efficiently.

- **_Verifiable Machine Trust_** : The verifiable nature of TEEs and the Automata Network enhances the overall trustworthiness of the reward distribution process.

## Team

Team [AlphaDevs](https://www.alphadevs.dev) 👇

### Github

[Harsh Tyagi](https://github.com/mr-harshtyagi)
[Yashasvi Chaudhary](https://github.com/0xyshv)

### Twitter / X

[Harsh Tyagi](https://twitter.com/0xmht)
[Yashasvi Chaudhary](https://twitter.com/0xyshv)

## Thanks

- Feel free to reach out to the [AlphaDevs team](https://www.alphadevs.dev) with any questions or issues.

- We appreciate your interest in our project and welcome contributions and feature suggestions.
