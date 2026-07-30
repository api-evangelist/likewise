# LikeWise

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
