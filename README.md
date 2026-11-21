# CT DIGITAL GROUP — Corporate Website

Official source-control repository for the [CT DIGITAL GROUP website](https://ctdigital.group/).

CT DIGITAL GROUP is a UK-operated digital group building and operating businesses across AI-enabled growth, websites, infrastructure, publishing and digital commerce.

## Repository status

**Verified production Worker source imported on 21 November 2026 as `worker.js` (commit `6afa465`).**

Cloudflare confirms that both `ctdigital.group` and `www.ctdigital.group` are assigned to the production Worker `ctdigital-group-services`. The imported `worker.js` was retrieved from that Worker via the Cloudflare API and matched byte-for-byte by SHA-256. This Git snapshot does not include private runtime bindings, secrets or any separately deployed services; production remains independently deployed and unchanged.

## Scope

- Corporate website pages, layouts, assets, responsive behavior and accessibility
- SEO, AEO and structured website metadata
- Website-side integration with Cora, the CTDG AI receptionist
- Future website development and maintenance with reviewable Git history

The Cora service and any operational backends must be inventoried separately before deciding whether they belong here or in their existing repositories.

## Source integrity and deployment

- The imported `worker.js` is the verified production source snapshot from 21 November 2026; check Cloudflare for later live changes before development or deployment.
- Do not import API keys, environment files, credentials, customer records, server backups, caches or deployment secrets.
- Do not infer or recreate earlier Git commits from historic work.
- Do not deploy to production merely because a commit was pushed to this repository.
- Review and test future changes before any independent, explicitly verified deployment.

## Related projects

- [CTDG Command Centre](https://github.com/colintandyonline/CTDG-Command-Centre)
- [CTDG Managed AI](https://github.com/colintandyonline/CTDG-Managed-AI)
- [CTDG Gandalf Mobile](https://github.com/colintandyonline/CTDG-Gandalf-Mobile)

Website: https://ctdigital.group/