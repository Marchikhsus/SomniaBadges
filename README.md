# SomniaBadges
NFT badge system for the Somnia ecosystem
# SomniaBadges

**SomniaBadges** is a simple and powerful NFT badge system built on the [Somnia blockchain](https://somnia.network), designed to reward user activity across dApps, games, and metaverse experiences.

This project allows users to mint unique ERC-721 NFT badges based on on-chain actions — like completing transactions, holding assets, or participating in community events.

---

## Features

- **ERC-721 NFT Badge System**
- On-chain minting by admin (can be automated later)
- IPFS-hosted metadata & images
- Simple frontend UI (HTML or React)
- Deployed on Somnia testnet

---

## Use Cases

- Reward users for being early adopters
- Grant badges for completing tasks (SocialFi, DeFi, etc.)
- Track participation in DAO proposals
- Gamify engagement in metaverse and Somnia apps

---

## Smart Contract

- File: `contracts/BadgeNFT.sol`
- Standard: `ERC-721` with `URIStorage` from OpenZeppelin
- Function: `mintBadge(address recipient, string memory tokenURI)`

---

## Project Structure

---

## Deployment

This project is deployed on **Somnia Testnet** (EVM-compatible).
To deploy:

1. Use [Remix IDE](https://remix.ethereum.org)
2. Load `BadgeNFT.sol`
3. Compile & deploy to Somnia RPC
4. Mint using IPFS-hosted metadata

---

## Author

Bogdan — [GitHub](https://github.com/bm8marchik) 
Email: bm8marchik@gmail.com

---

## License

MIT License

