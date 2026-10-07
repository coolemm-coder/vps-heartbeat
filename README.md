# vps-heartbeat

External uptime ping for the n8n VPS: every 10 min GitHub Actions checks `https://automation.landingpro.by/healthz` and pings healthchecks.io (which blocks Russian IPs, so the server cannot do it itself).
