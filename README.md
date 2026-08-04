# LikeWise

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

**Status: defunct / acquired — no live API surface.**

Likewise Software was a Bellevue, Washington enterprise software company building storage, identity and
security products that bridged Linux, Unix and Mac systems into Microsoft Active Directory environments.

- **Likewise Storage Services** — OEM SMB/CIFS multi-protocol file access licensed to network storage
  vendors (HP StorageWorks, Riverbed, EMC Data Domain and NetApp were named on the archived site).
- **Likewise Data Analytics and Governance** — auditing, reporting and governance over unstructured data,
  with a compliance resource center covering HIPAA, PCI DSS, SOX and FISMA.
- **Likewise Enterprise / Likewise Open** — Active Directory integration for Linux, Unix and Mac;
  subsequently part of BeyondTrust.

Backed by: trinity-ventures — listed as **Acquired** in the Trinity Ventures exited portfolio.

## Why this repo has no artifacts

The enrichment pipeline ran on 2026-07-19 and found no live surface to harvest:

| Probe | Result |
|---|---|
| `https://likewise.com/` | 301 → `pix-media.com` (unrelated owner) |
| `https://likewisesoftware.com/` | does not resolve |
| `https://likewise.io/` | 307 → parked, listed for sale |

There is no OpenAPI, AsyncAPI, SDK, package, MCP server, well-known document, changelog, CLI or
authentication surface to search, generate or derive from — so none were fabricated. Domain-security
probing was deliberately skipped: `likewise.com` now belongs to an unrelated party and its posture would
not describe this company.

Last archived homepage: <http://web.archive.org/web/20120704072229/http://likewise.com/>
