# Nooterra — Research Commitments

This repository contains cryptographic commitments (SHA-256 root hashes) to private research artifacts of **Nooterra LLC**.

Each ledger entry timestamps a body of work without revealing its content. The commitment root is the SHA-256 of a canonical manifest listing every covered file's individual SHA-256 plus the repository state at commitment time.

**Verification, upon any future disclosure:** recompute the manifest root from the disclosed files and manifest, compare to the ledger entry below, and use this repository's git history (and GitHub's served timestamps) as the time witness.

No further information about the work is published here by design.
