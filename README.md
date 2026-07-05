# PlanSwift (planswift)

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
