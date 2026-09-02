---
name: app-store-spam-guard
description: Plan, build, or audit app concepts and portfolios to reduce Apple App Store Guideline 4.3(a)/(b), Apple template-app, and Google Play repetitive-content, spam, and minimum-functionality risk. Use for new app ideation, white-label or multi-app architecture, pre-submission review, portfolio expansion, or responding to a spam rejection.
---

# App Store Spam Guard

Help the user create products that are genuinely distinct and useful. Do not optimize for disguising clones or evading review systems.

## Route the task

1. Identify the requested mode: concept review, implementation or metadata review, multi-app or white-label architecture, portfolio audit, or rejection response.
2. Establish the comparison set: the developer's existing and planned apps, apps from related accounts or template vendors, and close products already common in the target store.
3. Read the relevant reference before judging the app:
   - Apple: [references/apple.md](references/apple.md)
   - Google Play: [references/google-play.md](references/google-play.md)
   - Portfolio structure: [references/portfolio-design.md](references/portfolio-design.md)
   - Existing rejection: [references/rejection-response.md](references/rejection-response.md)
4. For decisions that could cause submission, rejection, suspension, or account-level risk, verify current language on the official Apple or Google pages and record the date. Treat forums, Reddit, X, and other community reports only as enforcement signals. See [references/sources.md](references/sources.md).

## Evaluate substance, not cosmetics

Compare each app across:

- core user problem and promised outcome;
- target users and usage context;
- unique content, data, services, or network;
- primary workflows and feature set;
- information architecture, interaction model, and visual system;
- binary, source, dependencies, assets, and template lineage;
- title, description, screenshots, icon, and positioning;
- content provider, brand owner, and submitting developer;
- reason the product must be separate instead of a module, tenant, locale, custom product page, or custom store listing.

Changing only the name, icon, colors, screenshots, language, geographic content, or keywords is not meaningful product differentiation. Shared infrastructure is not automatically prohibited, but the resulting product must deliver distinct value and experience. Apple may also consider binary, source-code, asset, template, metadata, and concept similarity.

## Choose an architecture

Prefer one aggregated app when variants share the same core job and workflows and mainly differ by client, city, team, school, language, catalog, or branding. Use modules, tenant selection, search, localization, in-app content, Apple custom product pages, or Google Play custom store listings where appropriate.

Keep separate apps only when each has an independent product reason, adequate standalone functionality and content, materially different workflows or services, and a sustainable maintenance plan. For white-label work, apply the platform-specific ownership and account guidance in the references.

## Report the decision

Return:

1. **Verdict:** Green, Amber, or Red for each store. This is a qualitative engineering review, not an approval probability.
2. **Policy mapping:** specific clauses and observed facts.
3. **Nearest comparisons:** similarities to the developer's catalog and saturated market patterns.
4. **Required product changes:** functionality, content, workflow, architecture, or ownership—not merely presentation.
5. **Merge vs. split recommendation:** product and maintenance rationale.
6. **Evidence packet:** a concise differentiation table and reviewer notes with testable facts.
7. **Unknowns:** information to verify before submission.

Use the user's language unless requested otherwise. Separate official requirements, internal heuristics, and community observations explicitly.

## Hard stops

- Never recommend new bundle/package IDs, alternate accounts, obfuscation, superficial redesigns, metadata tricks, or staggered submissions to evade similarity detection.
- Never claim a design is guaranteed to pass review.
- Do not infer that an approved competitor or sibling proves compliance.
- After a spam rejection, do not recommend repeated resubmission until the cited issue and broader catalog have been materially audited.
- Do not invent thresholds such as a required percentage of unique code or screens; neither platform publishes such a safe harbor.
