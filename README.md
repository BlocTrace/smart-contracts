# BlocTrace Smart Contracts:

# Overview

Traceability You Can Trust,From Source to Shelf.
Providing OEMs in the electronics industry with a comprehensive solution to track their products from raw materials to the end product

# Details

These contracts setup the veriication for users, additionally it enables verified users to craete and manage consignments by minting ERC1155 and assigning them.

# File Structure

Smart Contracts:

- ERC721 Contract for handling OEM verification - `BlocTraceOEM`
- ERC1150 Contract for managing Batches of products customers will create and assign - `BlocTraceConsignment.sol`

# Deployed Contracts:

- OEM Verification Contract address: `0x076828DBE51bBeC252E4C72F8dE523f39c7819f4`
- Batch Management Contract address: `0x4837AbB3E0A9Ec8957448f80E2332F82676D4C80`

# Running Scripts:

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```
