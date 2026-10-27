# Litzki Systems

Technical SEO, AI enablement and custom software by Thorsten Litzki: reporting portals, automation, tools and pages that search engines and AI agents can read.

**Measured, not estimated.** Every tool here works with real data and shows where each number comes from. No simulated scores, no AI-invented metrics.

## Open-source tools

| Repository | What it does | Licence |
|---|---|---|
| [seo-content-workflow](https://github.com/litzki-systems/seo-content-workflow) | Claude skill for German-language SEO copy: seven checked stages from brief to CMS package, with no invented experience, sources or metrics. Plugin for Claude Code, ZIP for claude.ai. | MIT |
| [briefing-generator](https://github.com/litzki-systems/briefing-generator) | 12 free briefing templates: fill them in your browser and hand them over as a fillable PDF. Live in [German](https://litzki-systems.com/de/werkzeuge/briefing-aufbau-erstellen/) and [English](https://litzki-systems.com/tools/how-to-write-a-brief/). | MIT |
| [seo-forecast](https://github.com/litzki-systems/seo-forecast) | Forecasts clicks, leads and ROI from search volume, position and device, with CTR curves whose source you can see. | MIT |
| [infra-check](https://github.com/litzki-systems/infra-check) | Checks a domain on five machine-readable signals: JSON-LD, llms.txt, robots.txt for AI crawlers, security headers and TLS. Command line, also for domain lists. | MIT |
| [chatgpt-render-check](https://github.com/litzki-systems/chatgpt-render-check) | Simulates how ChatGPT reportedly splits a fetched page into text chunks. Across 1,000 domains, a plain text conversion cut differently on 363 of 376 multi-chunk pages. | MIT |
| [gsc-ga4-export](https://github.com/litzki-systems/gsc-ga4-export) | Pulls Google Search Console and GA4 data, merges both sources and exports XLSX reports. Runs locally, no SaaS, no data leaving your machine. | MIT |

Free online: [QuickScan](https://validator.litzki-systems.com) checks how well search engines and AI agents can read a domain and how well it is secured.

## AI agents and AI enablement

- [sovp-agentrust-bridge](https://github.com/litzki-systems/sovp-agentrust-bridge) turns a SOVP attestation into an Ed25519-signed AgenTrust TRACE v0.2 trust record that passes `agentrust-trace-tests` at Level 0. Every field that would claim a strong guarantee is set to its weakest honest value. Apache 2.0, PyPI: [`litzki-sovp-agentrust-bridge`](https://pypi.org/project/litzki-sovp-agentrust-bridge/).
- [seo-content-workflow](https://github.com/litzki-systems/seo-content-workflow) is a Claude skill tested with and without the skill: 34 of 34 checks passed with it, 23 without.
- I build my own software with Claude Code: an SEO reporting portal, a CRM with an AI agent and the tools on this page.
- I have selected, trained and edited up to 40 freelance writers, trained a client's SEO team, and created a video course and SOPs.

## Research: Sovereign Validation Protocol (SOVP)

SOVP is a protocol for checking, before ingestion, that a signed identity document was produced by the holder of the Ed25519 key published in DNS for a host. It is research and an open specification, not a product.

- Specification: IETF Internet-Draft [draft-litzki-sovp-04](https://datatracker.ietf.org/doc/draft-litzki-sovp/), Individual Submission, Intended Status: Experimental
- Reference implementation: [sovp-python](https://github.com/litzki-systems/sovp-python), Apache 2.0 (PyPI: [`sovp`](https://pypi.org/project/sovp/))
- Bridge to AgenTrust TRACE: see [AI agents and AI enablement](#ai-agents-and-ai-enablement)

A scan reports one of three verdicts: **CERTIFIED**, **NOT_CONFORMANT** or **INCOMPLETE**. INCOMPLETE means the host could not be measured, for example because access was blocked. It is not a statement about the host's quality. Verdicts are part of the scan result, not of the signed identity document.

## Work with me

Custom development on request: SEO reporting portals, dashboards, automation and websites. Contact: https://litzki-systems.com/contact

---

### Kurz auf Deutsch

Technische SEO, AI Enablement und Individualsoftware von Thorsten Litzki. Grundsatz: **gemessen statt geschätzt**. Alle Werkzeuge oben sind Open Source (MIT): ein Claude-Skill für deutschsprachige SEO-Texte, ein Briefing-Generator, ein SEO-Prognose-Rechner, zwei Prüfwerkzeuge für maschinenlesbare Signale und ein lokaler Export für Search Console und GA4. Kostenlos online: der [QuickScan](https://validator.litzki-systems.com/?lang=de). Für KI-Agenten: eine Brücke von SOVP zu signierten AgenTrust-TRACE-Nachweisen (besteht die offizielle Testsuite auf Level 0). Ich baue meine Software selbst mit Claude Code und habe bis zu 40 Texterinnen und Texter sowie das SEO-Team eines Kunden geschult. SOVP ist Forschung und offenes Protokoll, kein Produkt. Individuelle Entwicklung auf Anfrage: https://litzki-systems.com/contact

---

Patent Pending, U.S. Provisional Patent Application No. 64/005,737
© 2026 Litzki Systems LLC
