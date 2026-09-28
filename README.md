# Portfolia
A web-first portfolio intelligence product with an original UI/UX and an open-source financial infrastructure strategy.

## Current product slice
- Responsive portfolio overview
- Holdings and security details
- Transactions with local persistence
- Income and allocation reports
- Core portfolio calculations + XIRR tests
- Supabase/Postgres/Auth/RLS schema staged
- yahoo-finance2 market adapter staged
- PyXIRR service boundary staged
- Playwright desktop/mobile E2E suite staged

## Verification status
Source and tests are committed. A connected runtime/deployment has not yet executed build/browser verification, so this repository is not yet described as production verified.

## Next engineering gate
Connect the database/auth runtime, make the transaction ledger canonical, derive holdings/cash/cost basis from it, connect market data with freshness metadata, then execute unit/E2E/visual QA.
