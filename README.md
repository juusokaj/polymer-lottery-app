# Polymer lottery app

Technologies used:

- Nuxt 3
- Bootstrap 5
- Web3Modal v2
- Wagmi / use-wagmi
- Viem

### Live version: https://lottery.tuananh.xyz

## Setup

Make sure to install the dependencies:
```bash
# yarn
yarn install
```

Copy `.env.example` to `.env` and fill in the required environment variables.

You can get the `WALLET_CONNECT_PROJECT_ID` from [WalletConnect](https://walletconnect.org/apps).

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# yarn
yarn dev
```

## Production

Build the application for production:

```bash
# yarn
yarn build
```

Locally preview production build:

```bash
# yarn
yarn preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
