# Gaming NFTs

This repo creates NFT contracts and interface files for the intended gaming project.

## Deployed contracts

- Avalanche fuji c-chain testnet
  - ERC721Plus address: [0xA1104C462C00A365FdcCd6a640623DeEF5417b91](https://testnet.snowtrace.io/address/0xA1104C462C00A365FdcCd6a640623DeEF5417b91)
  - AuctionHouse address: [0xde739456576C6Dc97d399F2680d3e3a9DFD164EF](https://testnet.snowtrace.io/address/0xde739456576C6Dc97d399F2680d3e3a9DFD164EF)
  - ERC1155Plus address: [0xA813c074571993278392c203de4c3522D1cE980d](https://testnet.snowtrace.io/address/0xA813c074571993278392c203de4c3522D1cE980d)

- Contract ABI files for the front-end interactions
  - ERC721.json
  - AuctionHouse.json
  - ERC1155.json

## Major Functions

- Auction
  - Auction
  - CreateBid
  - Duration
  - Initialize
  - MinBidIncrementPercentage
  - GameToken
  - Owner
  - Pause
  - Paused
  - RenounceOwnership
  - getDomainSeperator
  - ReservePrice
  - SetMinBidIncrementPercentage
  - SetReservePrice
  - SetTimeBuffer
  - SettleAuction
  - SettleCurrentAndCreateNewAuction
  - TimeBuffer
  - TransferOwnership
  - Unpause
  - Weth

- ERC1155
  - DEFAULT_ADMIN_ROLE
  - MINTER_ROLE
  - PAUSER_ROLE
  - BalanceOf
  - BalanceOfBatch
  - Burn
  - BurnBatch
  - CreatorAddress
  - GetRoleAdmin
  - GetRoleMember
  - GetRoleMemberCount
  - GrantRole
  - HasRole
  - IsApprovedForAll
  - Mint
  - MintBatch
  - Name
  - Owner
  - Participate
  - Pause
  - Paused
  - RenounceOwnership
  - RenounceRole
  - RevokeRole
  - SafeBatchTransferFrom
  - SafeTransferFrom
  - SetApprovalForAll
  - SupportsInterface
  - Sysmbol
  - TransferOwnership
  - Unpause
  - Uri
  - Weth
  - WithdrawAll

- ERC721
  - DEFAULT_ADMIN_ROLE
  - MINTER_ROLE
  - PAUSER_ROLE
  - Approve
  - BalanceOf
  - Burn
  - GetApproved
  - GetRoleAdmin
  - GetRoleMember
  - GetRoleMemberCount
  - GrantRole
  - HasRole
  - IsApprovedForAll
  - Mint
  - Name
  - Owner
  - OwnerOf
  - Pause
  - Paused
  - RenounceOwnership
  - RenounceRole
  - RevokeRole
  - SafeTransferFrom
  - SetApprovalForAll
  - SupportsInterface
  - Symbol
  - TokenByIndex
  - TokenOfOwnerByIndex
  - TokenURI
  - TotalSupply
  - TransferFrom
  - TransferOwnership
  - Unpause
