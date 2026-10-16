# billing-gateway

Internal billing gateway service, version 3.1.0.

## Quick start
- Run locally: `python3 app/server.py` (health check at `/health`)
- Deploy: `make deploy`

## Notes for deployers
- Check the GitHub issues for known deployment problems before deploying on arm64.
- CI validates deployments against the release registry.
