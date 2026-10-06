# Portfolio design and differentiation review

Use before building a sibling app, product flavor, localized package, or white-label catalog.

## Similarity matrix

Create one row per proposed app and compare it with close siblings using facts.

| Dimension | Evidence | Weak differentiation |
|---|---|---|
| User problem | Trigger, task, outcome | Same task with renamed audience |
| Users/context | Who, where, why | Segment exists only for ASO |
| Core workflow | Journey from launch to value | Same screens in new order |
| Features | Repeated capabilities | One peripheral feature |
| Content/data | Ownership, depth, refresh | Same feed filtered by locale |
| Service/network | Human, device, backend value | Same API with new theme |
| Interaction/UI | Architecture and interaction | New colors, icons, or logo |
| Metadata | Honest promise and evidence | Synonyms and keyword swaps |
| Distribution | Content provider and developer | Vendor publishes client clones |
| Separate-app need | User harm if merged | “More keyword coverage” |

Do not calculate a fake uniqueness percentage. The matrix supports judgment; it is not a platform formula.

## Verdict

### Red

Same job, workflow, and feature set; variants differ mainly by brand, theme, locale, client, geography, or keywords; small content can be aggregated; the rationale is store coverage; or a saturated category has only a peripheral improvement. Unknown template provenance is an evidence blocker, not by itself proof of duplication.

### Amber

A real audience or service distinction exists, but the launch experience remains substantially similar; unique content is thin or easy to aggregate; the split depends more on an operational boundary than user value; or reviewers cannot reproduce the claimed difference.

### Green

Independent user problem or materially different workflow; substantial standalone value at launch; distinct service/data/device capability; clear user benefit from remaining separate; sustainable ownership and updates; and differences reviewers can reproduce.

Apply these product-risk descriptions alongside the separate evidence-readiness gates in [evidence-gates.md](evidence-gates.md). Green applies only to the named stage and inspected scope; planned functionality cannot support submission readiness. Green is not guaranteed approval.

## Architecture patterns

Prefer one app with accounts, workspaces, tenants, organization switching, provider pages, localization, regional content, modules, entitlements, deep links, Apple custom product pages, or Google custom store listings when the experience is shared.

Separate apps may be justified for genuinely different regulated entities, hardware products, security boundaries, incompatible audiences, or independent services. Document the user-facing reason; legal separation alone does not resolve repetitive-experience risk.

## Development checkpoints

- **Concept:** compare the one-sentence outcome with siblings and top results. Stop if keyword-driven.
- **Design:** compare the primary journey, content model, and recurring value.
- **Build:** record template provenance, assets, libraries, backends, and content rights. Refactoring is not differentiation.
- **Submission:** test claims, supply reviewer access, verify metadata, audit siblings, and refresh policies.
- **Portfolio:** track policy actions, stability, retention, ratings, support load, SDK/API deadlines, and revenue per maintenance hour. Merge or retire apps without independent value.
