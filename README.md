# Sebastian — builder-operator

I design, ship and operate agent systems and automation on my own infrastructure —
a self-hosted fleet (Proxmox, Docker, Tailscale) running an always-on agent
orchestrator, an AI-governed knowledge vault, and a set of production tools I use
daily. Everything is built pair-programming with **Claude Code**: architecture,
priorities and verification are mine; the implementation is AI-generated and
verified against real behavior before it ships. I keep the receipts for both
halves of that claim.

## Public work

- **[agent-vault-gate](https://github.com/skk-hub/agent-vault-gate)** — mechanical
  trust for AI-written knowledge bases: a commit gate + batch-review workflow that
  lets multiple AI agents write to one vault unattended. Extracted from a system
  running in production since mid-2026; ships with a synthetic sample vault and a
  test suite proving each enforcement claim.
- **[poe2-tools](https://github.com/skk-hub/poe2-tools)** — a zero-dependency
  Node.js pricing and utility suite for Path of Exile 2: screen OCR (no API exists
  for that surface), rate-limit-aware API clients behind one adaptive queue, and
  five weeks of dense commit history that doubles as the design log.

Most of the rest lives in private repos (a personal knowledge vault, home-fleet
operations tooling, fitness/API integrations) — the repos above are the parts
that extract cleanly without personal data.

## Background

Before engineering: founded and ran a 24/7 online digital-services marketplace
(2017–2020) with a 20+ person distributed team — which is where the operator's
respect for queues, audit trails and trust-and-safety mechanics comes from.

📫 skkahlina@gmail.com · Zagreb, Croatia · remote-first
