# Open Source Templates Library

A categorized directory of open-source website templates, UI starters, and full-stack application foundations. Use it to compare stacks, inspect demos, customize layouts, and choose a sensible starting point for a project.

> **This repository is a catalog, not a copy of the upstream projects.** It links to original repositories and documentation so their authors retain attribution and updates. Before reuse, check the upstream `LICENSE`, current maintenance status, dependencies, and commercial-use terms.

## Browse by category

| Category | Best for | Catalog |
|---|---|---|
| SaaS & subscription apps | Authentication, billing, organizations, customer portals | [saas/](categories/saas/README.md) |
| Full-stack React / Next.js | Modern TypeScript apps and API-connected websites | [react-nextjs/](categories/react-nextjs/README.md) |
| Python: FastAPI & Django | Python APIs, admin tools, database-backed apps | [python/](categories/python/README.md) |
| Admin dashboards | Back-office panels, forms, tables, analytics layouts | [admin-dashboards/](categories/admin-dashboards/README.md) |
| E-commerce | Storefronts, product catalogs, commerce backends | [ecommerce/](categories/ecommerce/README.md) |
| CMS, blogs & documentation | Content-managed websites, blogs, docs portals | [cms-blog-docs/](categories/cms-blog-docs/README.md) |
| Portfolio & business websites | Personal portfolios, agency sites, company landing pages | [portfolio-business/](categories/portfolio-business/README.md) |
| PHP & Laravel | PHP apps, admin panels, business systems | [php-laravel/](categories/php-laravel/README.md) |
| Education & LMS | Learning platforms and education portals | [education-lms/](categories/education-lms/README.md) |

## Recommended starting points

- **Modern SaaS:** [Next.js SaaS Starter](https://github.com/nextjs/saas-starter)
- **SaaS with a broader feature set:** [Open SaaS](https://github.com/wasp-lang/open-saas)
- **Python full-stack:** [Full Stack FastAPI Template](https://github.com/fastapi/full-stack-fastapi-template)
- **Admin dashboard:** [AdminLTE](https://github.com/ColorlibHQ/AdminLTE)
- **Commerce storefront:** [Medusa Next.js Starter](https://github.com/medusajs/nextjs-starter-medusa)
- **Content-driven Next.js sites:** [Payload](https://github.com/payloadcms/payload)

These are starting points to evaluate, not a claim that every feature is production-ready for your use case.

## How to choose and customize a template

1. **Pick the category** based on the product you want to build.
2. **Match the stack** to what you can maintain: for example, Next.js/TypeScript, Python/FastAPI, Django, or Laravel.
3. **Check the upstream license** and whether all bundled assets, fonts, and integrations have compatible terms.
4. **Read the README and inspect the demo** before copying or forking anything.
5. **Run it unchanged first** and record the exact setup steps.
6. **Customize in a fork or feature branch**, not directly on a production branch.
7. **Keep secrets out of Git**, use environment variables, and use test credentials and a test database.
8. **Run tests, dependency/security checks, and a production build** before deployment.

## Suggested template review checklist

- [ ] License and attribution requirements checked
- [ ] Recent maintenance and open issues reviewed
- [ ] Mobile layout and accessibility inspected
- [ ] Authentication and authorization reviewed (if included)
- [ ] Database migrations and backup strategy understood
- [ ] Payment integrations tested in sandbox mode only
- [ ] Environment variables documented; no secrets committed
- [ ] Tests and production build pass
- [ ] Deployment, monitoring, and rollback plan documented

## Contributing

Add entries to the appropriate category README. Each entry should include the upstream repository, purpose, stack, license link (only when verified), demo/documentation link, and any known caveats. Do not copy upstream source code into this catalog unless you have confirmed the license permits it and preserve all required notices.

## Disclaimer

This is a curated discovery list, not a security audit or endorsement. Technologies, maintainers, features, and licenses can change. Always verify the current upstream repository before adopting a project.
