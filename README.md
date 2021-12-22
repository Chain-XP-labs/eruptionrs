# eruptionrs
A truly decentralized, interoperable, accessible, high throughput, and low-cost blockchain node using the Avalanche Consensus Protocol written in Rust.

## Goals
 - Current blockchains are still not truly decentralized. For example, Ava Labs [historically](https://read.cash/@J-Stodd/my-opinion-of-avalanche-avax-in-2021-successes-shortcomings-and-concerns-f6da38fe) has centralized control having owned a majority of Avax. This defeats the purpose of decentralized blockchains. Instead, we aim to create a [DAO-like entity](https://en.wikipedia.org/wiki/The_DAO_(organization)).
 - Allow consensus to determine when, where, and how to balance proof of stake and proof of identity. One goal of decentralization is to step away from the old fashioned framework where the wealthy get to make all the decisions. Majority, plurality, and opinion of the public is an important factor in systemic decisions. 
 - Accessibility and equal access. Rust as a programming language is safe and lightweight when compared to Avax's Go. This allows the technology to be used by more people without top of the line computers around the world.
 - Robust against pyramid schemes, rug pulls, no refunds, and other activities crypto is notorius for. We aim to do this by incorporating things like proof of identity and "task lifetimes (TBD)" into the core of our implementation. This allows our protocol to be trustable, without having to trust external entities.
