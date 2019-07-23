# Release notes

## Chainstack 1.2.1

*July 1, 2019*

### What’s New
* **Documentation**. New guide: [Deploying a hybrid MultiChain network](/operations/deploying-a-hybrid-multichain-network). New tutorial: [Loyalty program on Quorum](/developer-materials/loyalty-program-on-quorum)

### Bug Fixes
* Improved Ropsten nodes syncing

## Chainstack 1.2

*June 21, 2019*

### What’s New
* **Protocols**. [Ethereum](/blockchain-essentials/ethereum) Ropsten testnet support with Bolt. Updated [Quorum](/blockchain-essentials/quorum) explorer from [blk-explorer-free](https://github.com/blk-io/blk-explorer-free) to [epirus-free](https://github.com/blk-io/epirus-free)
* **Node details**. Added complete details for [Quorum](/blockchain-essentials/quorum), including default wallet private/public keys. Standardized fields for all protocols
* **Documentation**. New tutorial: [Academic certificates on Ethereum](/developer-materials/academic-certificates-on-ethereum)

### Bug Fixes
* Numerous UI and copy fixes and improvements

## Chainstack 1.1.1

*May 9, 2019*

### What’s New
* **Protocols**. Shared [Ethereum](/blockchain-essentials/ethereum) Mainnet nodes support
* [**Projects**](/key-concepts/project). Made project description field optional

### Bug Fixes
* Issues with MultiChain stability
 
## Chainstack 1.1

*May 3, 2019*

### What’s New
* **Updating and deleting resources**. Editing project name and description, network and node name. Deleting nodes by the owner, networks are deleted automatically when the last node is deleted, projects can be deleted if empty
* **Navigation**. Updated menu with links to [Documentation](../) and [Support](https://support.chainstack.com)
* **Support**. Added Zendesk widget

### Bug Fixes
* Sign up markup issues
* Adjusted columns in network/node list
 
## Chainstack 1.0.2

*April 11, 2019*

### What’s New
* **Protocols**. [MultiChain](/blockchain-essentials/multichain) 2.0 release support. [Quorum](/blockchain-essentials/quorum) 2.2.3 support

### Bug Fixes
* MultiChain explorer lack of connectivity
* Project invitations duplicates
* Clearing the cookies on log out without a valid token
 
## Chainstack 1.0.1

*April 2, 2019*

### What’s New
* **Registration and sign in**. Password recovery via email

### Bug Fixes
* Provided links to documentation, ToS and Privacy Policy
* Sorting by date in the network list
 
## Chainstack 1.0

*March 17, 2019*

* **Registration and sign in**. Signing up via email, password and personal details. Signing up for a member invited to the project. Email confirmation on successful registration. Email verification
* [**Consortium project**](/key-concepts/consortium-project). Wizards to create a new network and add a node to the existing network. Invitation of other organizations as members to the project via email
* [**Public chain project**](/key-concepts/public-chain-project). Wizards to join a public network and add another node
* **Protocols**. [MultiChain](/blockchain-essentials/multichain) 2.0-beta-1 support with blockchain explorer. [Quorum](/blockchain-essentials/quorum) 2.2.1 support with [Raft](/blockchain-essentials/quorum#raft) and [IBFT](/blockchain-essentials/quorum#istanbul-byzantine-fault-tolerance), and [blk-explorer-free](https://github.com/blk-io/blk-explorer-free) blockchain explorer. Full [Ethereum](/blockchain-essentials/ethereum) Mainnet node deployment with [Bolt](/key-concepts/bolt) rapid sync mechanism
* **Clouds**. Google Cloud Platform and Amazon Web Services in APAC region
* **Node details**. Default wallet private/public keys and chain name for [MultiChain](/blockchain-essentials/multichain). Constellation private/public keys and network ID for [Quorum](/blockchain-essentials/quorum). Sync mode and network id for [Ethereum](/blockchain-essentials/ethereum). Client version for all protocols
* **Settings**. Editing personal and organization details. Changing password
* **Documentation**. [Portal based on VuePress](../)