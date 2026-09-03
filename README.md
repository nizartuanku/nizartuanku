## Nizar Tuanku — network security since 2007

I build **Hexward**: self-hosted security tools for MSPs and network engineers. Single Go binary, SQLite, offline licence check, no telemetry, no phone-home. Every repository below is the free edition — the same engine as the paid tiers, Apache-2.0.

### Start here

| If you want to… | Open this | See it before you run it |
|---|---|---|
| Migrate a firewall between vendors (ASA / FTD / PAN-OS / FortiGate / Check Point) with nothing silently dropped | [**RuleForge**](https://github.com/nizartuanku/ruleforge) | [Sample conversion report](https://github.com/nizartuanku/ruleforge/blob/main/docs/samples/asa-to-panos-conversion-process-report.pdf) · [final migration report](https://github.com/nizartuanku/ruleforge/blob/main/docs/samples/asa-to-panos-final-migration-report.pdf) |
| Find the shadowed, permissive and drifted rules in a config you already have | [**RuleHawk**](https://github.com/nizartuanku/rulehawk) | [Four sample configs](https://github.com/nizartuanku/rulehawk/tree/main/docs/samples) — the ASA one yields 11 findings, 2 high |
| Stop a certificate from taking production down | [**CertLight**](https://github.com/nizartuanku/certlight) | Run it, add a host, results in seconds |
| Read the cross-vendor gotchas without installing anything | [**Firewall migration notes**](https://github.com/nizartuanku/firewall-migration-notes) | [FortiGate central NAT](https://github.com/nizartuanku/firewall-migration-notes/blob/main/fortigate-central-nat.md) |

If one of these saves you an hour, a ⭐ on the repo is how the next engineer finds it.

### The whole line

| Tool | The question it answers | Port |
|---|---|---|
| [CertLight](https://github.com/nizartuanku/certlight) | Is our TLS about to expire — or badly configured? | `:8422` |
| [Attack Surface Monitor](https://github.com/nizartuanku/attack-surface-monitor) | What do we actually expose to the internet? | `:8423` |
| [Decoy](https://github.com/nizartuanku/decoy) | Is someone already inside? | `:8424` |
| [Patchlight](https://github.com/nizartuanku/patchlight) | Which CVEs are actually exploited — and affect us? | `:8425` |
| [RuleHawk](https://github.com/nizartuanku/rulehawk) | Does our firewall still mean what we think it means? | `:8426` |
| [Loglight](https://github.com/nizartuanku/loglight) | If something were attacking us right now, would we know? | `:8427` |
| [RuleForge](https://github.com/nizartuanku/ruleforge) | Can we move this firewall to another vendor without losing a rule? | `:8428` |
| [DmarcWatch](https://github.com/nizartuanku/dmarcwatch) | Who is sending mail as our domain? | `:8429` |
| [TenantWatch](https://github.com/nizartuanku/tenantwatch) | Is our Microsoft 365 / Google Workspace tenant configured the way we think? | `:8430` |
| [Posture Report](https://github.com/nizartuanku/posture-report) | One score across the whole stack — what is it this week? | `:8432` |
| [TopoLight](https://github.com/nizartuanku/topolight) | What does the physical network look like right now, and what is the root cause? | `:8432` |
| [AuditLight](https://github.com/nizartuanku/auditlight) | What would an assessor find — before the assessor does? | `:8431` |

They work as a system: every tool can emit findings as syslog, and **Loglight** folds them into kill-chain incidents. Pro and Team tiers (higher limits, more alert channels, team features) are on Whop — **[all products](https://whop.com/nizar-tuanku?utm_source=github&utm_medium=profile)**, 14-day trial, key delivered by DM right after checkout. Running Cisco Secure Firewall? [Firewall Operations Platform](https://whop.com/nizar-tuanku/firewall-ops-platform?utm_source=github&utm_medium=profile) covers FMC/FTD operations.

### Writing and video

Real migrations, real attacks, practical fixes — one mistake per post: [Hexward Labs on LinkedIn](https://www.linkedin.com/company/143576107/) · [YouTube](https://www.youtube.com/@nizartuanku) · [Documentation hub](https://nizartuanku.github.io)
