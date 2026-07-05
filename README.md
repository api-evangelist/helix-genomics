# Helix (helix-genomics)

Helix is a population genomics company operating an end-to-end precision health platform: a proprietary **Exome+** next-generation sequencing assay, a CLIA/CAP-certified clinical lab (CLIA #05D2117342, CAP #9382893), and bioinformatics tooling. The platform enables health systems, life sciences companies, and payers to integrate genomic data into clinical care and research at population scale, on a "Sequence Once, Query Often" model.

Through its **DNA Product Studio**, Helix exposes a partner-gated developer surface for building DNA-powered products:

- **Genomics API** — direct programmatic access to more than 100 million base pairs, including SNPs, indels, and copy number variants, with panel-grade coverage of clinically important regions (ACMG actionable genes, carrier screening, hereditary cancer, hereditary cardiovascular disease).
- **Ancestry API** — continental ancestry across 6 global populations or regional ancestry across 26+ populations.
- **Insight API** — user-specific results for hundreds of genetic traits and conditions, from single-marker traits to machine-learning polygenic risk scores.

Partners build on top of these APIs via **Embedded Apps** (launched on the Helix platform with no coding or hosting) or the **App Acceleration Framework** (white-label standalone web and mobile DNA apps).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/helix-genomics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/helix-genomics/refs/heads/main/apis.yml)

## Access Model

**Enterprise / partner-gated — not public self-serve.** Helix does not publish an open developer portal, a public API base URL, or a machine-readable API specification (OpenAPI/AsyncAPI). The Genomics, Ancestry, and Insight APIs are provisioned through Helix partnerships, and API access presupposes a sequencing relationship with Helix's own CLIA/CAP lab. Because no open reference exists, the API entries in `apis.yml` are **modeled** from Helix's public product documentation — no endpoint paths, base URLs, or auth schemes were fabricated.

## Pricing

B2B / contact-sales. Helix does not publish self-serve API pricing. Platform commercials are structured around offerings such as **Helix Genomic Advantage™** (subscription-based pricing for health systems), the **Helix Research Network®**, and **Helix Precision Pathway™**, all engaged directly through Helix's partnerships team. No public plans, rate-limit, or FinOps documents were created because no sourced pricing details are published.

## WebSocket / Realtime

No documented public WebSocket API. No realtime, bidirectional, or streaming (ws:// or wss://) endpoint is documented anywhere on Helix's platform. See `review.yml`.

## Tags

- Genomics
- Population Genomics
- Sequencing
- Exome
- Precision Health
- Bioinformatics
- Healthcare
- DNA
- Partner API

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs

### Helix Genomics API

Partner-gated programmatic access to Helix Exome+ sequencing data — 100M+ base pairs including SNPs, indels, and copy number variants, with panel-grade coverage of ACMG actionable genes, carrier screening, hereditary cancer, and hereditary cardiovascular disease.

- **Human URL:** [https://genomics.helix.com/](https://genomics.helix.com/)

### Helix Ancestry API

Partner-gated ancestry results derived from a participant's Exome+ sequence — continental ancestry across 6 global populations or regional ancestry across 26+ populations.

- **Human URL:** [https://genomics.helix.com/](https://genomics.helix.com/)

### Helix Insight API

Partner-gated user-specific results for hundreds of genetic traits and conditions, from single-marker traits to machine-learning polygenic risk scores computed over Helix Exome+ data.

- **Human URL:** [https://genomics.helix.com/](https://genomics.helix.com/)

## Common Properties

- [Website](https://www.helix.com)
- [LinkedIn](https://www.linkedin.com/company/my-helix)
- [Documentation](https://genomics.helix.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
