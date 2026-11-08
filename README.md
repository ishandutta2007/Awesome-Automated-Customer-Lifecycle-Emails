# Awesome Automated Customer Lifecycle Emails

A curated list of platforms, tools, and open-source frameworks for automated customer lifecycle emails, event-triggered communication, and retention workflows.

---

## Sector Overview & Market Dynamics

The global email marketing and customer lifecycle automation market is estimated at **$11.5 billion** (expanding beyond **$22 billion by 2030** at ~15.4% CAGR), embedded within the broader **$50+ billion** marketing automation industry. The sector is **moderately to highly fragmented**: while mega-vendors like HubSpot, Twilio SendGrid, and Intuit Mailchimp command significant aggregate market share in transactional delivery and SMB marketing, specialized contenders (Klaviyo in e-commerce, Customer.io in product-led SaaS, and Braze/Iterable in enterprise mobile/omnichannel) have established strong defensible moats around distinct data models, preventing a single winner-take-all consolidation.

---

## SaaS Platforms

| Platform | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits | Best For / Focus |
|---|---|---|---|---|
| **HubSpot (Marketing Hub)** | **$11.5B – $11.8B market cap** (~$3.13B+ ARR) | **$15/month** (Starter, billed annually; $20/month billed monthly) for 1,000 marketing contacts & 1 seat | **Free-forever tier:** Up to 2 seats, 1,000 static CRM segments, and 2,000 marketing email sends/month (includes HubSpot branding; no multi-step workflows) | Inbound marketing, full CRM integration, and lifecycle lead nurturing |
| **Mailchimp (Intuit)** | **$10B acquisition valuation** (~$1.3B annual revenue) | **$13/month** (Essentials plan for 500 contacts, scaling with volume) | **Free-forever tier:** 250 contacts and 500 email sends/month (daily limit of 250 sends; 1 user seat, pre-built email templates) | SMBs, content creators, and broadcast-oriented newsletters |
| **Klaviyo** | **$5.8B – $6.3B market cap** (~$1.24B ARR; guiding ~$1.53B) | **$20/month** (Starter paid tier for 251–500 active profiles & 5,000 monthly email sends) | **Free-forever tier:** Up to 250 active profiles and 500 email sends/month (includes email support for first 60 days) | E-commerce brands, Shopify stores, and revenue-driven predictive lifecycle campaigns |
| **Braze** | **$5.2B – $5.6B market cap** (~$738M+ ARR) | **Starts at ~$50,000/year** (Entry-level Braze Go edition; annual contract based on MAUs & Action Credits) | **14-day free trial:** Guided product tour and sandbox testing; no permanent free plan | Enterprise cross-channel engagement (mobile push, in-app, SMS, email) |
| **ActiveCampaign** | **$3B valuation** (~$290M ARR) | **$15/month** (Starter tier for 1,000 contacts, billed annually) | **14-day free trial:** Full access to automation builder, CRM features, and templates up to small sandbox limit; no permanent free plan | SMB and mid-market behavioral automations, lead scoring, and sales pipelines |
| **SendGrid (Twilio)** | **$3B acquisition valuation** (~Twilio parent ~$10B+ market cap) | **$15/month** (Marketing Campaigns Basic 5K plan for up to 5,000 contacts & 15,000 sends/month; Email API Starts at $19.95/month) | **60-day free trial:** Capped at 100 emails/day during trial period; no permanent free tier | Developer-friendly transactional email delivery and programmatic lifecycle campaigns |
| **Iterable** | **$2B valuation** (~$200M ARR) | **Starts at ~$30,000/year** (Annual commitment based on active profile count, starting ~100k profiles) | **No free-forever tier & no public free trial:** Enterprise sales demo and bespoke proof-of-concept required | High-growth and enterprise-scale cross-channel journey orchestration |
| **Brevo** | **$1B valuation** (~$218M ARR) | **$9/month** (Starter plan with 5,000 emails/month and unlimited contact storage) | **Free-forever tier:** Unlimited contacts with a send limit of 300 emails/day (includes Brevo watermark) | High-contact / volume-based sending, cost-conscious SMBs, and integrated CRM |
| **Customer.io** | **~$700M valuation** (~$100M ARR) | **$100/month** (Essentials plan for up to 5,000 profiles & 1M emails/month; overages: $0.009/profile, $0.12/1k emails) | **14-day free trial:** Access to visual journey builder and event tracking; also offers 12 months free for early-stage startups (<$10M funding) | Product-led growth (PLG) SaaS, event-driven web/mobile behavioral workflows |
| **Kit (formerly ConvertKit)** | **~$450M valuation** (~$45M ARR) | **$15/month** (Creator plan for up to 300 subscribers with visual automation funnels) | **Free-forever tier:** Up to 10,000 subscribers for broadcast emails and landing pages (automated sequences & funnel builders require paid plans) | Newsletter operators, digital creators, course creators, and solopreneurs |

---

## Open-Source Frameworks & Self-Hosted Solutions

| Project | Description | Architecture / Capabilities | Status |
|---|---|---|---|
| **[Laudspeaker](https://github.com/laudspeaker/laudspeaker)** | Open-source alternative to Braze & Iterable | Event-triggered cross-channel messages (email, SMS, push), visual drag-and-drop journey builder, time delays, PostHog integration | Active |
| **[Mautic](https://github.com/mautic/mautic)** | Enterprise-grade marketing automation system | Complex campaigns, multi-stage segments, email builder, dynamic content, and CRM tracking | Mature / Active |
| **[Listmonk](https://github.com/knadh/listmonk)** | High-performance newsletter & mailing list manager | Single Go binary with PostgreSQL; multi-threaded SMTP queue, custom SQL segmentation, and fast templating | Active |
| **[Keila](https://github.com/pentacent/keila)** | Privacy-friendly newsletter platform | Written in Elixir; supports MJML/HTML templates, custom fields, and self-hosted privacy analytics | Active |

---

## Contribution Guidelines

Contributions are welcome! Please make sure any proposed platform meets the following criteria:
1. Provide verified starting tier pricing and specific free-tier/trial limits (no generic placeholders).
2. Clearly distinguish between billing notification templates and dedicated lifecycle/retention marketing systems.
