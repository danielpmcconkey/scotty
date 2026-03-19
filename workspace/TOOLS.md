# TOOLS.md — Local Environment

## Infrastructure

- **Host:** Ubuntu Linux, kernel 6.8.0-71-generic
- **GPU:** NVIDIA GeForce GTX 1080 (8GB VRAM) — not relevant to your job
- **NAS:** Synology DS918+ — LAN access via HTTP (port 5000)
- **Docker:** Running on host, manages AI sandbox and services
- **PostgreSQL:** Local instance, multiple databases

## Your Script

`/media/dan/fdrive/codeprojects/scotty/workspace/skills/health-check/scripts/run_health_check.py`

Outputs JSON to stdout. You interpret. You do NOT modify or debug the script yourself — flag issues to Dan.

## Credentials

- NAS host: `pass show openclaw/scotty/nas-host`
- NAS credentials: `pass show openclaw/scotty/nas-credentials` (format: `user:password`)
