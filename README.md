# OpenTable (opentable)

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

OpenTable is a global restaurant reservation platform owned by Booking Holdings. The OpenTable Partner Portal exposes restricted partner APIs for reservations, availability, restaurant content, reviews, and CRM integrations to approved partners.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/opentable/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Hospitality, Reservations, Restaurants

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-06-03

## APIs

### OpenTable Partner API
Restricted REST API for approved partners covering restaurant content, availability, reservations, and CRM. Access is granted through the OpenTable Partner Portal under contractual agreement.

**Human URL:** [https://dev.opentable.com/partner-portal](https://dev.opentable.com/partner-portal)

#### Tags:

 - REST, Partner, Reservations

#### Properties

- [Documentation](https://docs.opentable.com/)
- [Portal](https://dev.opentable.com/partner-portal)
- [SignUp](https://www.opentable.com/restaurant-solutions/api-partners/)
- [Sandbox](https://dev.opentable.com/partner-portal)
- [Authentication](https://docs.opentable.com/)
- [FAQ](https://www.opentable.com/restaurant-solutions/api-partners/faqs/)
- [Marketing](https://platform.opentable.com/)

### OpenTable Affiliate / Restaurant Search Widgets
Widget and reservation embeds for affiliate sites, plus restaurant search/availability for approved partners.

**Human URL:** [https://dev.opentable.com/partner-portal](https://dev.opentable.com/partner-portal)

#### Tags:

 - Affiliate, Widgets

#### Properties

- [Documentation](https://docs.opentable.com/)
- [SignUp](https://www.opentable.com/restaurant-solutions/api-partners/)
- [Portal](https://dev.opentable.com/partner-portal)

## Common Properties

- [GitHubOrganization](https://github.com/opentable)
- [LinkedIn](https://www.linkedin.com/company/opentable)
- [Website](https://www.opentable.com/)
- [Developer](https://dev.opentable.com/partner-portal)
- [Documentation](https://docs.opentable.com/)
- [Pricing](https://www.opentable.com/restaurant-solutions/plans/)
- [StatusPage](https://status.opentable.com/)
- [Support](https://support.opentable.com/)
- [FAQ](https://www.opentable.com/restaurant-solutions/api-partners/faqs/)
- [Tools — HorizonCalendar (Swift Calendar UI)](https://github.com/opentable/HorizonCalendar)
- [Tools — otj-pg-embedded (Java Embedded PostgreSQL)](https://github.com/opentable/otj-pg-embedded)
- [Tools — spur-ioc (Node.js Dependency Injection)](https://github.com/opentable/spur-ioc)
- [Tools — mercury-bot (Static Translation Bot)](https://github.com/opentable/mercury-bot)
- [Tools — eslint-config-opentable (Shared ESLint Config)](https://github.com/opentable/eslint-config-opentable)
- [Plans](plans/opentable-plans-pricing.yml)
- [RateLimits](rate-limits/opentable-rate-limits.yml)
- [FinOps](finops/opentable-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Restaurant Content and Directory | Programmatic access to restaurant profiles, locations, and metadata for approved partners. |
| Availability and Reservations | Real-time table availability lookups and reservation booking for partner experiences. |
| Reviews and Guest Data | Access to diner reviews and guest/CRM data for approved integrations under contract. |
| Sandbox Environment | Approved partners receive a sandbox for discovery and testing before production access. |

## Use Cases

| Name | Description |
|------|-------------|
| Embedded Restaurant Booking | Third-party apps and sites embed availability and booking flows to let diners reserve tables without leaving the partner experience. |
| Tech Stack Integration | Restaurants connect OpenTable to POS, CRM, and operations systems to unify reservation and guest data. |
| Affiliate Referrals | Affiliate partners surface OpenTable availability and earn from referred reservations. |

## Integrations

| Name | Description |
|------|-------------|
| POS Integrations | OpenTable integrates with point-of-sale systems to sync reservations, covers, and guest spend data with restaurant operations. |
| CRM and Marketing Platforms | Guest profile, reservation, and review data can flow to partner CRM and marketing tools through approved partner integrations. |
| Affiliate and Booking Widgets | Affiliate sites and third-party platforms embed OpenTable reservation widgets and deep links to surface real-time availability and drive bookings. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
