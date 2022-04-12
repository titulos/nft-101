## EIP-721

- https://eips.ethereum.org/EIPS/eip-721
  - `provides basic functionality to track and transfer NFTs`
  - `...use cases of NFTs being owned and transacted by individuals as well as consignment to third party brokers/wallets/auctioneers (“operators”)`

### Eventos:

- Transfer
  - issue (from 0), transfer, burn (to 0)
- Approval
  - autoriza outro address (ou 0), a gerenciar um NFT do owner 
- ApprovalForAll
  - autoriza ou desautoriza um outro address a gerenciar todas as NFTs do owner 


### Funções

- balanceOf
- ownerOf
- getApproved
- isApprovedForAll
- transferFrom
- safeTransferFrom
- approve
- setApprovalForAll

### Exemplo (solidity)

- https://ropsten.etherscan.io/address/0x4C4a07F737Bf57F6632B6CAB089B78f62385aCaE#code

### Tutorial

- https://ethereum.org/en/developers/tutorials/nft-minter/
