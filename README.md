<p align="center">
<img align="center" src="https://github.com/PriyankDev0308/DummyRepo/assets/144904558/b0edc6d5-1b17-4acb-8d94-e9a2997ea26c" width="250">
</p>

<div align="Center">
<h1>Avail Project Developer Documentation</h1>
<h3>The Essential Base Layer for Modern Blockchains</h3>
</div>

[![All Contributors](https://img.shields.io/github/all-contributors/PriyankDev0308/DummyRepo?color=ee8449&style=flat-square)](#contributors)

<p align="left">
  Welcome to the Avail Project Developer Documentation, your go-to resource for all things related to data availability and modular blockchain development. Designed with a focus on community collaboration, this repository aims to provide the most accurate, comprehensive, and up-to-date information for anyone interested in learning about, contributing to, or maintaining projects within the Avail ecosystem.
</p>

<!-- TOC -->

- [Avail Overview](#avail-overview)
  - [The Evolution from Monolithic to Modular Blockchains](#the-evolution-from-monolithic-to-modular-blockchains)
  - [The Avail Solution](#the-avail-solution)
    - [Key Features](#key-features)
    - [Benefits for Validiums and Sovereign Rollups](#benefits-for-validiums-and-sovereign-rollups)
  - [High Availability and Scalability](#high-availability-and-scalability)
  - [Key Repositories under availproject](#key-repositories-under-availproject)
    - [Get Started](#get-started)
    - [Full List](#full-list)
- [Repository Overview](#repository-overview)
  - [Configuration Guide](#configuration-guide)
    - [Static-Site Generator](#static-site-generator)
    - [Deployments](#deployments)
    - [Algolia DocSearch](#algolia-docsearch)
    - [Plausible Analytics](#plausible-analytics)
    - [Translations](#translations)
    - [Files and Folders](#files-and-folders)
  - [How to Contribute to the Avail Documentation](#how-to-contribute-to-the-avail-documentation)
    - [How to Contribute Changes via the Avail Documentation Website](#how-to-contribute-changes-via-the-avail-documentation-website)
    - [How to Locally Run the Avail Documentation](#how-to-locally-run-the-avail-documentation)
      - [Quick Run](#quick-run)
      - [Setup Steps](#setup-steps)
  - [License](#license)

<!--/ TOC -->

# Avail Overview

Avail aims to revolutionize the blockchain space by providing a trust-minimized and secure base layer focused on data availability. This base layer serves as the foundation for next-generation, trust-minimized applications and blockchains.

## The Evolution from Monolithic to Modular Blockchains

Traditional monolithic blockchains like Ethereum have faced scaling challenges due to handling multiple operations like Execution, Settlement, Ordering, and Data Availability on a single chain. Avail adopts a modular approach, separating these core operations into different layers for greater scalability and flexibility.

## The Avail Solution

Avail is a blockchain-based platform focused on creating a general-purpose data availability layer, addressing key challenges such as scalability, governance, and decentralization. By enabling technologies like Validiums and Sovereign Rollups, Avail allows for off-chain data availability, which significantly reduces costs and enhances efficiency.

### Key Features

- **Data Blob Indexing**: Avail simplifies data indexing by tying all transaction data to an application ID.
- **Erasure Encoding**: Adds redundancy to the data, making it harder for nodes to suppress information.
- **KZG Polynomial Commitments**: Ensures that the data has a footprint in the Avail block header.
- **Decentralized Network of Validators**: Avail aims to support up to 1,000 external validators to reduce centralization risks.
- **Validity Proofs**: Allows light clients to guarantee state correctness and data availability immediately after finalizing.

### Benefits for Validiums and Sovereign Rollups

- **Trust-Minimized Data Availability**: Avail provides a secure and decentralized solution for data availability.
- **Data Attestation Bridge**: Allows for attestation to Ethereum and other EVM-compatible chains, proving that data is available.

## High Availability and Scalability

Avail's light client network ensures high data availability through Data Availability Sampling. As more light clients join the network, Avail can support bigger blocks, unlocking significant scaling potential for blockchains.

## Key Repositories under availproject

Below is a curated list of GitHub repositories that are actively tracking the various development efforts related to Avail.

### Get Started

| Repository Name & Link                                                                                                                                      | Description                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| [Reference Document](https://github.com/availproject/data-availability/blob/master/reference%20document/Data%20Availability%20-%20Reference%20Document.pdf) | Comprehensive document outlining the rationale, design decisions, and theoretical foundations. |
| [Avail Node](https://github.com/availproject/avail)                                                                                                         | Repository for the Avail node implementation, built using Substrate.                           |
| [Light Client](https://github.com/availproject/avail-light)                                                                                                 | Light client designed for verifying data availability proofs on Avail.                         |
| [Explorer](https://github.com/availproject/avail-apps)                                                                                                      | Implementation repository for the Avail explorer, built using PolkadotJS Apps.                 |
| [Tests](https://github.com/availproject/avail-test)                                                                                                         | Repository for end-to-end tests designed to validate Avail's functionalities.                  |

### Full List

| Category                                             | Repository Name                                                                          | Description                                              |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| **Core Components**                                  | [Avail](https://github.com/availproject/avail)                                           | Main DA (Data Availability) Node for the Avail project.  |
|                                                      | [Avail Core](https://github.com/availproject/avail-core)                                 | Core components for Avail's data availability layer.     |
| **Light Clients**                                    | [Avail Light](https://github.com/availproject/avail-light)                               | Light client for Avail.                                  |
|                                                      | [Avail Light Bootstrap](https://github.com/availproject/avail-light-bootstrap)           | Bootstrap for Avail Light client.                        |
|                                                      | [Avail Light Relay](https://github.com/availproject/avail-light-relay)                   | Relay for Avail Light client.                            |
| **Applications**                                     | [Avail Apps](https://github.com/availproject/avail-apps)                                 | Repository for applications built on Avail.              |
| **Substrate (now part of Polkadot SDK) Integration** | [Go Substrate RPC Client](https://github.com/availproject/go-substrate-rpc-client)       | RPC client for Substrate integration.                    |
|                                                      | [Substrate](https://github.com/availproject/substrate)                                   | Fork of Substrate for Avail.                             |
| **Explorations**                                     | [Avail Explorations](https://github.com/availproject/avail-explorations)                 | Experimental features and research.                      |
|                                                      | [Avail Sovereign DA Adapter](https://github.com/availproject/avail-sovereign-da-adapter) | Data availability adapter for Sovereign Rollups.         |
| **Tooling**                                          | [CLI](https://github.com/availproject/cli)                                               | CLI tool for Avail.                                      |
|                                                      | [Avail JS](https://github.com/availproject/avail-js)                                     | JavaScript library for Avail; Fork of PolkadotJS         |
| **Contracts and Proofs**                             | [Op EVM Contracts](https://github.com/availproject/op-evm-contracts)                     | EVM contracts for Avail.                                 |
|                                                      | [Poly Multiproof](https://github.com/availproject/poly-multiproof)                       | Multiproof contracts for Avail.                          |
| **SDKs**                                             | [Sovereign SDK](https://github.com/availproject/sovereign-sdk)                           | SDK for Sovereign Rollups on Avail.                      |
| **Proposals**                                        | [RFCs](https://github.com/availproject/RFCs)                                             | Repository for Avail Request for Comments and proposals. |

# Repository Overview

## Configuration Guide

### Static-Site Generator

The [Avail Developer Documentation](https://docs.availproject.org/) is built using [Docusaurus](https://docusaurus.io/), making it easy to serve and host its static files.

### Deployments

The Avail Documentation is deployed across two distinct environments: **staging** and **prod**. Both are configured to operate from the `main` branch of the repository.

- **Staging**: Hosted on Digital Ocean, this environment serves as the testing ground for new changes. It allows for quality assurance and verification before updates are pushed to Production. You can view the staging site [here](https://docs-refresh-2-rjp2q.ondigitalocean.app/).

- **Production (Prod)**: This is the live environment, hosted on GitHub Pages, and is manually deployed by the Avail Documentation team. It is accessible to end-users and receives updates only after they have been successfully validated in the Staging environment.

### Algolia DocSearch

The documentation utilizes [Algolia's DocSearch](https://docsearch.algolia.com/) to provide a powerful and user-friendly search experience. DocSearch is specifically designed to improve navigation in documentation websites, making it easier for users to find the information they need.

### Plausible Analytics

[Plausible Analytics](https://plausible.io/) is integrated into the platform to monitor user interactions. This helps in understanding user engagement and behavior, thereby aiding in the continuous improvement of the documentation.

### Translations

| ❗ The documentation is currently undergoing reorganization and frequent updates in preparation for the Avail mainnet launch. Translation efforts will be prioritized once this is complete. |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

### Files and Folders

This section provides an overview of the various files and folders in the Avail Documentation repository, explaining the purpose of each.

| Name                   | Purpose                                                                    |
| ---------------------- | -------------------------------------------------------------------------- |
| `LICENSE`              | Contains the license information for the project.                          |
| `README.md`            | The main introduction file for the Avail Docs repository.                  |
| `babel.config.js`      | Configuration file for Babel, a JavaScript compiler.                       |
| `build/`               | Contains static content generated for deployment.                          |
| `docusaurus.config.js` | Configuration file for website layout and other Docusaurus settings.       |
| `docs/`                | Contains the Markdown files that make up the content of the documentation. |
| `node_modules/`        | Contains all the npm packages and dependencies.                            |
| `package.json`         | Specifies dependencies and scripts for the project.                        |
| `sidebars.js`          | Used to modify the sidebar navigation.                                     |
| `src/`                 | Contains source files for the project.                                     |
| `static/`              | Contains static assets like images, CSS, and fonts.                        |
| `yarn.lock`            | Yarn lock file to keep track of all package versions.                      |


## Contributors

We are grateful to these amazing folks for their contributions to Avail's docs :) [emoji key](t)

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://13thcodearmy.hashnode.dev/"><img src="https://avatars.githubusercontent.com/u/56264430?v=4?s=100" width="100px;" alt="Priyank Gupta"/><br /><sub><b>Priyank Gupta</b></sub></a><br /><a href="#doc-Genesis3800" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
