# TxsPhish
The open-source material of TxsPhish

## TxsPhish dataset
| Category                       |                   |                     | Target Assets | Spread Method | Num  |
|--------------------------------|-------------------|---------------------|---------------|---------------|------|
| Exploiting legitimate contract | Ice phishing      | Approve             | ERC20         | website       | 1247 |
|                                |                   | Permit              | ERC20         | website       | 814  |
|                                |                   | SetApproveForAll    | NFT           | website       | 508  |
|                                | NFT order         | Bulk transfer       | NFT           | website       | 37   |
|                                |                   | Proxy upgrade       | NFT           | website       | 108  |
|                                |                   | Free buy order      | ERC20 & NFT   | website       | 464  |
| Deploying phishing contract    | Address Poisoning | Zero value transfer | ERC20         | Transaction   | 104  |
|                                |                   | Fake token transfer | ERC20         | Transaction   | 100  |
|                                |                   | Dust value transfer | ERC20         | Transaction   | 22   |
|                                | Payable Function  | Airdrop function    | ETH           | Transaction   | 788  |
|                                |                   | Wallet function     | ETH           | Transaction   | 808  |
| Benign                         | -                 | -                   | -             | -             | 13557 |


The open-source ground-truth dataset is in the **./dataset/TXSPHISH_groundtruth.csv**

## TxsPhish detection bot

We public our detection system in [Forta scam detection bot](https://app.forta.network/bot/0x9ba66b24eb2113ca3217c5e02ac6671182247c354327b27f645abb7c8a3e4534?search=0x9ba66b24eb2113ca3217c5e02ac6671182247c354327b27f645abb7c8a3e4534), and it is free to subsribe.
