# Chain Specification

## Chain Information
- **Chain Name**: ATARAXIA
- **Chain ID**: 2201
- **Coin**: XPQ
- **Subcoin**: oriul

## Monetary Units
- **oriul**: The smallest unit of XPQ (1 XPQ = 100,000 oriul)
- **oriul Value**: 1
- **XPQ Value**: 100,000

## Supply & Incentives
- **Maximum Supply**: 150,000,000 XPQ (15,000,000,000,000,000 oriul)
- **Genesis Distribution**: 0 XPQ (no premine)
- **Supply-Based Incentive Model**:
  - 50-25-12,5-6,25-3,125-0,5 XPQ
  - 0-50% supply: 50 XPQ per block
  - 51-60% supply: 25 XPQ per block
  - 61-70% supply: 12,5 XPQ per block
  - 71-80% supply: 6,25 XPQ per block
  - 81-90% supply: 3,125 XPQ per block
  - 91-100% supply: 0,5 XPQ per block
- **Total Duration**: ~460 years
- **Supply Source**: 100% from mining rewards 

## Block Parameters
- **Block Time**: 60 seconds (1 minutes)
- **Block Incentive Maturity**: 1440 blocks

## Difficulty Adjustment
- **Adjustment Blocks**: 14400
- **Minimum Difficulty**: 1
- **Max Difficulty Up**: 3
- **Max Difficulty Down**: 1

## Transaction Parameters
- **Max Transaction Size**: 32 KB (32,768 bytes)
- **Fee Per KB**: 1000 oriul
- **Base Fee**: 1000 oriul
- **Max Block Header Size**: 1024 bytes

## Cryptographic Parameters
- **Dilithium5 Public Key Size**: 2592 bytes
- **Dilithium5 Signature Size**: 4595 bytes
- **Cuckoo Cycle Sample Nodes**: 16

## Timestamp Parameters
- **Timestamp Drift Tolerance**: 90 seconds
- **Genesis Timestamp**: 1767225600 (January 1, 2026 00:00:00 UTC)
- **Genesis Difficulty**: 1
- **Genesis Nonce**: 0

## License

This project is licensed under the MIT License.

MIT License

Copyright (c) 2026 ATARAXIA

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
