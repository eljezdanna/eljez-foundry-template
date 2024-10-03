# Foundry Template Using Openzeppelin
Please note this template using blockscout platform.

## Deploying Smart Contract
```
forge create ./src/Contract.sol:MyToken\
 --rpc-url <your_rpc_url>\
 --private-key <your_private_key_wallet>
```

## Verify Smart Contract
```bash
forge verify-contract <contract_address> ./src/Contract.sol:MyToken\
 --verifier blockscout\
 --verifier-url <your_verifier_url\
 --rpc-url <your_rpc_url>
```

Thanks.
