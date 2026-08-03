# Axanar public platform status

**Public, read-only status for fans and press.**  
Canonical branded UI: [https://beta.axanar.com/status](https://beta.axanar.com/status)

This repository exists so the community is **not stuck behind a private engineering monorepo**.

| Artifact | Purpose |
| --- | --- |
| [`status.json`](./status.json) | Machine-readable public status (no private tickets, emails, or donor data) |
| [`index.html`](./index.html) | Lightweight static status page (GitHub Pages) |
| GitHub Pages | Public mirror of the same data |

## Links

- **Branded product page:** https://beta.axanar.com/status  
- **Raw JSON:** https://lquessenberry.github.io/axanar-status/status.json  
- **Static mirror (Pages):** https://lquessenberry.github.io/axanar-status/  
- **Report problems:** [portal support / beta](https://beta.axanar.com/portal/support?tab=beta) · [axanartech@gmail.com](mailto:axanartech@gmail.com?subject=Axanar%20beta%20issue)

## What is *not* here

- No private GitHub issue tracker  
- No donor PII, receipts, or account data  
- No deploy credentials for production apps  

Engineering work is triaged privately. This page only carries **public summaries**.

## How updates land here

Ops refresh scrubbed JSON in the private monorepo (`status/status.json`), then mirror into this public repo (automated workflow or `scripts/mirror-status-public.sh`).

## License

Status text and layout are © Axanar Productions. Data may be cited with attribution. Fan production — not endorsed by CBS / Paramount.
