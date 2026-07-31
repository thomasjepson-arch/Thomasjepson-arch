<div align="center">

# Hi, I'm Thomas Jepson 👋

**GTM Leader · Salesforce Data Cloud · AI Builder**

I work at the intersection of enterprise go-to-market and applied AI — helping Salesforce
Data Cloud teams move faster, know more, and win deals.

*Currently building AI systems that make GTM teams sharper, not busier.*

</div>

---

## 🧭 The through-line

Most people position a CDP from a slide. I wanted to know how one actually works — so
I rebuilt the core of Data 360 from scratch in plain SQL: identity resolution, calculated
insights, segment governance, consent enforcement, journey orchestration.

It turns out you argue about customer data differently once you've had to write the
survivorship rules yourself.

---

## 🛠️ What I'm building

### 🗄️ [Jepson CDP](https://github.com/thomasjepson-arch/jepson-cdp) — a Customer Data Platform, from scratch

A working CDP on Postgres, plus the marketing console to run it. No vendor. Every layer
readable and arguable.

| | |
|---|---|
| **Identity resolution** | Confidence-scored, not binary. Normalizes email (plus-addressing, Gmail dots), phone and address; eight rules from 1.00 down to 0.72; auto-merges above 0.90 and sends the ambiguous band to a **human review queue**. Verified at **precision 1.0 / recall 1.0** against injected duplicates. |
| **Over-merge guard** | Caps cluster size so a shared family tablet can't cascade eight people into one super-profile — caught and prevented in testing. |
| **Calculated insights** | ~50 derived attributes: RFM, lifecycle, share-of-wallet, browse→cart→buy funnel, margin, predicted next order. |
| **Governance** | Consent resolved most-restrictive-wins across sources, enforced at audience count, at enrollment, **and at every send**. |
| **Journey engine** | Deterministic SQL. Continuous and event-triggered entry, A/B splits, conditional branching, holdout groups, cross-journey fatigue caps. |
| **Measurement** | Opens, clicks, last-touch attribution, holdout lift — with small-sample warnings so nobody ships a conclusion off n=12. |

**Proven in operation:** 46.7 hours unattended · 91 engine ticks · **zero errors, zero
governance violations** · 1,546 synthetic profiles.

`Postgres` `Supabase` `SQL` `Claude`

---

### 🤖 Data 360 GTM Intelligence Agent

An AI-powered SMS agent for Salesforce Data Cloud GTM teams. It monitors 8 industry sources
overnight, synthesises the single most relevant Data Cloud development, and delivers a
curated brief to your phone at 6am — every morning, automatically.

- **Reply "1"** to any brief → a publish-ready thought leadership post in your voice
- **Ask anything** via SMS → answers with your role and competitive landscape baked in
- **Local portal** → PIN-protected dashboard for costs, drafts and personalisation
- **Always on** → macOS background service, zero maintenance

`Python` `Flask` `Anthropic Claude` `Twilio` `launchd` `ngrok`

---

## 🎯 Focus areas

**Salesforce Data Cloud** — GTM strategy, competitive positioning, customer data platform
architecture

**Applied AI** — agents that remove the grunt work of staying sharp, not chatbots that add to it

**Thought leadership** — turning platform developments into narratives that win deals

---

## 🧰 Tech I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres-336791?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)

---

<div align="center">

*"The best GTM teams don't read faster — they have better tools."*

</div>
