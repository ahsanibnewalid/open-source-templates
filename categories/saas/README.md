# SaaS & Subscription Applications

For products with accounts, organization workspaces, billing, customer portals, and subscription plans.

| Project | What to explore | Stack / notes |
|---|---|---|
| [Next.js SaaS Starter](https://github.com/nextjs/saas-starter) | Starter for a subscription web app | Next.js, PostgreSQL, Stripe, shadcn/ui; verify current setup and payment requirements |
| [Open SaaS](https://github.com/wasp-lang/open-saas) | Broader SaaS starter with app features | React, Node.js, Prisma, Wasp; inspect its current supported integrations |
| [BoxyHQ SaaS Starter Kit](https://github.com/boxyhq/saas-starter-kit) | Enterprise-oriented SaaS patterns | Next.js ecosystem; useful to study SSO and organization-oriented architecture |
| [Nextacular](https://github.com/nextacular/nextacular) | Next.js SaaS boilerplate | Evaluate maintenance and compatibility before choosing |

**Customization ideas:** brand/theme, pricing page, tenant onboarding, role-based access, invoices, email templates, audit logs.

**Before launch:** review tenant isolation, auth/session handling, billing webhooks, cancellation/refund logic, privacy obligations, and rate limiting. A starter's presence of a feature does not mean it is secure or production-ready.
