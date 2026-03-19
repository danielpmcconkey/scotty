# Scotty — Setup Checklist

## Phase 0 (Dan's Hands)

- [ ] **Discord bot** — Developer Portal → New Application → "Scotty"
  - Install Link → None (immediately)
  - Public Bot OFF, Message Content Intent ON
  - OAuth2 → bot scope → Send Messages, Read Message History, View Channels
  - Invite to `dan-home`
  - Copy bot token

- [ ] **Discord channel** — `#engine-room` in `dan-home`
  - Deny `@everyone`, allow only Dan

- [ ] **NAS user** — DSM Control Panel → User & Group → Create `scotty`
  - No admin, no shared folder write access

- [ ] **NAS credentials** — `pass insert openclaw/scotty/nas-credentials`
  - Format: `scotty:PASSWORD`

- [ ] **NAS host** — `pass insert openclaw/scotty/nas-host`
  - Value: NAS IP or hostname (e.g. `192.168.1.100`)

## Phase 1 (Hobson Builds)

- [ ] Repo structure + git init
- [ ] Workspace files written
- [ ] `run_health_check.py` + `requirements.txt`
- [ ] Python venv created
- [ ] OpenClaw registration (needs bot token + channel ID)
- [ ] Dry run: script JSON output verified
- [ ] E2E: cron trigger → Discord post
- [ ] GitHub repo created + pushed
