# Evidence gates for new apps and submission readiness

These are internal risk-management practices, not platform-mandated quotas. Scale the work to the product and the requested stage. Do not turn one rejection questionnaire into a universal Apple submission requirement.

## Concept: earn the right to build

Inspect the actual available developer catalog, planned products, and nearest market alternatives. A folder list is not the live catalog; a store listing is not proof of every implemented capability. Record sources, dates, coverage, and inaccessible comparisons. Do not infer that an account's app count caused enforcement.

Compare the closest workflow substitutes, including competitors that already have the proposed headline feature. For each, record the user's input, core decisions, useful output, and material limitation supported by evidence. Unknown competitor functionality must stay unknown, not become a claimed market gap.

Write a falsifiable hypothesis: "For [user doing a real task], [specific limitation] leads to [observable cost]; our [central workflow/capability] improves [outcome], demonstrated by [test]." A narrowly named audience, attractive UI, offline operation, PDF export, subscriptions, or 3D/AI alone is not enough. A combination may be substantive if its end-to-end benefit is demonstrable.

Recommend a small prototype or task trial when the hypothesis is untested. A concept can be promising while evidence remains Amber; do not require a completed beta before exploratory development. Recommend stopping or merging when the only independent rationale is search coverage or superficial segmentation.

## Build: preserve traceable claims

Maintain a concise evidence record in the app's existing documentation, not a parallel bureaucracy:

| Claim | Implementation/content source | Observed test or user evidence | Build/date | Limits or unknowns |
|---|---|---|---|---|

Distinguish planned, implemented, observed in the candidate build, and validated with target users. Recheck notes against the candidate build, not only a newer working tree. A passing test name or self-authored product document is not independent proof: inspect assertions, implementation boundaries, and output when claims matter. For example, direct top-face load checking must not be described as cumulative structural safety validation.

Audit provenance by component: product-specific domain logic, shared in-house infrastructure/UI, standard platform/third-party libraries, commercial templates, assets, datasets, and client content. Record origin, license/rights, sibling reuse, and role in the core experience. Hash matching can reveal exact duplicates, not prove originality. AI-assisted development alone establishes neither compliance nor a 4.2.6 violation; describe actual template lineage and ownership honestly without pretending generated code was hand-authored.

Compare related apps' primary journeys and domain behavior, not merely their names. Shared payments/settings are different from the same renamed input-list-detail-export application. Explain why consolidation would harm the actual user workflow; do not demand consolidation of unrelated useful products just because they share infrastructure.

## User evidence: distinguish quality from demand

Keep engineering QA, device validation, and real target-user validation separate. For a new unvalidated professional workflow, recommend representative users attempting realistic tasks before claiming submission readiness. Missing real-user evidence keeps the user-value claim unverified; it is not automatically a policy violation. An established service may already have relevant operational evidence without a new TestFlight beta.

Record anonymized participant role, date, build, task/input, observed result, feedback, and resulting change or reason no change was needed. Do not require invented fixes to fill a feedback template. Use a justified, product-appropriate sample, not an alleged Apple minimum number of testers, days, or interviews. Invitations/download counts alone do not prove task success. Empty current TestFlight lists do not rule out documented off-platform or past testing. Request missing facts rather than fabricate them.

Use consented, redacted evidence; do not place customer data, private reviewer correspondence, credentials, or participant identities in a public skill repository or review attachment unnecessarily. If testing needs external recruitment or communication, request the needed authorization; lack of participants is an evidence gap, not permission to message people.

## Submission: demonstrate, do not assert

Before recommending submission, verify:

- A current comparison supports the central differentiated outcome, including why this belongs in a separate app.
- Material review claims have evidence for the candidate build; important unknowns and unresolved review requests are explicit.
- Source/content ownership and meaningful reuse are understood, including the content-provider account when applicable.
- Target-user value is supported proportionately to the claims; engineering QA is not used as a substitute.
- Reviewers can reach and reproduce the central workflow, including paid features through the legitimate review flow; do not silently unlock different functionality just for reviewers.

Provide a short path with starting state/sample inputs, action, expected observable result, and implementation limits. Demonstrate consequential behavior: changing a meaningful input or constraint changes a useful result. Screenshots or a short video supplement, not replace, a working app. Notes should explain what the product does and its substantive differences, not recite "not a reskin" or promise to be unique.

When a gate is unmet, identify the smallest evidence-gathering or product task that resolves it. Do not present a recommendation to submit as safe simply because builds, screenshots, IAP configuration, or tests are complete. Never promise approval.
