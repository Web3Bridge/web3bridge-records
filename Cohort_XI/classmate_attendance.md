# Web3Bridge Classmate DApp - Cohort XI Attendance

## Overview

Classmate is Web3Bridge's decentralized attendance tracking system. After each class session, students sign their attendance which mints an ERC-1155 NFT as proof of participation. This document provides details about Cohort XI's attendance contract and statistics.

## Contract Details

### Factory Contract

- Network: Base Mainnet
- Factory Contract Address: 0xF11878F662Dc53b6B033De55aE6e0D0d3fa29b49

### Cohort XI Attendance Contract

- Child Contract Address: 0xb708BEedd1C35985cCce9e1c2111D29B1C006137
- Total Attendance Transactions: 3,472
- Contract Deployment Date: 7th August 2024

## Statistics

- Total Number of Classes: 84
- Graduated Number of Students: 63
- Average Daily Attendance: 41

## How It Works

1. Students attend their daily class session
2. At the end of each class, students connect their wallet to Classmate
3. Students sign the attendance transaction
4. An NFT is automatically minted to their wallet as proof of attendance
5. The attendance is permanently recorded on the blockchain

## Verification

To verify attendance NFTs:

1. Connect to Base Network
2. Visit [BaseScan](https://basescan.org/)
3. Enter the contract address
4. Select a transaction hash or wallet address
5. View transaction details

## Technical Integration

- Platform: Classmate DApp
- Network: Base Mainnet
- Standard: ERC-1155
- Metadata: IPFS

## Notes

- All attendance NFTs are non-transferable
- Each student can only sign attendance once per class
- NFTs serve as permanent proof of participation
- Contract is part of Web3Bridge's attendance tracking system
