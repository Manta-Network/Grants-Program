# Manta Wallet

- **Team Name:** Manta Wallet
- **Payment Address:** Ethereum(USDT/DAI/USDC)
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 3

## Project Overview :page_facing_up:

A crypto wallet on Manta network.
Manta wallet is an extension that lets you explore the Manta ecosystem in your browser.
With the browser extension installed, Manta wallet allows you to engage with Web3 apps on the Manta blockchain.

#### The Manta wallet Browser Extension lets you:
- Create wallet accounts with both public address and zkAddress with a single mnemonic.
- Import, and persistently store the mnemonics and the derived private key.
- View public assets and zkAssets in the wallet.
- Connect to DApps and sign human-readable transactions from trusted DApps.
- zkAssets public2Private, private2Private, private2Public
- Show your recent public / private transactions

#### We Keep You Safe
- Manta wallet encrypts your keys and mnemonics on your device.
- Import private keys and mnemonics into your wallet.
- Rotate your private key from within the wallet if needed.
- Easily review and simulate transactions before signing them.


### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- An overview of the technology stack to be used
  React、TypeScript、Less、Ant-Design、Umi、Koa
- Documentation of core components, protocols, architecture, etc. to be deployed
  https://github.com/Manta-Network/manta-extension/blob/develop/README.md#get-start


## Team :busts_in_silhouette:

