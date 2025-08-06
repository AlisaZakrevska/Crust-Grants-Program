# Crust Grant Proposal DexGo

* **Project Name:**  DexGo 
* **Team Name:** DexStudios
* **Payment Address:** 0xF52e9dA33fFde0a12418e93CE6Fe8B5691212164
* **Receivable Token:** USDT

### Overview

- **Project Name:** DexGo
- **Brief Description:** DexGo is a Move-to-Earn mobile game powered by AR technologies, where users earn by walking real-world routes. The app transforms city walks into gamified adventures, allowing users to explore hidden locations, complete tasks, and monetize their activity using NFTs and personalized content creation.
- **Integration with Crust:** DexGo plans to integrate Crust for decentralized storage of user-generated routes, AR assets, and location-based gameplay data. This enhances data security, permanence, and user ownership—key to the decentralized vision of Web3 gaming.
- **Why We're Building It:** We're building DexGo to motivate people to walk more, rediscover their cities, and interact with the real world through digital layers. We’re passionate about blending gaming, wellness, and Web3 tools like Crust to create more meaningful outdoor experiences and build a community-driven metaverse rooted in physical reality.

### Project Details 
DexGo is a Move-to-Earn AR game where users earn rewards by walking real-world routes. The app uses GPS, augmented reality, NFTs, and blockchain.

## Live App
- Android: https://play.google.com/store/apps/details?id=app.dexgo.android  
- iOS: https://apple.co/3ZIrrC8  
- Pitch Deck: https://t.co/SySPqyYBDi  
- Video Pitch: https://vimeo.com/933655388

## Stack
- Unity (client)  
- Node.js / PostgreSQL  
- Solidity (EVM)  
- Crust Network + IPFS (planned)

## Status
- 15M+ video views  
- $20K+ NFT sales  
- Available on Android and iOS

### Ecosystem Fit 

DexGo fits into the Crust ecosystem as a consumer-facing dApp that brings decentralized storage into a real-world gaming context. We plan to use Crust to store user-generated route data, AR assets, and gameplay metadata, ensuring verifiability, permanence, and censorship resistance.
Our project meets the need for secure, decentralized storage of dynamic, user-driven geolocation data and game assets. Centralized storage in similar apps creates risks of data loss, tampering, and lack of ownership. Crust helps us solve this by offering decentralized infrastructure for our location-based metaverse features.
To our knowledge, there are no direct Move-to-Earn AR games using IPFS/Crust. While some fitness or NFT apps store metadata on-chain or in centralized systems, DexGo combines real-world movement, NFTs, AR, and Crust-based storage in a single mobile experience. This makes us unique not only within the Crust ecosystem but across the broader Web3 gaming landscape.

## Team

### Team members
Oleksii Vinogradov: A serial entrepreneur and investor with 25 years of experience, founder of CFC and Heartln Inc., and President/Owner of IXC Softswitch.
Oleg Bondar: Chief Executive Officer with over 12 years of experience in leading companies focused on developing retail stores for various global brands.
Eugene Luzgin: A problem solver with a diverse background in the software industry, from contributor to startup founder, responsible for managing investor relationships.
Inna Koliasnikova: With four years of experience in product testing across mobile and web applications, I also focus on business development and strategic representation in international markets, enhancing product quality through client and partner interactions.
Denis Leschinskiy - is a Unity designer who specializes in 2D and 3D character art production. Highly efficient with high/low resolution sculpting, texturing techniques, rigging, skinning, lighting, and rendering.

### Contact
* **Contact Name:** Alisa Zakevska
* **Contact Email:** alisa@dexgo.club

### Legal Structure 
* **Registered Address:** 7950 NW 53rd Street, Suite 337, Miami, Florida 33166
* **Registered Legal Entity:** IXC Global 

### Team's experience
Our founding team possesses a unique combination of domain expertise in both blockchain technology and game development, providing us with a deep understanding of the challenges and opportunities at the intersection of these fields. Additionally, our extensive network within the gaming and blockchain communities gives us access to valuable partnerships and resources, enhancing our ability to execute our vision effectively. This blend of expertise and connections creates a formidable advantage that would be challenging for another team to replicate.

