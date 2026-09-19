# Ledger Anchor Log

Append-only, tamper-evident anchor record for a **private** research ledger.

- `ANCHOR.txt` - current chain head hash, entry/run counts, timestamp.
- `chain_export.txt` - the full hash chain (one entry per line, pipe-separated).

Contains **hashes and counts only** - no instruments, positions, prices, or account data.
Branch protection is enabled (no force-push, no deletion), so published history cannot be rewritten.
