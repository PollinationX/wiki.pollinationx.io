---
description: >-
  PollinationX dynamic sNFTs represent the storage and bandwidth unit, while the
  NFT image reflects the real-time storage capacity state.
cover: ../.gitbook/assets/PX-sNFT-mockup-comp.jpg
coverY: 0
---

# PX Storage NFTs

### Intro to PX  sNFTs

PX sNFTs are built for both developers and end-users. PX decentralized storage NFTs represent the storage unit and bandwidth upload capacity. Utilizing dynamic NFT technology, the NFT image dynamically updates to represent the real-time status of storage capacity. NFTs come with predefined storage and bandwidth allocations and can be minted to meet specific requirements. Storage usage metrics are synchronized via the \[PXMain] smart contract, ensuring accurate tracking. Based on the selected storage size in gigabytes and the number of bandwidth uploads (i.e. 1 bandwidth = 1 data file upload), PX sNFTs are minted to grant storage access.

### Fundamentals

* Pseudonymous storage access via Web3 login
* Self-custodial
* Robust and resistant to Web2 data mining & data ownership loss
* On-chain verifiable
* No centralized point of failure
* Multi-chain
* Transferable
* Composable
* EVM-native

### Developers

Developers can integrate the PX sNFTs directlly into their apps, enabling users to self-custody their data right out-of-the-box. As an PX sNFT owner, the integrator is authorised to claim credentials to access the PX SDK methods and have access to advanced PX dApp functionalities.

With PX sNFT integration, developers benefit from decentralization storage optimization. There is no need to maintain a larger storage capacity for storage reselling. End users maintain and hold their storage themselves in the form of the PX sNFT.&#x20;

{% hint style="info" %}
**Note:** The PX sNFT owner is authorised to claim credentials to access the PollinationX SDK methods. The storage size gets updated via NFT \[PXMain] smart contracts when the user uploads the files. When maxing the storage size, a new NFT must be minted.
{% endhint %}

### End-users

Through dynamic Storage NFTs, users can securely manage their storage quotas and bandwidth capacities. Due to the PX sNFT multi-chain nature, users can mint the sNFTs in the domain of their native chain.

### Integrations & Features

<table><thead><tr><th width="217">App</th><th>Minting</th><th>State overview</th><th>Account overview</th></tr></thead><tbody><tr><td><a href="https://app.pollinationx.io/">PX dApp</a></td><td><h2>✅</h2></td><td><h2>✅</h2></td><td><h2>✅</h2></td></tr><tr><td><a href="https://blockcommunicator.com/">BlockCommunicator</a></td><td><h2>✅</h2></td><td><h2>✅</h2></td><td><h2>✅</h2></td></tr><tr><td><a href="https://w3xshare.com/">W3XShare</a></td><td><h2>✅</h2></td><td><h2>✅</h2></td><td><h2>✅</h2></td></tr><tr><td><a href="https://app.the4thpillar.io/">4P Super App</a></td><td><h2>✅</h2></td><td><h2>✅</h2></td><td><h2>✅</h2></td></tr></tbody></table>

### Sizes, Bandwidth & Prices

<table><thead><tr><th>Size</th><th>Bandwidth</th><th width="182">Estimated price in $</th></tr></thead><tbody><tr><td>100MB</td><td>25 uploads</td><td>Free</td></tr><tr><td>1GB</td><td>50 uploads</td><td>≈ 5$</td></tr><tr><td>5GB</td><td>150 uploads</td><td>≈ 15$ </td></tr><tr><td>20BG</td><td>400 uploads</td><td>≈ 30$</td></tr></tbody></table>

<table><thead><tr><th>Bandwidth</th><th width="182">Estimated price in $</th></tr></thead><tbody><tr><td>10 uploads</td><td>≈ 1$</td></tr></tbody></table>

{% hint style="info" %}
**Note:** References to USD prices are made for approximate fiat value illustration purposes only. Access [Fees](fees.md) chapter for more information.
{% endhint %}

### Adding the PX sNFT to MetaMask

1. Go to MetaMask and access the NFT tab
2. Click ➕_Import NFT_
3. Fill in the details below:\
   \- **Address:** 0x1142b080a5493695e3E35c9C4269f6C06B5CE0F4\
   \- **Token ID:** (e.g. #123)
4. Click _Import_

{% hint style="info" %}
**Note:** NFT smart contracts address is no always the same. Check the exact address on the [supported network](https://wiki.pollinationx.io/overview/supported-networks-and-storages) page. Every PX sNFT has its uniqe ID. You can find it on the NFT graphics (# + a specific number) or access it in the NFT mint smart contract transaction.
{% endhint %}

### Resources

{% embed url="https://github.com/PollinationX/smart-contracts" %}
