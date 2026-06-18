# VulnBank - Discovered Endpoints (Burp Recon)

## Authentication
- GET /login
- POST /login
- GET /register
- POST /register
- GET /dashboard

## Transactions
- GET /transactions/{transaction_id}

## User / Banking APIs
- GET /api/virtual-cards
- GET /api/bill-categories
- GET /api/bill-payments/history

## Notes
- Most endpoints return JSON responses except auth pages.
- Sensitive endpoints appear under /api/
- Transaction endpoint uses numeric ID (possible IDOR candidate)