# Adcendo

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

Adcendo ApS is a clinical-stage biopharmaceutical company headquartered in Copenhagen, Denmark,
with US operations in Boston, Massachusetts, developing a new generation of antibody-drug
conjugates (ADCs) for cancers with high unmet medical need. Founded in 2017 out of research by
Lars Henning Engelholm and Niels Behrendt, its pipeline includes ADCE-T02 (Tissue Factor, in the
Phase 1b Tiffany-01 study), ADCE-D01 (uPARAP, granted FDA Fast Track designation for soft tissue
sarcoma), and the pre-clinical ADCE-B05.

- https://adcendo.com/

## API coverage

Adcendo publishes **no public API, no developer portal, and no machine-readable API contract**.
Probed on 2026-08-06: `/openapi.json`, `/swagger.json`, `/api-docs`, `/docs`, `/developers`,
`/api`, `/graphql`, `/llms.txt`, `/.well-known/agent-card.json`, `/.well-known/agent.json`,
`/.well-known/security.txt`, `/.well-known/openid-configuration`,
`/.well-known/oauth-authorization-server`, `/.well-known/api-catalog` and
`/.well-known/ai-plugin.json` all returned **404**; there is no `adcendo` GitHub organization.
The one JSON endpoint on the host is `https://adcendo.com/wp-json/` — the stock WordPress REST
API of the marketing CMS (LiteSpeed, Wordfence, Divi, Google Site Kit plugin routes), which is
website infrastructure and not a product API, so it is not cataloged as a developer offering.

This is an honest zero for a therapeutics developer, not a gap the company is expected to close.
It is recorded in `apis.yml` as `x-coverage: {state: none, reason: not-a-software-company}`.
