# concordium-testnet-faucet

## Development

Create the .env.local file and fill up the variables.

```bash
cp .env.example .env.local
```

Example enviroment variable values

```bash
NEXT_PUBLIC_EXPLORER_API_URL=https://wallet-proxy.testnet.concordium.com/v1
NEXT_PUBLIC_EXPLORER_URL=https://ccdexplorer.io/
NEXT_PUBLIC_SENDER_ADDRESS=4eDtVqZrkmcNEFziEMSs8S2anvkH5KnsYK4MhwedwGWK1pmjZe
NEXT_PUBLIC_USAGE_LIMIT_IN_DAYS=1
NEXT_PUBLIC_CLOUDFLARE_TURNSTILE_SITE_KEY=3x00000000000000000000FF
NODE_URL=node.testnet.concordium.com
NODE_PORT=20000
CCD_DEFAULT_AMOUNT=1
SENDER_PRIVATE_KEY=12...34
```

Note: The `3x00000000000000000000FF` value in the `NEXT_PUBLIC_CLOUDFLARE_TURNSTILE_SITE_KEY` is a site key provided by Cloudflare for testing purposes; it works fine locally. For setting up the Cloudflare Turnstile service in production, please refer to this [guide](docs/turnstile/SETUP.md).
---

## Portfolio Context

**Completed bounty project** demonstrating blockchain infrastructure development and Web3 user experience design.

### What Was Built

A user-friendly testnet faucet for the Concordium blockchain:

- **Next.js Frontend:** Modern web application with responsive design
- **Cloudflare Turnstile:** Bot protection for fair token distribution
- **Usage Limits:** Per-address daily limits to prevent abuse
- **Explorer Integration:** Real-time balance checking via Concordium explorer API
- **Documentation:** Complete setup guide for Cloudflare Turnstile integration

### Technical Achievements

- Built production-ready faucet with anti-bot protection
- Integrated Cloudflare Turnstile for seamless user verification
- Implemented per-address usage limits and cooldown periods
- Connected to Concordium testnet node for transaction broadcasting
- Created comprehensive documentation for deployment and configuration

### Skills Demonstrated

TypeScript, Next.js, Tailwind CSS, Concordium SDK, Cloudflare Turnstile, Blockchain Infrastructure, Web3 UX Design

---

*Completed 2024. Deployed on Concordium testnet.*
