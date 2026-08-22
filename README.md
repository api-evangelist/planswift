# PlanSwift (planswift)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

PlanSwift is Windows desktop takeoff and estimating software for construction estimators, owned by **ConstructConnect**. It turns digital plans (PDF, image, and CAD) into measurable, countable, exportable material takeoffs and estimates across trades such as roofing, concrete, earthwork, flooring, and electrical.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/planswift/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/planswift/refs/heads/main/apis.yml)

## Access model — read this first (honest stub)

**PlanSwift does not publish a public web/REST API.** There is no HTTPS base URL, no API keys or OAuth, and no documented web endpoints. This entry is an honest stub: PlanSwift's developer surface is a **desktop extensibility SDK embedded in the Windows application**, not a network API.

Third parties extend PlanSwift through:

- **OLE Automation (COM)** — drive/automate PlanSwift from external Windows applications via the Component Object Model.
- **Scripting** — an internal scripting engine for extending PlanSwift behavior from inside the app.
- **Plugins and Starter Packs** — plugins add features; starter packs add trade-specific templates, parts, and assemblies.

Developer tooling is exposed through a password-gated **"Under-The-Hood" (U-T-H) tab**. The password is obtained by contacting ConstructConnect at **takeoff@constructconnect.com**. ConstructConnect warns that back-end modifications are unsupported and are lost on reinstall.

The only public code artifacts are legacy SDK examples on GitHub for **PlanSwift9**:

- `PlanSwift/sdk-examples-2008` — Pascal (2008)
- `PlanSwift/sdk-examples-2010` — Visual Basic (2010)

Because there is no network API surface, no OpenAPI or AsyncAPI document was authored and no `apis[]` are listed in `apis.yml`. See `review.yml` for the full assessment.

## Tags

- Construction
- Takeoff
- Estimating
- Desktop Software
- Plugin SDK
- OLE Automation
- COM
- Scripting
- ConstructConnect
- No Public Web API

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## Pricing (per seat)

PlanSwift is licensed per seat for the desktop product; the extensibility SDK ships inside the licensed application (there is no separate API subscription). Public pricing is inconsistent and ConstructConnect increasingly quotes directly. Commonly cited public figures:

- ~**$1,749** one-time (perpetual) with first-year updates + support; ~$250/license/year to renew, **or**
- ~**$2,000** per user per year (annual) with first-year training, updates + support; ~$300/license/year to renew.

A free trial is available at [planswift.com/free-trial](https://www.planswift.com/free-trial/). See `plans/planswift-plans-pricing.yml`. Confirm with a quote via [ConstructConnect](https://www.constructconnect.com/products/planswift).

## Common Properties

- [GitHub Organization](https://github.com/PlanSwift)
- [LinkedIn](https://www.linkedin.com/company/planswift)
- [Website](https://www.planswift.com)
- [Documentation](https://help.constructconnect.com/planswift-developer-documentation-234)
- [Plans](plans/planswift-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
