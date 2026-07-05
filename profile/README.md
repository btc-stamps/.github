<div align="center">

# btc-stamps

**Open-source tooling for the Bitcoin Stamps protocol.**

[![Docs](https://img.shields.io/badge/docs-bitcoinstamps.xyz-F7931A?logo=bitcoin&logoColor=white)](https://bitcoinstamps.xyz)
[![Explorer](https://img.shields.io/badge/explorer-stampchain.io-F7931A?logo=bitcoin&logoColor=white)](https://stampchain.io)
[![npm](https://img.shields.io/npm/v/@btc-stamps/tx-builder.svg?label=tx-builder)](https://www.npmjs.com/package/@btc-stamps/tx-builder)
[![Telegram](https://img.shields.io/badge/community-Telegram-26A5E4?logo=telegram&logoColor=white)](https://t.me/BitcoinStamps)

</div>

Libraries, SDKs, and developer tools for building on [Bitcoin Stamps](https://bitcoinstamps.xyz): unprunable data storage on Bitcoin's UTXO set. Stamps embed data directly in Bitcoin transactions where node operators cannot prune it, making every stamp a permanent on-chain artifact.

**btc-stamps** is the tooling and libraries home. The reference indexer, public API, and protocol specifications live in the sibling [**stampchain-io**](https://github.com/stampchain-io) organization. Founded by [mikeinspace](https://x.com/mikeinspace), Arwyn, and Reinamora; mascot: KEVIN.

### Protocols

**SRC-20** (fungible tokens) · **SRC-101** (naming) · **SRC-721** (NFTs) · **SRC-721r** (recursive stamps) · **OLGA** (P2WSH encoding)

Full specifications and guides at [bitcoinstamps.xyz](https://bitcoinstamps.xyz).

### Libraries & Tools

| Repository | Description |
|------------|-------------|
| [**tx-builder**](https://github.com/btc-stamps/tx-builder) | Transaction builder for Bitcoin Stamps and SRC-20 metaprotocols ([NPM](https://www.npmjs.com/package/@btc-stamps/tx-builder) · [JSR](https://jsr.io/@btc-stamps/tx-builder)) |
| | [![Node.js CI](https://img.shields.io/github/actions/workflow/status/btc-stamps/tx-builder/ci.yml?branch=main)](https://github.com/btc-stamps/tx-builder/actions) [![codecov](https://codecov.io/gh/btc-stamps/tx-builder/graph/badge.svg?token=AWB6I9Z0AQ)](https://codecov.io/gh/btc-stamps/tx-builder) [![npm](https://img.shields.io/npm/v/@btc-stamps/tx-builder.svg)](https://www.npmjs.com/package/@btc-stamps/tx-builder) [![JSR](https://jsr.io/badges/@btc-stamps/tx-builder)](https://jsr.io/@btc-stamps/tx-builder) |
| [**bitcoinstamps.xyz**](https://github.com/btc-stamps/bitcoinstamps.xyz) | Official protocol documentation and developer guides at [bitcoinstamps.xyz](https://bitcoinstamps.xyz) (VitePress, 7 languages) |
| | [![CI](https://github.com/btc-stamps/bitcoinstamps.xyz/actions/workflows/ci.yml/badge.svg)](https://github.com/btc-stamps/bitcoinstamps.xyz/actions/workflows/ci.yml) [![Deploy](https://github.com/btc-stamps/bitcoinstamps.xyz/actions/workflows/deploy-cloudflare.yml/badge.svg)](https://github.com/btc-stamps/bitcoinstamps.xyz/actions/workflows/deploy-cloudflare.yml) |
| [**spellbook**](https://github.com/btc-stamps/spellbook) | SQL views for Dune analytics |

### Ecosystem

The core Bitcoin Stamps indexer and explorer live in the [**stampchain-io**](https://github.com/stampchain-io) organization:

- [**btc_stamps**](https://github.com/stampchain-io/btc_stamps): indexer for all Bitcoin Stamps transactions
- [**stampchain.io**](https://github.com/stampchain-io/stampchain.io): REST API and block explorer at [stampchain.io](https://stampchain.io)
- [**stamps_sdk**](https://github.com/stampchain-io/stamps_sdk): TypeScript SDK for building with Bitcoin Stamps
- [**stampchain-mcp**](https://github.com/stampchain-io/stampchain-mcp): MCP server for AI integration

### Links

- [bitcoinstamps.xyz](https://bitcoinstamps.xyz): protocol home and documentation
- [stampchain.io](https://stampchain.io): explorer and minting tools
- [API Documentation](https://stampchain.io/docs): OpenAPI reference
- [Telegram](https://t.me/BitcoinStamps): community chat

---

<div align="center">

Built with Bitcoin. Permanent by design. 🧡

</div>
