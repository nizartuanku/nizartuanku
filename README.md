## Hexward — self-hosted security tools

Six focused tools on one shared core. Each answers a question a small team actually asks — and they work as a system: **Loglight** can ingest the other tools' alerts and fold them into its kill-chain correlation. Your data never leaves your network: single Go binaries, SQLite, offline license validation, no telemetry, no phone-home.

| # | Tool | The question it answers | Dashboard |
|---|------|-------------------------|-----------|
| 1 | [**CertLight**](https://github.com/nizartuanku/certlight) | Is our TLS about to expire — or badly configured? | `:8422` |
| 2 | [**Attack Surface Monitor**](https://github.com/nizartuanku/attack-surface-monitor) | What do we actually expose to the internet? | `:8423` |
| 3 | [**Decoy**](https://github.com/nizartuanku/decoy) | Is someone already inside? | `:8424` |
| 4 | [**Patchlight**](https://github.com/nizartuanku/patchlight) | Which CVEs are actually being exploited — and affect us? | `:8425` |
| 5 | [**RuleHawk**](https://github.com/nizartuanku/rulehawk) | Does our firewall still mean what we think it means? | `:8426` |
| 6 | [**Loglight**](https://github.com/nizartuanku/loglight) | If something were attacking us right now, would we know? | `:8427` |

Every repository here is the **free edition** — fully functional, Apache-2.0, running the same engine as the paid tiers. Pro and Team tiers (higher limits, more alert channels, team features) and the complete **[Hexward Suite](https://whop.com/hexward-suite)** bundle are on Whop.

Running Cisco Secure Firewall? **[Firewall Operations Platform](https://whop.com/firewall-ops-platform)** covers the Cisco-depth side: upgrade orchestration, content updates, dead object cleanup, NAT-aware event mapping, and flow graphs for FMC & FTD.

---

Weekly security habits, explained for people who don't work in security: [Instagram @nizartuanku](https://instagram.com/nizartuanku)
