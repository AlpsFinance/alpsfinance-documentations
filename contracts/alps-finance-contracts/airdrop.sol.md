# Airdrop.sol

GitHub Link: [https://github.com/AlpsFinance/alpsfinance-smart-contracts/blob/main/contracts/airdrop/Airdrop.sol](https://github.com/AlpsFinance/alpsfinance-smart-contracts/blob/main/contracts/airdrop/Airdrop.sol)

Description: This smart contract is used to handle ALPS ERC20 Token Airdrop using the Merkle Tree data structure

### getMerkleRoot()

* Get the current Merkle root that is used within the Airdrop.sol smart contract

### setMerkleRoot(bytes32 \_newMerkleRoot)

* Set the Merkle root to the `_newMerkleRoot` value
* Requirements:
  * `_newMerkleRoot` must not be zero value
  * `_newMerkleRoot` cannot have the same value as the current Merkle root

### claim(uint256 amount, bytes32\[] calldata proof)
