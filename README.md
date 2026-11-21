# CT DIGITAL GROUP — Corporate Website

Official source-control repository for the [CT DIGITAL GROUP website](https://ctdigital.group/).

CT DIGITAL GROUP is a UK-operated digital group building and operating businesses across AI-enabled growth, websites, infrastructure, publishing and digital commerce.

## Repository status

**Repository initialized; authoritative website source import pending verification.**

This README does **not** claim that the current contents reproduce the live site. The production website remains independently deployed and unchanged. Its verified server-side document root has previously been recorded as `/var/www/vhosts/ctdigital.group/httpdocs`; any import must be checked against the actual live deployment and any separate application services before code is committed.

## Scope

- Corporate website pages, layouts, assets, responsive behavior and accessibility
- SEO, AEO and structured website metadata
- Website-side integration with Cora, the CTDG AI receptionist
- Future website development and maintenance with reviewable Git history

The Cora service and any operational backends must be inventoried separately before deciding whether they belong here or in their existing repositories.

## Source integrity and deployment

- The live website remains the authoritative reference until the source snapshot has been verified.
- Do not import API keys, environment files, credentials, customer records, server backups, caches or deployment secrets.
- Do not infer or recreate earlier Git commits from historic work.
- Do not deploy to production merely because a commit was pushed to this repository.
- Review and test future changes before any independent, explicitly verified deployment.

## Related projects

- [CTDG Command Centre](https://github.com/colintandyonline/CTDG-Command-Centre)
- [CTDG Managed AI](https://github.com/colintandyonline/CTDG-Managed-AI)
- [CTDG Gandalf Mobile](https://github.com/colintandyonline/CTDG-Gandalf-Mobile)

Website: https://ctdigital.group/