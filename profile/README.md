<a href="https://4mica.io"><img src="/profile/banner.png" alt="4Mica – the payment infrastructure for the agentic economy"></a>

# Welcome to 4Mica

4Mica is the clearing house for the agentic economy: a credit layer for the [x402](https://docs.4mica.io/core-concepts/how-x402-works) HTTP payment standard. A payer deposits collateral once, then signs an off-chain payment guarantee for every request. Guarantees are verified in milliseconds, netted over settlement cycles, and only net positions settle on-chain. Collateral stays non-custodial and earns yield through ERC-4626 strategies such as Aave.

Start with the [Quickstart](https://docs.4mica.io/getting-started/quickstart), browse the full [documentation](https://docs.4mica.io), and check the [supported networks](https://docs.4mica.io/getting-started/supported-networks) (Base Sepolia, Base mainnet, Ethereum Sepolia).

## Build on 4Mica

- **Pay for APIs** – build an agent or client that pays per request with signed guarantees instead of on-chain transactions. [Buyer quick start](https://docs.4mica.io/buyer/quick-start) · [Make paid requests automatically](https://docs.4mica.io/buyer/make-paid-requests-automatically)
- **Get paid for APIs** – gate an API, model, dataset, or workflow behind an x402 paywall with middleware for Express, Hono, Next.js, FastAPI, or Flask. [Seller quick start](https://docs.4mica.io/seller/quick-start) · [Payment middleware](https://docs.4mica.io/seller/payment-middleware)
- **Facilitators** – verify and settle 4Mica credit payments from an existing x402 integration, or run your own facilitator. [How facilitators work](https://docs.4mica.io/core-concepts/facilitator) · [facilitator-4mica](https://github.com/4mica-Network/facilitator-4mica)

## SDKs

| Language | Package | Source |
| --- | --- | --- |
| TypeScript | [`@4mica/sdk`](https://www.npmjs.com/package/@4mica/sdk) with adapters for Node, Express, Hono, Next.js, and Deno | [packages/sdk](https://github.com/4mica-Network/4mica/tree/main/packages/sdk) |
| Python | [`sdk-4mica`](https://pypi.org/project/sdk-4mica/) | [packages/sdk-python](https://github.com/4mica-Network/4mica/tree/main/packages/sdk-python) |
| Rust | [`sdk-4mica`](https://crates.io/crates/sdk-4mica) | [packages/sdk-rust](https://github.com/4mica-Network/4mica/tree/main/packages/sdk-rust) |
| CLI | [`@4mica/cli`](https://www.npmjs.com/package/@4mica/cli) | [packages/cli](https://github.com/4mica-Network/4mica/tree/main/packages/cli) |

## Repositories

- [4mica](https://github.com/4mica-Network/4mica) – monorepo with the web platform, docs, SDKs, CLI, and examples
- [facilitator-4mica](https://github.com/4mica-Network/facilitator-4mica) – x402 facilitator that runs the 4Mica credit flow
- [4mica-integration-demo](https://github.com/4mica-Network/4mica-integration-demo) – pay-per-segment video streaming paid with x402 and 4Mica
- [4mica-polygon-demo](https://github.com/4mica-Network/4mica-polygon-demo) – 4Mica payments demo on Polygon

## Resources

[Website](https://4mica.io) • [Docs](https://docs.4mica.io) • [Changelog](https://docs.4mica.io/updates/changelogs) • [X](https://x.com/0x4Mica) • [LinkedIn](https://www.linkedin.com/company/4mica)
