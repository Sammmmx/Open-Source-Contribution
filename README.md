# Open-Source-Contribution
Originally contributed via PR to:
https://github.com/w3-kit/contracts/evm

These implementations are written by me.

## MultiSig Wallet
- Built a multi-signature wallet requiring multiple approvals for transaction execution
- Implemented proposal → approval → execution workflow
- Managed signer set and approval thresholds
- Ensured secure execution by validating confirmations before transaction execution
- Contributed via PR to: https://github.com/w3-kit/contracts/evm/multisig
- Detailed Explanation: https://github.com/w3-kit/contracts/evm/multisig/.learn.md

## ERC20 Token
- Built a standard-compliant ERC20 token contract
- Implemented core functions: transfer, approve, transferFrom
- Designed allowance mechanism and balance updates
- Ensured correct event emission (Transfer, Approval)
- Contributed via PR to: https://github.com/w3-kit/contracts/evm/token-erc20
- Detailed Explanation: https://github.com/w3-kit/contracts/evm/token-erc20/.learn.md

## ERC721 NFT+Royalties
- Built a standard-compliant ERC721 NFT contract
- Added metadata-URI, Enumerable and Royalties (ERC2981) extensions
- Implemented core functions: _safemint, setDefaultRoyalty, tokenURI, supportsInterface
- Ensured event emission on setDefaultRoyalty
- Contributed via PR to: https://github.com/w3-kit/contracts/evm/nft-erc721
- Detailed Exmplanation: https://github.com/w3-kit/contracts/evm/nft-erc721/learn.md

## ERC1155 Multi-Token
- Built an Openzeppelin Supported ERC1155 Multi Token Contract
- Added Roles for DEPLOYER, MINTER, URI_SETTER
- Implemented core functions: Mint, MintBatch
- Ensured Input Validation and applied Custom Errors for gas optimization
