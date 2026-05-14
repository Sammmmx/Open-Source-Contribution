# Open-Source-Contribution
Originally contributed to:
https://github.com/w3-kit/contracts/tree/main/evm

These implementations are written by me.

## MultiSig Wallet
- Built a multi-signature wallet requiring multiple approvals for transaction execution
- Implemented proposal → approval → execution workflow
- Managed signer set and approval thresholds
- Ensured secure execution by validating confirmations before transaction execution
- Contributed to: [w3-kit multisig](https://github.com/w3-kit/contracts/tree/main/evm/multisig)
- Detailed Explanation: [learn.md](https://github.com/w3-kit/contracts/tree/main/evm/multisig/learn.md)

## ERC20 Token
- Built a standard-compliant ERC20 token contract
- Implemented core functions: transfer, approve, transferFrom
- Designed allowance mechanism and balance updates
- Ensured correct event emission (Transfer, Approval)
- Contributed to: [w3-kit token-erc20](https://github.com/w3-kit/contracts/blob/main/evm/token-erc20)
- Detailed Explanation: [learn.md](https://github.com/w3-kit/contracts/blob/main/evm/token-erc20/.learn.md)

## ERC721 NFT+Royalties
- Built a standard-compliant ERC721 NFT contract
- Added metadata-URI, Enumerable and Royalties (ERC2981) extensions
- Implemented core functions: _safemint, setDefaultRoyalty, tokenURI, supportsInterface
- Ensured event emission on setDefaultRoyalty
- Contributed to: [w3-kit nft-erc721](https://github.com/w3-kit/contracts/blob/main/evm/nft-erc721)
- Detailed Exmplanation: [learn.md](https://github.com/w3-kit/contracts/blob/main/evm/nft-erc721/.learn.md)

## ERC1155 Multi-Token
- Built an Openzeppelin Supported ERC1155 Multi Token Contract
- Added Roles for DEPLOYER, MINTER, URI_SETTER
- Implemented core functions: Mint, MintBatch
- Ensured Input Validation and applied Custom Errors for gas optimization
- Contributed to: [w3-kit erc-1155](https://github.com/w3-kit/contracts/tree/main/evm/erc-1155)
- Detailed Explanation: [learn.md](https://github.com/w3-kit/contracts/blob/main/evm/erc-1155/.learn.md)

## Subscriptions
- ERC20 token based recurring payments
- Merchant registration and plan management
- Subscriber controls — pause, resume, and cancel
- Manual Renewal
- Merchant withdrawal logic
- Hardhat test suite
- Contributed to: [w3-kit subscription](https://github.com/w3-kit/contracts/tree/main/evm/subscription)
- Detailed Explanation: [learn.md](https://github.com/w3-kit/contracts/tree/main/evm/subscription/learn.md)
