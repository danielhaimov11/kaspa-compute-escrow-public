# Architecture (public)

## Split
- **On-chain:** one Escrow covenant → `become Payout{owner}` on release/refund; refund requires `tx.daa >= deadline`.
- **Off-chain:** job metadata (resource kind: gpu / cpu_vm / database / cloud_run), marketplace auto-provision (mock→live), dashboards.

## Parties
- Renter (buyer), Provider, Admin (ops; `force_deadline` is demo-only and never feeds on-chain paths).

## Networks
- Target: **testnet-10** first, then mainnet after security ACK.
