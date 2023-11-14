# Civ Kit: A Peer-to-Peer Electronic Market System

Nicholas Gregory, Ray Youssef and Antoine Riard
a@hachiko.dev

**Abstract.** The Bitcoin protocol enables a global store of value system without a single trusted third party issuing or holding the funds. Participants are only required to have access to a standard computer using a broadband connection. As a second layer, the Lightning protocol enables fast, instant, and cheap value transfers between all participants of the Bitcoin system by rolling out a decentralized network of payment channels. While those protocols enable global value transfers, they do not allow global trading with the same properties.

We propose a new peer-to-peer electronic market system, which enables censorship-resistant and permissionless trading between users of the global Bitcoin system. This design builds on top of the new Nostr protocal for its truth for its Web-of-Stake market ranking paradigm. Market trades are locked under Bitcoin contracts to avoid reliance on trusted third parties for dispute arbitration. All market nodes are incentivized by privacy-preserving service credentials backed by Bitcoin payments. This market system should enable global trade of any kind of item all over the world: fiat currencies, goods, services.

**License.** This work is released into the public domain.

## 1 Introduction

Golbal trade has come to rely on a market system characterized by high barriers to entry and dispute mediation costs. This uncertainty generates additional transactional costs for people who must acquire these centralized fiat currencies to participate in global trade. Participants trading across countries to participate in global trade. Participants trading across countries often lack standardized and compatible social identification techniques to address their institutional confidence needs. A more decentralized market infrastructure can be desirable with the same properties Bitcoin has achieved as a store of value: censorship-resistance, neutrality, openness.

A peer-to-peer electronic market system is needed to extend the global flows of Bitcoin liquidity, fiat currencies, and goods to any community in a permissionless manner. In this paper, we propose such a system in which two parties can discover trade offers across a set of distruibuted bulletin boards, find each other, and execute a trade for anything using Bitcoin or Lightning as a clearing layer. No custodians are needed to escrow the coins, as they remain locked under Bitcoin Script trust-minimized escrow contracts. The escrow mechanism can be refined over time to accommodate all types of transactions, from Bitcoin to fiat money to goods and services, by leveraging oracles. Anyone can start a market bulletin board or oracle for anything, and anyone can engage in trading. All the frictions and blockades that have hindered free trade will be reduced to pure technical capabilities.

## Design Rational
