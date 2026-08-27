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

Every repository here is the **free edition** — fully functional, Apache-2.0, running the same engine as the paid tiers. Pro and Team tiers (higher limits, more alert channels, team features) and the complete **[Hexward Suite](https://whop.com/hexward-suite?utm_source=gh-profile)** bundle are on Whop.

The six above watch your infrastructure. **[RuleForge](https://github.com/nizartuanku/ruleforge)** does something different: it moves it. Firewall configs converted between Cisco ASA, FTD, Palo Alto PAN-OS, FortiGate and Check Point — all 20 directions, not one. Deep analysis and an editable mapping step before anything is generated, per-element accounting so nothing is silently dropped, and round-trip verification that re-parses its own output and diffs it against the source. Dashboard on `:8428`.

Running Cisco Secure Firewall? **[Firewall Operations Platform](https://whop.com/firewall-ops-platform?utm_source=gh-profile)** covers the Cisco-depth side: upgrade orchestration, content updates, dead object cleanup, NAT-aware event mapping, and flow graphs for FMC & FTD.

---

Weekly security habits, explained for people who don't work in security: [Instagram @nizartuanku](https://instagram.com/nizartuanku)
