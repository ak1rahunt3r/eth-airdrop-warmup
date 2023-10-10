# eth-airdrop-warmup
Make low-cost transactions on new ethereum accounts to avoid airdrop disqualification and increase airdrop chance.

### Transaction types
- Base bridge
- Zora bridge
- ZK bridge
- Starknet bridge
- Bungee refuel

### Setup
- Create files:
- - private_keys.txt - ethereum private keys with some eth balances
  - addresses_starknet.txt - your addresses on starknet where bridge swap comes
  - addresses_evm.txt - your eth addresses where transfers comes
- RandomGasFee - random gas fee about minimum
- MaxModulesCount - use all swaps for each private key
- ShuffleModules - shuffle module execution order (recommended)
