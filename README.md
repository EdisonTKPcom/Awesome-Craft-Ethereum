<div align="center">

# Awesome Craft Ethereum [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of verified open-source Ethereum clients, SDKs, dev frameworks, wallets and security tools.

![Tools](https://img.shields.io/badge/tools-25-6366f1?style=for-the-badge)
[![Categories](https://img.shields.io/badge/categories-7-0ea5e9?style=for-the-badge)](#contents)
[![Combined stars](https://img.shields.io/badge/combined_stars-191.9k-f59e0b?style=for-the-badge&logo=github)](#-leaderboard)
[![Stars](https://img.shields.io/github/stars/EdisonTKPcom/Awesome-Craft-Ethereum?style=for-the-badge&color=22c55e)](https://github.com/EdisonTKPcom/Awesome-Craft-Ethereum/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/EdisonTKPcom/Awesome-Craft-Ethereum?style=for-the-badge&color=ec4899)](https://github.com/EdisonTKPcom/Awesome-Craft-Ethereum/commits/main)

</div>

Running validators, deploying contracts or using experimental tooling can put real funds at risk. This list is not investment or yield advice. Public code is not an audit.

This list is the Ethereum-specific stack. AMM and perpetual protocol source lives mainly in Awesome Craft Web3, to reduce overlap. Running a validator or deploying contracts can put real funds at risk. This list is not investment advice. Browser wallets are included only when their repository licence was checked.

## Contents

- [Dashboard](#dashboard)
- [Execution clients](#execution-clients)
- [Consensus clients](#consensus-clients)
- [SDKs and libraries](#sdks-and-libraries)
- [Dev frameworks and languages](#dev-frameworks-and-languages)
- [Wallets and accounts](#wallets-and-accounts)
- [Indexers and explorers](#indexers-and-explorers)
- [Security and audit tools](#security-and-audit-tools)
- [Related lists](#related-lists)
- [Star history](#star-history)


## Dashboard

<table>
<tr>
<td align="center"><h2>25</h2>listed projects</td>
<td align="center"><h2>7</h2>categories</td>
<td align="center"><h2>191.9k</h2>combined GitHub stars</td>
<td align="center"><h2>68.8k</h2>combined forks</td>
<td align="center"><h2>23/25</h2>pushed in the last 30 days</td>
<td align="center"><h2>11</h2>languages</td>
</tr>
</table>

**FACT** (snapshot taken 2026-11-15, GitHub API): 25 listed projects, 25 of them on GitHub with public repository statistics. Official documentation and other non-GitHub entries are listed but have no stars, forks or push dates.

**ESTIMATE**: 191.9k combined GitHub stars and 68.8k combined forks, summed from those API counts on the snapshot date. Live star badges next to GitHub entries may differ.

### 🏆 Leaderboard

<table>
<tr><th>Rank</th><th>Project</th><th>Kind</th><th align="right">Stars</th><th></th></tr>
<tr><td align="center">🥇</td><td><b>go-ethereum</b></td><td>Execution client</td><td align="right">51.5k</td><td><code>████████████████████</code></td></tr>
<tr><td align="center">🥈</td><td><b>OpenZeppelin Contracts</b></td><td>Contract library</td><td align="right">27.4k</td><td><code>███████████</code></td></tr>
<tr><td align="center">🥉</td><td><b>Solidity</b></td><td>Contract language</td><td align="right">25.8k</td><td><code>██████████</code></td></tr>
<tr><td align="center">4</td><td><b>Foundry</b></td><td>EVM toolchain</td><td align="right">10.8k</td><td><code>████</code></td></tr>
<tr><td align="center">5</td><td><b>ethers.js</b></td><td>JavaScript library</td><td align="right">8.7k</td><td><code>███</code></td></tr>
<tr><td align="center">6</td><td><b>Hardhat</b></td><td>EVM toolchain</td><td align="right">8.5k</td><td><code>███</code></td></tr>
<tr><td align="center">7</td><td><b>Slither</b></td><td>Static analysis</td><td align="right">6.4k</td><td><code>██</code></td></tr>
<tr><td align="center">8</td><td><b>Reth</b></td><td>Execution client</td><td align="right">5.9k</td><td><code>██</code></td></tr>
<tr><td align="center">9</td><td><b>web3.py</b></td><td>Python library</td><td align="right">5.5k</td><td><code>██</code></td></tr>
<tr><td align="center">10</td><td><b>Vyper</b></td><td>Contract language</td><td align="right">5.2k</td><td><code>██</code></td></tr>
</table>


### Stars by category

```mermaid
pie showData
    title Combined GitHub stars by category
    "Execution clients" : 64466
    "Consensus clients" : 10182
    "SDKs and libraries" : 45280
    "Dev frameworks and languages" : 50241
    "Wallets and accounts" : 2192
    "Indexers and explorers" : 9378
    "Security and audit tools" : 10117
```

### Licences

![Apache-2.0](https://img.shields.io/badge/Apache--2.0-7-64748b?style=flat-square) ![Custom](https://img.shields.io/badge/Custom-5-64748b?style=flat-square) ![MIT](https://img.shields.io/badge/MIT-4-64748b?style=flat-square) ![LGPL-3.0](https://img.shields.io/badge/LGPL--3.0-3-64748b?style=flat-square) ![GPL-3.0](https://img.shields.io/badge/GPL--3.0-3-64748b?style=flat-square) ![AGPL-3.0](https://img.shields.io/badge/AGPL--3.0-3-64748b?style=flat-square)

"Custom" or "None" means GitHub could not match a standard SPDX licence, often because of extra terms or an undeclared licence. Read the project licence before you use it commercially.

## Execution clients

- [Erigon](https://github.com/erigontech/erigon) - An efficiency-oriented Ethereum execution client, formerly ledgerwatch/erigon. ![Stars](https://img.shields.io/github/stars/erigontech/erigon?style=flat-square&label=%E2%AD%90)
- [go-ethereum](https://github.com/ethereum/go-ethereum) - The Go Ethereum execution-layer client, commonly called Geth. The repository includes LGPL-3.0 and the GPL-3.0 text that LGPL-3 references; treat Geth as LGPL-3.0 unless a specific package says otherwise. ![Stars](https://img.shields.io/github/stars/ethereum/go-ethereum?style=flat-square&label=%E2%AD%90)
- [Hyperledger Besu](https://github.com/hyperledger/besu) - An enterprise-oriented Ethereum execution client written in Java, under the Hyperledger project. ![Stars](https://img.shields.io/github/stars/hyperledger/besu?style=flat-square&label=%E2%AD%90)
- [Nethermind](https://github.com/NethermindEth/nethermind) - The .NET Ethereum execution-layer client. ![Stars](https://img.shields.io/github/stars/NethermindEth/nethermind?style=flat-square&label=%E2%AD%90)
- [Reth](https://github.com/paradigmxyz/reth) - A Rust execution-layer client for Ethereum, dual-licensed MIT or Apache-2.0. ![Stars](https://img.shields.io/github/stars/paradigmxyz/reth?style=flat-square&label=%E2%AD%90)

## Consensus clients

- [Lighthouse](https://github.com/sigp/lighthouse) - A Rust consensus-layer client for Ethereum, maintained by Sigma Prime. ![Stars](https://img.shields.io/github/stars/sigp/lighthouse?style=flat-square&label=%E2%AD%90)
- [Lodestar](https://github.com/ChainSafe/lodestar) - A TypeScript consensus-layer client for Ethereum, maintained by ChainSafe. ![Stars](https://img.shields.io/github/stars/ChainSafe/lodestar?style=flat-square&label=%E2%AD%90)
- [Nimbus](https://github.com/status-im/nimbus-eth2) - A lightweight Ethereum consensus client from Status. ![Stars](https://img.shields.io/github/stars/status-im/nimbus-eth2?style=flat-square&label=%E2%AD%90)
- [Prysm](https://github.com/OffchainLabs/prysm) - An Ethereum consensus client, now under Offchain Labs (formerly prysmaticlabs/prysm). ![Stars](https://img.shields.io/github/stars/OffchainLabs/prysm?style=flat-square&label=%E2%AD%90)
- [Teku](https://github.com/Consensys/teku) - A Java Ethereum consensus client from Consensys. ![Stars](https://img.shields.io/github/stars/Consensys/teku?style=flat-square&label=%E2%AD%90)

## SDKs and libraries

- [ethers.js](https://github.com/ethers-io/ethers.js) - A widely used JavaScript and TypeScript library for Ethereum wallets, providers and contracts. ![Stars](https://img.shields.io/github/stars/ethers-io/ethers.js?style=flat-square&label=%E2%AD%90)
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - A library of reusable Solidity contracts for tokens, access control and related patterns. This is library code, not a substitute for an audit of your own system. ![Stars](https://img.shields.io/github/stars/OpenZeppelin/openzeppelin-contracts?style=flat-square&label=%E2%AD%90)
- [viem](https://github.com/wevm/viem) - A TypeScript interface for Ethereum, focused on type safety and modularity. ![Stars](https://img.shields.io/github/stars/wevm/viem?style=flat-square&label=%E2%AD%90)
- [web3.py](https://github.com/ethereum/web3.py) - A Python library for interacting with Ethereum. Confirm the current GitHub organization and licence in the repository you install. ![Stars](https://img.shields.io/github/stars/ethereum/web3.py?style=flat-square&label=%E2%AD%90)

## Dev frameworks and languages

- [Foundry](https://github.com/foundry-rs/foundry) - A Rust-based toolchain for compiling, testing, scripting and deploying Ethereum contracts. ![Stars](https://img.shields.io/github/stars/foundry-rs/foundry?style=flat-square&label=%E2%AD%90)
- [Hardhat](https://github.com/NomicFoundation/hardhat) - A JavaScript and TypeScript contract development environment. ![Stars](https://img.shields.io/github/stars/NomicFoundation/hardhat?style=flat-square&label=%E2%AD%90)
- [Solidity](https://github.com/ethereum/solidity) - The Solidity compiler, solc. ![Stars](https://img.shields.io/github/stars/ethereum/solidity?style=flat-square&label=%E2%AD%90)
- [Vyper](https://github.com/vyperlang/vyper) - A Python-like contract language and compiler. ![Stars](https://img.shields.io/github/stars/vyperlang/vyper?style=flat-square&label=%E2%AD%90)

## Wallets and accounts

- [Safe Smart Account](https://github.com/safe-fndn/safe-smart-account) - The Safe smart-contract account (formerly Gnosis Safe) for multi-signature self-custody. UI products and modules may have additional terms. ![Stars](https://img.shields.io/github/stars/safe-fndn/safe-smart-account?style=flat-square&label=%E2%AD%90)

## Indexers and explorers

- [Blockscout](https://github.com/blockscout/blockscout) - A self-hostable Ethereum explorer. Current versions use a source-available licence with commercial-hosting restrictions; older tags were GPL-3.0. See the Web3 list for a longer licence note. ![Stars](https://img.shields.io/github/stars/blockscout/blockscout?style=flat-square&label=%E2%AD%90)
- [Otterscan](https://github.com/otterscan/otterscan) - A lightweight, self-hostable Ethereum explorer UI. ![Stars](https://img.shields.io/github/stars/otterscan/otterscan?style=flat-square&label=%E2%AD%90)
- [The Graph Node](https://github.com/graphprotocol/graph-node) - A self-hostable indexer for Ethereum and other chain data via subgraphs. ![Stars](https://img.shields.io/github/stars/graphprotocol/graph-node?style=flat-square&label=%E2%AD%90)

## Security and audit tools

- [Echidna](https://github.com/crytic/echidna) - A smart-contract fuzzer from Trail of Bits, used to find assertion failures and property violations. ![Stars](https://img.shields.io/github/stars/crytic/echidna?style=flat-square&label=%E2%AD%90)
- [Medusa](https://github.com/crytic/medusa) - A Go Ethereum smart-contract fuzzer from Trail of Bits, related to the Echidna family of tools. ![Stars](https://img.shields.io/github/stars/crytic/medusa?style=flat-square&label=%E2%AD%90)
- [Slither](https://github.com/crytic/slither) - A Solidity static analysis framework from Trail of Bits. Static analysis is not a complete audit. ![Stars](https://img.shields.io/github/stars/crytic/slither?style=flat-square&label=%E2%AD%90)

## Related lists

Other lists in the Awesome Craft series:

- [Awesome Craft](https://github.com/EdisonTKPcom/Awesome-Craft) - A curated list of open-source, self-hostable alternatives to popular SaaS tools.
- [Awesome Craft Agents](https://github.com/EdisonTKPcom/Awesome-Craft-Agents) - A curated list of open-source chat apps, coding agents, self-hosted agent bots, workflow automation and image-generation UIs.
- [Awesome Craft AI](https://github.com/EdisonTKPcom/Awesome-Craft-AI) - A curated list of open-source, self-hostable AI runtimes, servers, Hugging Face libraries and related infrastructure.
- [Awesome Craft BSC](https://github.com/EdisonTKPcom/Awesome-Craft-BSC) - A curated list of verified open-source clients, SDKs, dev tools and protocol code for BNB Smart Chain and opBNB.
- [Awesome Craft CUDA](https://github.com/EdisonTKPcom/Awesome-Craft-CUDA) - A curated list of open-source CUDA learning material, kernel libraries, tooling and portability projects.
- [Awesome Craft DeepSeek](https://github.com/EdisonTKPcom/Awesome-Craft-DeepSeek) - A curated list of official DeepSeek repositories and open-source harnesses, serving engines, eval tools and fine-tuning stacks that work with DeepSeek models.
- [Awesome Craft DevOps](https://github.com/EdisonTKPcom/Awesome-Craft-DevOps) - A curated list of open-source, self-hostable alternatives to popular DevOps and hosting SaaS tools.
- [Awesome Craft DNA](https://github.com/EdisonTKPcom/Awesome-Craft-DNA) - A curated list of open-source tools for DNA, genomics and synthetic biology.
- [Awesome Craft EV](https://github.com/EdisonTKPcom/Awesome-Craft-EV) - A curated list of open-source software and hardware for electric vehicles and charging.
- [Awesome Craft Hardware](https://github.com/EdisonTKPcom/Awesome-Craft-Hardware) - A curated list of open-source tools for PCB, FPGA, ASIC and chip design.
- [Awesome Craft Hyperliquid](https://github.com/EdisonTKPcom/Awesome-Craft-Hyperliquid) - A curated list of verified open-source SDKs, node tools, analytics and community libraries for the Hyperliquid ecosystem.
- [Awesome Craft Jarvis](https://github.com/EdisonTKPcom/Awesome-Craft-Jarvis) - A curated list of open-source tools to run a personal JARVIS-style AI assistant locally, including dashboards, agent runtimes, voice, MCP connections and memory.
- [Awesome Craft Malaysia](https://github.com/EdisonTKPcom/Awesome-Craft-Malaysia) - A curated list of open-source tools useful to Malaysian SMEs, with verified MyInvois support called out separately.
- [Awesome Craft Mars](https://github.com/EdisonTKPcom/Awesome-Craft-Mars) - A curated list of open-source tools and open data for Mars missions and settlement planning.
- [Awesome Craft Neuro](https://github.com/EdisonTKPcom/Awesome-Craft-Neuro) - A curated list of open-source tools for brain-computer interfaces, electrophysiology and neurotechnology.
- [Awesome Craft Robotics](https://github.com/EdisonTKPcom/Awesome-Craft-Robotics) - A curated list of open-source robotics software and hardware, including Microduck, Unitree SDKs, open humanoids, arms, simulation and middleware.
- [Awesome Craft Solana](https://github.com/EdisonTKPcom/Awesome-Craft-Solana) - A curated list of verified open-source Solana clients, SDKs, frameworks, explorers and program libraries.
- [Awesome Craft Space](https://github.com/EdisonTKPcom/Awesome-Craft-Space) - A curated list of open-source tools for spaceflight and rockets, covering orbit simulation, telemetry, launch data and more.
- [Awesome Craft Starlink](https://github.com/EdisonTKPcom/Awesome-Craft-Starlink) - A curated list of open-source tools for Starlink and other LEO satellite internet systems.
- [Awesome Craft Web3](https://github.com/EdisonTKPcom/Awesome-Craft-Web3) - A curated list of open-source DEX protocol code, self-custody software, indexers, frameworks and Blockchain infrastructure.

## Star history

[![Star History Chart](https://api.star-history.com/chart?repos=EdisonTKPcom/Awesome-Craft-Ethereum&amp;type=Date)](https://www.star-history.com/#EdisonTKPcom/Awesome-Craft-Ethereum&Date)

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

<div align="center">

If this list is useful, give it a ⭐ so others can find it.

</div>
