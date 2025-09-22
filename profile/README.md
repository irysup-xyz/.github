# IrysUp — A Decentralized Platform for Creative Asset Management

## Overview

IrysUp is an open-source platform designed to enable creators to publish, distribute, and permanently store digital creative assets — including images, icons, and illustrations — on the Irys DataChain. Built on decentralized infrastructure, IrysUp eliminates reliance on centralized storage providers and offers a censorship-resistant alternative to traditional stock asset platforms.

Unlike conventional services, IrysUp does not retain user data on centralized servers. All content is anchored to the blockchain via the Irys DataChain, ensuring immutability, verifiability, and long-term availability. The platform is currently in testnet phase, with full migration to mainnet scheduled for early 2025.

## Key Principles

- **Decentralization**: Assets are stored on-chain via Irys, not on proprietary servers.  
- **Privacy**: No personally identifiable information is collected or stored.  
- **Transparency**: All operations are auditable through blockchain records.  
- **Accessibility**: Designed for non-technical creators — no CLI or blockchain expertise required.  
- **Sustainability**: Zero transaction fees for users during the initial phase.  

## Current Status

IrysUp operates on the Sepolia testnet of the Irys DataChain. All uploaded assets are stored temporarily and subject to automatic deletion after 60 days, in accordance with Irys testnet policy. This phase is intended for functional validation, user feedback, and system optimization prior to mainnet deployment.

Full migration to the Irys mainnet will enable permanent, low-cost, and globally accessible asset storage, with enhanced cryptographic guarantees and economic sustainability.

## Architecture

IrysUp is built using a modern, modular stack:
 
- **Blockchain Layer**: Irys DataChain SDK for data anchoring and manifest generation  
- **Authentication**: WalletConnect integration with Ethereum-compatible wallets (e.g., MetaMask)  
- **Storage**: Irys SDK handles file encoding, IPFS pinning, and Ethereum transaction anchoring  

All user interactions occur through a web interface. No native applications are required.

## Functional Workflow

1. **User Registration**  
   A user registers by connecting an Ethereum-compatible wallet. No email, password, or personal data is stored.

2. **Asset Upload (Creator)**  
   Creators upload digital assets through the web interface. Metadata (title, tags, authorship) is embedded and anchored to the Irys DataChain. A unique manifest identifier is generated.

3. **Asset Access (User)**  
   Any user may browse, download, and use assets freely. Assets are served from temporary backend storage during testnet.

4. **On-Chain Storage (Optional)**  
   Users may choose to re-upload and re-anchor assets to the Irys DataChain via the Irys Storage module, ensuring permanent, decentralized preservation.

5. **Mainnet Transition**  
   Upon migration to mainnet, all asset storage will occur exclusively on-chain. Backend servers will be decommissioned for data persistence.

## Security and Privacy

IrysUp adheres to a strict privacy-by-design model:

- User passwords are encrypted client-side using standard cryptographic primitives.  
- A second encryption layer is applied server-side before storage.  
- Only the final hashed value is persisted in the database.  
- No personally identifiable information is collected, processed, or retained.  
- All on-chain data is publicly verifiable but does not expose user identity.

## Contribution

IrysUp is an open-source project. Contributions are welcome from developers, designers, and blockchain enthusiasts.

To contribute:

1. Fork the repository.  
2. Create a feature branch: `git checkout -b feature/your-feature-name`  
3. Commit changes with clear, descriptive messages.  
4. Push to your fork: `git push origin feature/your-feature-name`  
5. Open a pull request against the `main` branch.

Please ensure all code adheres to established style guidelines and includes appropriate documentation.

Issues labeled “enhancement” and “bug” are prioritized for community contribution. See the [Issues](https://github.com/irysup/irysup/issues) page for current tasks.

## Roadmap

- **Phase 1: Public Launch (Completed)**  
  Initial platform released with core upload, download, and wallet integration functionality.

- **Phase 2: Mobile Responsiveness (In Progress)**  
  Optimization of the web interface for consistent performance across desktop and mobile devices.

- **Phase 3: Feature Expansion**  
  Implementation of metadata tagging, search, licensing indicators, and asset categorization.

- **Phase 4: Full On-Chain Storage**  
  Complete migration of asset storage from temporary servers to the Irys DataChain.

- **Phase 5: Mainnet Deployment**  
  Transition from Sepolia testnet to Irys mainnet, enabling permanent, economically sustainable storage.

## Usage

The live platform is accessible at:  
https://irysup.xyz

Note: All assets on the current deployment are stored on testnet and are subject to deletion after 60 days. Production-grade permanence will be available upon mainnet release.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries, collaboration, or technical support:  
irysupxyz@gmail.com

## Acknowledgments

This project is built upon the foundational work of the Irys team and their DataChain protocol. We acknowledge the broader Web3 community for advancing the principles of decentralized ownership and open access.

---

> IrysUp is not a service. It is a protocol for creative sovereignty.
