# zeus-offsite-monitor

Off-site uptime check for the public sites served from the house. Runs every 30 minutes on GitHub Actions.
When most sites are unreachable twice in a row the run fails, and GitHub emails the owner. It exists because
every other monitor lives in the house and goes quiet with it. Set up 2026-10-22 as part of Doll's
server-admin redesign.