### Team Code Repos
https://github.com/oleksiivinogradov/

### Team LinkedIn Profiles
- Alex Vinogradov - founder - https://www.linkedin.com/in/oleksiivinogradov/
- Oleg Bondar - CEO - https://www.linkedin.com/in/oleg-bondar-820710246/
- Denis Leschinskiy - designer, developer - https://www.linkedin.com/in/denis-leschinsky-78
- Inna Koliasnikova - QA/BD - https://www.linkedin.com/in/inna-koliasnikova-066098156/

## Development Roadmap

Over three months, we will integrate Crust as DexGo’s decentralized storage layer.
In Month 1, we’ll connect our backend to Crust IPFS. Route data, AR assets, and metadata will be uploaded, with CIDs returned and verified. We’ll provide full documentation, a Dockerfile, and tests for storage and retrieval.
In Month 2, we’ll link Crust to our NFT system. Sneaker and route metadata will be stored on Crust, and CIDs will be embedded in token URIs. We’ll publish API docs, metadata examples, and test suites for the NFT minting flow.
In Month 3, we’ll launch Crust-backed publishing for user-generated routes. All content will be CID-verified before use, and a public dashboard of verified routes will go live. This milestone includes full E2E tests, tutorials, and Docker environments.
By the end, DexGo will rely on Crust for secure, verifiable, user-owned storage.

## DexGo x Crust Roadmap

### Overview
- **Total Estimated Duration:** 3 months  
- **Full-Time Equivalent (FTE):** 3 FTE  
- **Total Costs:** 30,000 USD


### Milestone 1 — Crust Integration Backend
- **Estimated Duration:** 1 month  
- **FTE:** 1  
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| ------:|-------------|----------------|
| 0a. | License | MIT |
| 0b. | Documentation | Tutorial and architecture diagram on storing route data and assets to Crust IPFS from backend. |
| 0c. | Testing Guide | Unit and integration tests for storage, retrieval, CID verification. |
| 0d. | Dockerfile | Includes local dev setup with Crust IPFS integration. |
| 1. | Store & fetch routes | Functions to upload/download route metadata and AR files via Crust. |
| 2. | CID validation | Verification of IPFS CID integrity from client side. |


### Milestone 2 — NFT Metadata with Crust
- **Estimated Duration:** 1 month  
- **FTE:** 1  
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| ------:|-------------|----------------|
| 0a. | License | MIT |
| 0b. | Documentation | API docs for NFT minting with Crust metadata, example JSON metadata. |
| 0c. | Testing Guide | Test coverage for upload, validation, minting process. |
| 0d. | Dockerfile | Crust + EVM environment (e.g. Hardhat). |
| 1. | Metadata Upload | Store sneaker/route metadata to Crust and link in tokenURI. |
| 2. | Contract Update | Modify NFT contract to emit metadata CID for on-chain traceability. |


### Milestone 3 — User-Generated Route Publishing
- **Estimated Duration:** 1 month  
- **FTE:** 1  
- **Costs:** 12,000 USD

| Number | Deliverable | Specification |
| ------:|-------------|----------------|
| 0a. | License | MIT |
| 0b. | Documentation | Guide to create, publish and verify Crust-based routes. |
| 0c. | Testing Guide | Full E2E tests: publish, fetch, verify content. |
| 0d. | Dockerfile | Full stack docker-compose with backend + verification logic. |
| 1. | Content Publishing | Allow users to submit routes pinned to Crust. |
| 2. | Verification Layer | Client-side hash check before displaying route. |
| 3. | Public Dashboard | Show published routes, CIDs, and authors. |


## Future Plans

In the short term, we plan to support Crust as our main storage layer for all game metadata and route assets. We will promote this feature to players and NFT holders through in-game content and social channels.

Long-term, we intend to move all DexGo user-generated content to Crust, expand to new regions, and introduce DAO voting mechanisms for route curation, where CID-backed content plays a key role in governance and transparency.
