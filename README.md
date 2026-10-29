# Dimetrius Engine Portfolio

Static portfolio website. The page is served publicly through `dimetrius-eng.tech/`; the existing Cloudflare Worker remains the domain router and sends `/gadget-store-crm/*` requests to the CRM.

## Deploy

Connect this repository to Cloudflare Pages and use its `pages.dev` address as the Worker origin for the portfolio. Do not attach `dimetrius-eng.tech` directly to this Pages project while the Worker route owns that hostname.