> Please note that the data provided in this section is for administrative and informational purposes only. All beneficiaries of a grant must also be listed in the KYC/KYB process during the application phase. See our [FAQ](https://grants.web3.foundation/docs/faq#what-is-kyckyb-and-why-do-i-have-to-provide-this-data) for more info.

### Team members

- **Victor Ji, Co-Founder**.
- **Kenny Li, Product Lead**.
- **Chloe Wang, Project Manager**.
- **Ye Han, Product Designer**.
- **Joly Cao, Quality Assurance Engineer**.
- **Can Jin, Frontend Engineer**.
- **Daniel Zhang, Full-stack Engineer**.
- **Vern Zhang, Full-stack Engineer**.

### Contact

- **Contact Name:** Vern Zhang
- **Contact Email:** vern@manta.network
- **Website:** https://manta.network/

### Legal Structure

Manta Network Ltd., a British Virgin Islands corporation

### Team's experience

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past.

If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.

- Victor Ji: Victor is a Harvard University Economics Master. Binance Evangelist. Advisor to Unifi Protocol. He previously served as the Chair of Harvard Kennedy School Blockchain and Cryptocurrency PIC. He is a columnist of Chainnews, 8Btc, Mars finance. Before Harvard, he was the executive partner of BitBlock Capital and worked at Ontology.

- Kenny Li: Kenny is an entrepreneur that has started, advised, and invested in startups for over seven years. His initial business exposure in the cryptocurrency space was an advisory role for a Bitcoin options trading platform in 2014. He is a frequent writer on blockchain topics and operates a fund. He is the teaching assistant for Blockchain Lab and MBA graduate at MIT Sloan.


### Team Code Repos

- <https://github.com/Manta-Network/manta-extension>
- <https://github.com/Manta-Network/sdk>

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- Vern Zhang: https://github.com/vern-manta
- Daniel Zhang: https://github.com/DanielZhangReal
- Can Jin: https://github.com/jincan39

### Team LinkedIn Profiles (if available)

- Victor Ji: <https://www.linkedin.com/in/canghai-victor-ji-cpa-37688a5b/>
- Kenny Li: <https://www.linkedin.com/in/kennymuli>


## Development Status :open_book:

Manta Wallet has been released for more than half a year.
It is the wallet with the second largest number of users in the Polkadot ecosystem (the first is the official Polkadot.js)

- Total Chrome Store users 215K+ https://chrome.google.com/webstore/detail/enabgbdfcbaehmbigakijjabdpdnimlg
- Manta Wallet has developed a total of 28 versions
- xxx zkAddresses activated on Manta Wallet
- xxx transactions related to zk on Manta Wallet.


## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 7 months
- **Full-Time Equivalent (FTE):**  5
- **Total Costs:** 310,000 USD

### Milestone 1 — Basic functionality

- **Estimated duration:** 3 months
- **FTE:**  5
- **Costs:** 150,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | MIT |
| **0b.** | Documentation | Early technology and product research, wallet UI and basic functions, ZK related SDK design |
| 1. | Pre-technical conditions: 1 | Run Singer SDK in Extension |
| 2. | Pre-technical conditions: 2 | Store and encrypt/decrypt seed from storage |
| 3. | Pre-technical conditions: 3 | Design lock and unlock logic |
| 4. | Pre-technical conditions: 4 | Sync UTXO data to IndexedDB |
| 5. | Pre-technical conditions: 5 | Token structure design |
| 6. | Pre-technical conditions: 6 | Transaction structure design |
| 7. | Pre-technical conditions: 7 | Wallet structure design |
| 8. | Pre-technical conditions: 8 | Provider Inject |
| 9. | Page & UI Task: 1 | Create/import workflow - Choose create/import |
| 10. | Page & UI Task: 2 | Create/import workflow - Create password |
| 11. | Page & UI Task: 3 | Create/import workflow - Wallet import input |
| 12. | Page & UI Task: 4 | Create/import workflow - Wallet create seed/mask |
| 13. | Page & UI Task: 5 | Create/import workflow - Account details |
| 14. | Page & UI Task: 6 | Home page - Menu bar |
| 15. | Page & UI Task: 7 | Home page - Total Balance |
| 16. | Page & UI Task: 8 | Home page - Token Balance List |
| 17. | Page & UI Task: 9 | Home page - Network Choose |
| 18. | Page & UI Task: 10 | Home page - Private/Public Choose |
| 19. | Page & UI Task: 11 | Home page - Address Display |
| 20. | Page & UI Task: 12 | Home page - Account Details Link |
| 21. | Page & UI Task: 13 | Account Setting - Rename account |
| 22. | Page & UI Task: 14 | Account Setting - View recovery phrase |
| 23. | Page & UI Task: 15 | Account Setting - Delete Account |
| 24. | Page & UI Task: 16 | Account Setting - Unlock wallet |
| 25. | Page & UI Task: 17 | Dapp - DApp connected list |
| 26. | Page & UI Task: 18 | Dapp - DApp connection request |
| 27. | Page & UI Task: 19 | Dapp - DApp Signature request |
| 28. | Page & UI Task: 20 | Dapp - DApp disconnect action |


### Milestone 2 — SDK features & Wallet features

- **Estimated Duration:** 2 month
- **FTE:**  5
- **Costs:** 100,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | MIT |
| **0b.** | Documentation | SDK features & Wallet features |
| 1. | Sync Data: 1 | Sync page |
| 2. | Sync Data: 2 | Sync loading page |
| 3. | Sync Data: 3 | Initialization page |
| 4. | Sync Data: 4 | Home page balance sync |
| 5. | SDK: 1 | Ledger data checkpoint sync |
| 6. | SDK: 2 | New users sync the UTXO data. Improve initialization performance |
| 7. | SDK: 3 | Implacement parsed data save |
| 8. | SDK: 4 | PR Check CI |
| 9. | SDK: 5 | Build private-related transactions on DApp, https://github.com/Manta-Network/sdk/tree/signer_extension/manta-js#if-you-want-to-connect-manta-wallet-in-your-dapp-build-private-related-transactions |
| 10. | SDK: 6 | Integrate the SDK into your wallet, https://github.com/Manta-Network/sdk/tree/signer_extension/manta-js#if-you-want-to-test-the-sdk-or-integrate-the-sdk-into-your-wallet |
| 11. | SDK: 7 | zkSBT related features, https://github.com/Manta-Network/sdk/tree/signer_extension/manta-js#if-you-want-to-test-zksbt-related-functions |
| 12. | Private Transaction: 1 | Transfer assets from Public to Private |
| 13. | Private Transaction: 2 | Transfer zkAssets from Private to Private |
| 14. | Private Transaction: 3 | Transfer zkAssets from Private to Public |

### Milestone 3 — Audit and Release

- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 30,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | MIT |
| **0b.** | Documentation | Chrome Web Store & Security audit |
| 1. | Technical checklist: 1 | Google developer account apply / Group Account |
| 2. | Technical checklist: 2 | Banner & cover & description document |
| 3. | Technical checklist: 3 | Privacy policy links |
| 4. | Technical checklist: 4 | Code organization before audit |
| 5. | Technical checklist: 5 | Handle audited issues and confirm audit reports |


### Milestone 4 — Optimize Wallet

- **Estimated Duration:** 1 month
- **FTE:**  3
- **Costs:** 30,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | MIT |
| **0b.** | Documentation | Optimize Wallet |
| 1. | Wallet: 1 | Integration Manta Network |
| 2. | Wallet: 2 | Sync Transaction State from chain |
| 3. | Wallet: 3 | Sync Transaction  history from chain |
| 4. | Wallet: 4 | Sync balance when tx successful |
| 5. | Wallet: 5 | Transaction detail and lists |
| 6. | Wallet: 6 | Auto clean ledger data |
| 7. | Wallet: 7 | Update Total Balance when change network |
| 8. | Wallet: 8 | Sync token list from github configuration url |
| 9. | Wallet: 9 | Save Network data to indexedDB |
| 10. | Wallet: 10 | Disconnect dApp |
| 11. | SDK: 1 | UTXO consolidation |
| 12. | SDK: 2 | Add a retry mechanism to the initial_sync |
| 13. | SDK: 3 | Add caching to the getMetadata interface that takes up too much bandwidth |
| 14. | SDK: 4 | Add sdk node example |
| 15. | SDK: 5 | Add Api estimateTransferPostsCount and consolidateTransferSend |
| 16. | SDK: 6 | Add ledger sync progress, total ledger count and synced ledger count api |


## Future Plans

Please include here

- The EVM function will be developed next
- Continue to promote Manta Wallet
