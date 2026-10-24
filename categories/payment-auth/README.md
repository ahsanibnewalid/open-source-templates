# Payment & Authentication Projects

These entries are catalogued for evaluation. The upstream source code is **not vendored into this repository**. Review each upstream repository's current license, security notices, and dependencies before forking or redistributing.

## YouPI-PG

- **Upstream:** https://github.com/youpi-pg/YouPI-PG
- **Purpose:** Experimental self-hosted UPI payment gateway and checkout flows.
- **Use:** Local development, demos, and security research only until independently reviewed.
- **Important:** Upstream explicitly describes the project as experimental and not certified or production-ready. Its UPI workflow targets India; it is not a ready-made Bangladesh payment integration.
- **Before adoption:** Review the upstream LICENSE, bank/provider terms, payment verification, duplicate/replay handling, webhook security, reconciliation, and applicable legal requirements.

## WA-USERAUTH

- **Upstream:** https://github.com/gxurav1710/WA-USERAUTH
- **Purpose:** Review the upstream README and source to confirm the exact authentication use case and supported stack.
- **Use:** Evaluation only until the implementation, license, dependencies, and security posture have been verified.
- **Before adoption:** Confirm session/token protections, authentication bypass resistance, rate limits, secrets handling, account recovery, and automated test coverage.

## Importing full source

To preserve upstream history and attribution, prefer GitHub forks when available. If copying source into this catalog, keep each project in its own directory, retain all license/copyright notices, record the exact upstream commit, and confirm the license permits redistribution. Never copy secrets, local databases, customer data, or build artifacts.
