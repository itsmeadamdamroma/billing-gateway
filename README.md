# billing-gateway

Internal billing gateway service, version 3.1.0.

## Quick start
- Run locally: `python3 app/server.py` (health check at `/health`)
- Deploy: `make deploy`

## Deployment
Deployment is runbook-driven. Follow `DEPLOYMENT.md` exactly —
CI validates every deployment against the official runbook and marks
unregistered deploys as FAILED.
