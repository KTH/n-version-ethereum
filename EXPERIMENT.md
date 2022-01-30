Here we keep track of experiment results.

### The number of TCP and UDP messages sent/received by Besu in 1 minute

- TCP: 74281 packets, 79287867 bytes (incoming: 31350 packets, 19536806 bytes; outgoing: 42931 packets, 59751061 bytes)
- UDP: 580 packets, 154379 bytes (incoming: 351 packets, 58384 bytes; outgoing: 229 packets, 95995 bytes)

### The number of p2p messages sent/received by Besu in 1 minute

- Inbound

| Code | Message Type | Protocol | Count |
| ---- | ------------ | -------- | ----- |
| 0 | Status | eth/63 | 12 |
| 0 | Status | eth/64 | 4 |
| 0 | Status | eth/65 | 8 |
| 0 | Status | eth/66 | 160 |
| 1 | NewBlockHashes | eth/65 | 6.67 |
| 1 | NewBlockHashes | eth/66 | 58.7 |
| 2 | Transactions | eth/66 | 1623 |
| 3 | GetBlockHeaders | eth/66 | 5.33 |
| 4 | BlockHeaders | eth/66 | 90.7 |
| 6 | BlockBodies | eth/66 | 94.7 |
| 7 | NewBlock | eth/66 | 20 |
| 8 | NewPooledTransactionHashes | eth/65 | 66.7 |
| 8 | NewPooledTransactionHashes | eth/66 | 14683 |
| 14 | NodeData | eth/66 | 1979 |
| 16 | Receipts | eth/66 | 92 |
| - | SUM | - | 18903.8 |

- Outbound

| Code | Message Type | Protocol | Count |
| ---- | ------------ | -------- | ----- |
| 0 | Status | eth/63 | 17.3 |
| 0 | Status | eth/64 | 12 |
| 0 | Status | eth/65 | 9.33 |
| 0 | Status | eth/66 | 187 |
| 1 | Disconnect | Wire | 251 |
| 2 | Ping | Wire | 1.33 |
| 3 | GetBlockHeaders | eth/65 | 1.33 |
| 3 | GetBlockHeaders | eth/66 | 94.7 |
| 3 | Pong | Wire | 103 |
| 4 | BlockHeaders | eth/66 | 5.33 |
| 5 | GetBlockBodies | eth/66 | 96 |
| 13 | GetNodeData | eth/66 | 1981 |
| 15 | GetReceipts | eth/66 | 92 |
| - | SUM | - | 2851.32 |
