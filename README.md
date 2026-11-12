# ONE — Public website

Independent static public landing page for Work in ONE.

**Scope:** public informational website only. No authentication, APIs, tracking, client records, business data, or external dependencies. The live ONE application and identity staging are separate systems.

## Azure Static Web Apps — Free

Create a new Azure Static Web App (Free), connect GitHub repo `JPAccountancy/one-public-web` and branch `main`, and use:

- Framework preset: **Custom**
- App location: `/`
- API location: *(empty)*
- Output location: *(empty)*

The repository root contains `index.html` and `staticwebapp.config.json` — no build step is needed. Let Azure generate its deployment workflow and scoped GitHub secret. Do not commit or share any deployment tokens.

Verify the generated `https://...azurestaticapps.net/` website before changing the website's domain DNS. Map `www.workinone.com.au` and `workinone.com.au` using Azure's displayed DNS instructions, while preserving all existing Microsoft 365 email records. Confirm HTTPS and DNS before retiring the Lovable version.

**Azure trial warning:** A Free Trial subscription can be disabled after the trial credit expires unless upgraded; Free-tier services do not prevent this. Review subscriptions and billable resources before changing billing.

Design: ONE landing page approved 12 November 2026. Tagline: *Built from Practice, Not Prediction.*
