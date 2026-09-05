# testnet-10 plan (public)

## Status
Wallet connect + live fund transfers are **in progress** (not shipped in the public docs repo).

## Planned user flow
1. Connect Kaspa wallet (TN10)
2. Create / claim job
3. Fund escrow (real UTXOs → covenant genesis)
4. Deliver → dual-sig release **or** DAA timeout refund
5. Claim `Payout`

## Requirements (operator)
- Synced TN10 node or public RPC
- Funded buyer + provider keys
- Handshake CLI spend templates green after security re-ACK
