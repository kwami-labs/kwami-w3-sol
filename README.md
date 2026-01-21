# Kwami Solana Programs

Solana smart contracts for the Kwami ecosystem, built with Anchor framework.

## Programs

- **qwami_token**: Token program for QWAMI token
- **kwami_nft**: NFT minting and management program
- **kwami_dao**: DAO governance program

## Prerequisites

- Rust 1.75+
- Solana CLI 1.18+
- Anchor CLI 0.32.1+
- Node.js 18+

## Setup

1. Install dependencies:
```bash
npm install
```

2. Build the programs:
```bash
anchor build
```

3. Run tests:
```bash
anchor test
```

## Deployment

### Devnet
```bash
anchor deploy --provider.cluster devnet
```

### Mainnet
```bash
anchor deploy --provider.cluster mainnet
```

## Program Addresses

### Devnet
- qwami_token: `6CAgdgpPq8Np78LsDwREJqFPh9rM5Jh6RSS8eZ37kZuv`
- kwami_nft: `6W3VGmDkjwswpY8JNNDQH5f1VuCdqrttR6koWPkN7drr`
- kwami_dao: `6j64Ct74mypeT3UKVhtFUjBW8RX144VvxWJjH9iBqbAv`

## Scripts

- `npm run init:kwami-nft`: Initialize the Kwami NFT program

## Development

The project uses Anchor framework for Solana program development. Each program is located in the `programs/` directory with its own Cargo.toml and lib.rs.

## License

MIT
