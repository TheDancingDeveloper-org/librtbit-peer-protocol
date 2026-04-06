# librtbit-peer-protocol

BitTorrent peer wire protocol implementation for the rtbit client.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |

### Depends On

- **librtbit-buffers** (git, v0.1.0)
- **librtbit-bencode** (git, v0.1.0)
- **librtbit-clone-to-owned** (git, v0.1.0)
- **librtbit-core** (git, v0.1.0)

## BEP Implementations

- BEP 3 — Peer wire protocol messages (choke, unchoke, interested, have, piece, etc.)
- BEP 10 — Protocol extension framework (extended messages)
- BEP 11 — Peer exchange (ut_pex)
- BEP 21 — Metadata exchange (ut_metadata)
- BEP 55 — NAT hole punching relay (ut_holepunch)
