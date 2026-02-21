# Architecture

## High-level
- Client web app renders map and social UI.
- iOS app wraps the same web bundle via Capacitor.
- Firebase handles auth, data, media, and server-side validation/business rules.

## Data flow
1. User authenticates (guest or Google/account).
2. Client reads/writes pings, comments, reactions via secure pathways.
3. Media uploads flow through controlled storage + metadata docs.
4. Scheduled/server functions handle maintenance tasks (e.g., expiry, ranking logic).

## Key systems
- Auth state-driven UI modes (signed out, guest, signed in)
- Location and map interactions
- Ping posting pipeline with media
- Share-link system with metadata/preview pages
- Notifications + friend interactions

## Reliability and security practices
- Client and server validation
- Rule-aware operations
- Incremental hardening based on live QA feedback
- Cache-busting/version bumps for deterministic rollout behavior
