# Helix (helix-genomics)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
