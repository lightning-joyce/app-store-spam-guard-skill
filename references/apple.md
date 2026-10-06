# Apple App Store: spam and template-app review

Last policy verification: 2026-10-06 (4.2, 4.2.6, 4.3). Re-check the [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/) before consequential advice.

## Guideline 4.3(a): multiple versions and duplicate submissions

Apple says not to create multiple Bundle IDs for the same app. Its example is a separate map app for every city instead of one worldwide app. For location, sports-team, university, or comparable variants, Apple recommends one app with variations delivered in-app.

Review messages and Apple forum reports show that comparisons may involve similar binaries, source code, assets, commercial templates, metadata, concepts, and apps submitted from one or multiple accounts. Do not turn those observations into a claim that code reuse alone is always prohibited. Evaluate the complete product and portfolio. Cosmetic changes do not cure a duplicate product.

## Guideline 4.3(b): saturated or indistinguishable concepts

Apple may reject an app indistinguishable from what is widely available even when the developer has no sibling apps. Current examples include dating, flashlights, sound effects, wallpapers, simple timers, and fortune telling. A new entrant needs a meaningfully different or improved experience.

A polished UI, narrow audience label, or small feature is weak evidence when the core experience remains a commodity clone. Establish a differentiated outcome, workflow, service, content advantage, or central capability.

## Related rules

### Guideline 4.2: minimum functionality

The app should provide adequate utility or lasting entertainment and be more than a repackaged website, marketing artifact, content aggregator, or link collection.

### Guideline 4.2.6: commercial templates and app-generation services

Apps made from a commercialized template or app-generation service are rejected unless submitted directly by the app's content provider. Template services should not submit on behalf of clients. Apple identifies two safer structures:

- the content provider submits its own customized, innovative app; or
- the template provider publishes one aggregate or picker-style binary containing client entries or pages.

Content ownership and the submitting account therefore matter independently of UI differentiation.

## Apple pre-build gate

For every proposed Bundle ID, answer:

1. What independent user problem does it solve?
2. Which primary workflow would disappear if merged with the sibling?
3. What unique content, service, data, or capability exists at launch?
4. Why is an in-app module, tenant, locale, or custom product page inadequate?
5. What remains distinct after removing the name, logo, and colors?
6. Is a template or third-party codebase also shipped by other developers?
7. Is the submitting developer the content provider when 4.2.6 applies?
8. Is the category saturated under 4.3(b), and what central experience is meaningfully better?

If answers rely mostly on branding, audience wording, geography, language, or keyword coverage, recommend aggregation or substantive redesign.

## Evidence for review notes

Prepare a factual table covering the target user, job-to-be-done, substantive launch capabilities, proprietary or licensed content, differences from named sibling apps, reason for a separate app, demo credentials where needed, review path, and content-provider authorization where applicable. Give reviewers reproducible evidence; avoid unsupported “first,” “only,” or “completely unique” claims. Apply [evidence-gates.md](evidence-gates.md) before a readiness verdict; use the rejection-response reference when Apple requests further evidence.
