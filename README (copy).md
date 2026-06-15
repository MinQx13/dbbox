# Decentralized Black Box dApp

## Project Title
Decentralized Black Box dApp

## Project Description
A full-stack decentralized application (dApp) built on the Stellar blockchain utilizing Soroban smart contracts. This dApp acts as an on-chain "black box" for ride-hailing/transport drivers. It allows drivers to purchase insurance packages, and enables an authorized AI Server to automatically analyze accident telemetry, process claims, and permanently store verified accident reports with programmatic compensation calculation on-chain.

## Project Vision
The vision of Decentralized Black Box is to offer the transportation and insurance industries a decentralized, unalterable, and automated way to handle driver insurance policies and accident settlements without relying on slow, centralized intermediaries. This guarantees transparent data verification, instant programmatic compensation enforcement for victims, and eliminates fraudulent claim reports, significantly increasing user trust and operational reliability.

## Key Features
1. **Insurance Management:** Drivers can register and buy insurance policies that instantly grant them an active status, with coverage duration calculated natively on-chain.
2. **AI-Driven Automated Claims:** An authorized AI Server can programmatically trigger accident reports after evaluating telemetry data and dashcam footage hashes.
3. **Dynamic Tier-Based Compensation:** The smart contract automatically parses the damage level of an accident to calculate and allocate appropriate compensation tiers (e.g., Level 1, 2, or 3).
4. **Immutable Accident Records:** All processed accidents, video evidence hashes, and payout logs are permanently recorded on-chain for public auditability.
5. **Access Control:** System-restricted administrative initialization controls contract deployment, while specific functional constraints ensure only authorized AI servers can file claims.
6. **Transparent Status Tracking:** Anyone can query a driver's insurance validity or review accident settlement histories publicly on the blockchain ledger.
## Usage Instructions
1. - **Set Admin & Server:** Deploy the contract and assign the core system administrator and the authorized AI Server address.
2. - **Buy Insurance:** Drivers interact with the contract to activate their 30-day coverage cycle using their authenticated wallets.
3. - **Trigger Compensation:** Upon an incident, the authorized AI server signs a transaction containing the incident ID, driver address, victim address, video hash, and analyzed damage level.
4. - **Automated Settlement:** The contract validates the driver's insurance status, locks the calculated compensation amount, and flags the report as settled.
5. - **Query Settle State:** Anyone can reference the unique transaction or contract state data to verify accident compliance and payout values.

## Future Scope
- **Native Payment Execution:** Integrate native Stellar/Soroban tokens (XLM or custom assets) to dynamically handle insurance premiums and automatically release escrow funds to victims.
- **Advanced Telemetry Oracles:** Connect decentralized hardware oracles (IoT black boxes inside vehicles) to stream tamper-proof data directly to the smart contract.
- **Multi-Vehicle Fleets:** Support fleet management structures allowing delivery and ride-hailing companies to manage multiple drivers under a centralized corporate insurance contract.
- **User & Admin Dashboards:** Build an intuitive, responsive frontend interface using ReactJS and TailwindCSS for drivers to buy insurance and view their historical records.
- **IPFS Video Integration Player:**Decentralize accident proof storage by linking verified video hashes directly to playable IPFS nodes on the user interface.

## Technology Stack
- Rust and Soroban SDK for secure smart contract development.
- Stellar blockchain for decentralized, immutable state management.
- Cryptographic signing and timestamping for secure subscription enforcement.

## Contribution
Community contributions are welcomed from blockchain developers, web3 engineers, and smart contract auditors. Please fork the repository and submit a pull request with your planned feature enhancements.

## License
This project is licensed under the MIT License.

### Contract Detail
ID: CDEC3ZK4NAEV5ZTLMIALMYPGC3DKVT56JTZN2FYRN3KZVLTUR6LBVYYR
