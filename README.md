# Awesome-Automated-Customer-Lifecycle-Emails

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **"Chargebee Welcome Emails" is not a lifecycle email platform**, and the open-source side is thinner than your emphasis suggests.



## The data problems



**"Chargebee Welcome Emails" is not a standalone product.** It is an email notification template inside Chargebee's billing platform—you add customer and subscription details to the welcome email sent on signup . Listing it alongside Customer.io or Braze misleads readers. Chargebee is a billing platform that sends transactional notifications, not a lifecycle marketing platform.



**Customer.io's pricing is now published, but the entry point is higher than expected.** Essentials **starts at $100/month** (billed monthly); Premium **$1,000/month** (billed yearly); Enterprise custom . Overages: **$0.009/profile**, **$0.12 per 1,000 emails** . The free "Startup Program" gives **12 months free for companies raised under $10M** .



**SendGrid Marketing Campaigns has no free tier in 2026.** The smallest paid tier is **Basic 5K at $15/month for 5,000 contacts**—there is no 500 or 1,000 tier; the ladder jumps from a 100-contact trial straight to 5,000 . A weekly newsletter to 5,000 subscribers actually costs **~$42/month** after overages .



**Iterable, Braze, and Klaviyo have no public self-serve price table.**

- **Iterable**: quote-only, enterprise cross-channel .

- **Braze**: value-based pricing on platform edition + active users + flexible credits; no public figures .

- **Klaviyo**: free plan up to **250 profiles, 500 emails/month**; paid **from $20/month**, scaling with active profiles .



**Mailchimp, ActiveCampaign, Brevo, and ConvertKit surfaced no pricing in these results.** Do not fabricate.



## Open-source: what actually exists



| Project | What it actually does | Status |

|---|---|---|

| **Laudspeaker** | Open-source Braze/Iterable alternative; **event-triggered cross-channel messages** (email, SMS, push); no-code journey builder; time delays and windows for drip campaigns; user segments; PostHog plugin  | Active (Y Combinator launch, Oct 2026) |

| **Mautic** | Marketing automation with campaigns, segments, and email builder; **~30,000 live websites** running Mautic tracking; **350 free trial signups/month** via Dropsolid  | Mature, active |

| **Listmonk** | Self-hosted newsletter and mailing list manager; single binary + PostgreSQL; **one-way mailing lists** with SQL segmentation; Go templating; multi-SMTP queues  | Active (v7.0.0-beta.1, Oct 2026) |

| **Keila** | Newsletter tool with **MJML/HTML templates and content slots**; reusable templates with editable regions; Liquid support  | Active (v0.30.0, Jun 2026) |



**None of these are direct replacements for Braze or Iterable's cross-channel orchestration.** Laudspeaker is the closest—it explicitly positions itself as an open-source Braze/Iterable alternative with email, SMS, and push . Mautic is the most mature for email-only automation . Listmonk and Keila are newsletter engines, not lifecycle automation platforms .



**No star counts surfaced for any of these projects.** Do not invent them.



## What I recommend



**Remove "Chargebee Welcome Emails"** from the platform list. It is a billing notification template, not a lifecycle email platform .



**The SaaS section has verified pricing for Customer.io, SendGrid, and Klaviyo.** Iterable, Braze, Mailchimp, ActiveCampaign, Brevo, and ConvertKit should be marked **"quote-only"** or **"pricing not surfaced."**



**The open-source section should be led by Laudspeaker** for cross-channel lifecycle automation , with **Mautic** as the mature email-only alternative , and **Listmonk** and **Keila** as newsletter engines .



**Flag the pricing model differences explicitly:** per-profile (Customer.io, Klaviyo), per-contact-storage (SendGrid), value-based (Braze), and quote-only (Iterable) produce wildly different costs at the same list size. A reader choosing between them needs that context—SendGrid's $15 plan is a $42 plan for a normal weekly cadence .



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate star counts, present Chargebee as a lifecycle email platform, or cite Iterable/Braze pricing that the results do not contain.
