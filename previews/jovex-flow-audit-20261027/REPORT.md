# JOVEX / Flow Ninja reference audit — 27 October 2026

**Status: JOVEX audit completed; direct Flow Ninja visual comparison blocked by missing reference evidence. Audit only. No application changes.**

## 1. Decision and authoritative implementation

Use **feat/jovex-obsidian-chrome-20261025**, commit **131d184338960ae658f1ef40cd1ef0ca971677f5**, as the authoritative implemented Ninja-inspired JOVEX baseline for this audit. This is a repository-evidence determination, not a claim that a new design has been approved today. It contains the latest implemented identity in the relevant agency lineage and explicitly supersedes red, wine, ivory and cream. The later design-reference-anchors branch documents Orbital/Agencera source links and a sample-only exercise; it contains no replacement agency implementation.

Do not use feat/jovex-website, the shoe/storefront branches, or the ivory editorial rendering as the approved foundation. Do not integrate the separate UI Lab into the agency site on the basis of this audit.

| Branch | Commit | Actual role / evidence |
| --- | --- | --- |
| main | 47ff039 | Only AGENTS.md and README.md; rules, not the new agency implementation |
| feat/jovex-flow-reference-redesign | d22f68e | Three files: rules, README, reference blueprint. Requirements only; no site source, no browser-renderable implementation |
| review/jovex-flow-implementation-20261024 | 8403fe5 | First implemented 13-page reference-led agency architecture; vivid red; historical, superseded palette |
| feat/jovex-editorial-visual-refinement | cb757bd | Ivory/wine identity over that architecture; superseded |
| feat/jovex-next-visual-interactions-20261024 | bc73380 | Portfolio framing/reveals and interactions; immediate ancestor of the dark branch; superseded agency palette |
| feat/jovex-obsidian-chrome-20261025 | 131d184 | Current implemented 13-page architecture, Obsidian & Chrome identity, concept journeys, evidence and tests |
| design-reference-anchors | 627aeba | Later reference-source brief only; Orbital/Agencera images explicitly not retained as exact approved screenshots |
| feat/jovex-website | 8cdd1a9 | Separate earlier Next.js storefront/problem-card implementation; not an ancestor of the current agency branch |
| feat/jovex-streetwear-storefront-v1 | 29fa925 | Earlier storefront branch; excluded |
| feat/jovex-direct-implementation | aa65cd7 | Earlier footwear comparison work; excluded |
| feat/jovex-approved-four-stage-build | 3cf8ffb | Earlier storefront staging; excluded despite its historical name |
| preview/jovex-ui-lab | d10a533 | Standalone experiments; no authority to replace the agency design |
| test/codex-github-access | 7f3baa2 | Connectivity test; no design authority |

The Flow planning, first red implementation, editorial refinement, interaction branch, and Obsidian branch form an ancestor chain. The old storefront branches do not. See evidence/branches.json for exact SHAs, tracked-file counts and ancestor checks. No PR merge or production status is inferred from a branch name.

### Files responsible for the actual current rendering

| File | Responsibility |
| --- | --- |
| src/site.mjs | Original copy/data, 13 route definitions, header/footer, home, services, two concept details, About and inquiry markup. Route definitions near lines 13–25; shared shell 31–39; homepage 65–66; service selector 50–51; work/concept pages 77–82 |
| public/styles.css | Base layout, responsive grids/breakpoints, hero rings, original CSS/SVG compositions and local system type. It is compacted into long lines; inspect selectors, not only line numbers |
| public/identity.css | Authoritative agency dark tokens, later chrome overrides, illustration materials, motion and reduced-motion rules. Earlier declarations coexist with later overrides; final computed styles determine appearance |
| public/site.js | Mobile disclosure, service tabs/keyboard, URL-aware filters, concept stages, local unsent email draft, progressive portfolio reveals |
| public/favicon.svg | Original JOVEX favicon |
| scripts/build.mjs | Static generation from site.mjs; 13 routes plus generated 404, sitemap and robots |
| scripts/serve.mjs | Local audit serving only; never published as production |
| docs/JOVEX_OBSIDIAN_DESIGN.md and AGENTS.md | Most recent implemented identity/scope; explicitly supersede earlier palettes and old storefront modules |

There is no Next.js runtime in this authoritative branch. Its package contains Node standard-library scripts and no external runtime dependency. Do not transplant the old Next.js storefront architecture into it.

## 2. Reference integrity: three distinct evidence sets

### A. Today's requested Flow Ninja site

Requested origin: https://www.flowninja.com/ . HEAD through the inherited environment proxy returns **403 Forbidden at CONNECT**, curl exit **56**, destination HTTP status **000**. Chromium navigation independently fails with **net::ERR_TUNNEL_CONNECTION_FAILED**. The destination page is not reached. No Flow Ninja page, mobile screenshot, font, image, DOM, service page, work page, case study or animation was inspected live in this run. See evidence/reference-network.txt and browser-audit.json. No proxy bypass, alternative mirror, fabricated screenshot or generated reference was used.

### B. Historical Flow Ninja observations, 24–25 October

Repository documents JOVEX_REFERENCE_AUDIT.md, JOVEX_REFERENCE_BLUEPRINT.md and JOVEX_OBSIDIAN_DESIGN.md describe earlier web-content reads: WebOps hero; URL-audit entry; consultation/demo CTA; client proof; work; four service tabs; differentiators; testimonials/awards/results; agency information; closing conversion. Service paths recorded include /services/web-design, /services/website-development, /services/website-maintenance and /services/growth, plus /our-work, /meet-flow-ninja and /lets-talk-flow.

Those are **historical textual observations**, not today's verified site and not pixel-level desktop/mobile evidence. Their writers explicitly state that reference visual/interaction inspection remained incomplete. They cannot establish current navigation geometry, font family, image crop, breakpoint, exact section order or animation behavior.

### C. Earlier approved reference screenshots

The historical blueprint mentions an earlier blue/purple Flow Ninja screenshot. No actual file for that screenshot was found in the inspected branch tips, image history, attachments or library folders. Exact screenshot date, URL, viewport, visible states and full-page coverage are unavailable. The pasted images earlier in the conversation show other JOVEX directions, not a recoverable approved Flow Ninja screenshot set. No exact version match is claimed.

The newer Orbital Studio/Agencera brief contains links and desired traits, not exact approved screenshot files. Those references and the eight UI experiments are not substituted for Flow Ninja.

**Consequently a genuine Flow Ninja-versus-JOVEX side-by-side cannot be delivered from available evidence.** The review board instead provides actual JOVEX desktop/mobile pairs and explicitly labeled red-history-versus-current pairs. Historical JOVEX screenshots are never labeled Flow Ninja or presented as an approved foundation. A blank/error response is not passed off as a screenshot of the reference.

## 3. Rendered JOVEX inventory and comparison by area

All JOVEX observations below are from fresh Chromium rendering of the pinned branch; desktop 1440×900 and mobile 390×900 captures are supplied. Layout measurements also cover 320, 375, 430 and 768 CSS pixels. They are viewport simulations, not physical iPhone/Safari tests.

| Area | Today's Flow Ninja evidence | Historical reference evidence | Actual JOVEX / gaps / visual judgment |
| --- | --- | --- | --- |
| Homepage structure | Unavailable | Textual positioning → work/proof → services → differentiation → conversion | Hero → capability strip → two concepts → four-service selector → principles → four delivery steps → FAQ → closing CTA → footer. Core agency funnel exists. No website-URL audit tool, proof band, testimonials, awards/results or team photography. Unsupported proof is an intentional exclusion, not permission to invent it |
| Hero | Unavailable | Earlier screenshot described as blue/purple; no image file; later text says WebOps | Centered two-line original headline, supporting copy, two CTAs, static contour/ring geometry. Dark canvas and chrome buttons are consistent. No photography/video or large project mockup anchors the opening. Desktop hero 735px; 390px mobile hero 670px after a 71px header. Work begins around y=845 mobile; both CTAs are visible before it |
| Navigation | Unavailable; cannot infer a mega-menu | Historical text identifies agency/service/work/contact paths | Sticky JOVEX header, three nav links plus Let's talk; mobile Menu disclosure below 581px, Escape/focus restore/outside-click logic. Current layout is compact and functional; no evidence justifies adding a reference-specific mega-menu yet |
| Services | Unavailable | Four service tabs and deeper service journeys documented | Four working tabs; mobile compact grid; four complete detail pages with deliverables/process/FAQ/prefilled inquiry. Shared template is coherent but repeated, and the illustrations are small CSS studies rather than rich showcases. Two labels in the growth diagram are white-on-white; browser micro-label has residual wine/gray coloring and insufficient contrast |
| Portfolio | Unavailable | Work collection/case studies documented | Two large staggered cards on desktop; stacked on mobile; labeled concepts; filters and URLs work. Original geometric Fieldwork and small Orbit UI are consistent but cannot stand in for immersive full project imagery. No commissioned portfolio is claimed. Portfolio section must be scrolled before full-page capture so progressive reveals are visible |
| Case studies | Unavailable | Dedicated case-study organization described; exact narrative/visual composition unknown | /work/fieldwork and /work/orbit show a question, direction, scope, one interaction and next-concept/contact navigation. Honest self-initiated demos. Thin long-form visual storytelling: no sequence of full interface screens, responsive mockup set, research evidence or documented outcomes. Do not invent business outcomes |
| Typography | Unavailable; current font/weight/width unmeasured | No reliable visual font evidence | Arial/Helvetica system sans, large tight tracking, 42px service heading at narrow widths, 108px desktop hero and 46px mobile hero in the fresh route measurements. Chrome gradient emphasis and tiny uppercase labels. Functional system type is legitimate; distinctiveness and very small diagram/micro-label readability need review after true reference capture |
| Imagery/material | Unavailable | No licensed reference images retained | Zero img, video or canvas nodes on every audited route: visual work is CSS/SVG and text. Original and rights-documented, not copied client imagery. Gloss appears mostly in buttons, headline and modest frame highlights; case art remains illustrative rather than photographic. This is a gap against the requested immersive premium direction, not a proven mismatch to an unseen screenshot |
| Colors | Unavailable | Earlier blue screenshot/red translation and later ivory are superseded | Body/header #090A0C; graphite sections #111318; work #0D0F13; positioning #12151A; chrome #D7DCE4; text #F1F3F6. The agency is dark and consistent, not an ivory foundation. Compatibility names such as accent-red do not mean rendered red. Residual diagram contrast and duplicate surface-raised definition need attention |
| Motion/interactions | Unavailable; no timing comparison possible | Historical interaction purposes only | 280ms service-panel entrance, 550ms portfolio reveal, fine-pointer card lift -3px and artwork scale 1.025 verified. Tabs/filter/concept/draft flows work. No continuous immersive scroll scene, hero film or major section transition is present; absence is not automatically a defect because current design notes explicitly avoid heavy motion. No new lab technique is approved here |
| Mobile | Unavailable | Earlier mobile geometry not recorded | 390/430/768/1440 route layouts pass bounds checks. 320 and 375 reveal actual deliverable-grid overflow below. Screenshots show deliberate stacked portfolio, controls and CTAs, but only Chromium was exercised |
| Footer/contact | Unavailable | Qualification/consultation conversion documented | Original link-rich footer and contact page; browser-local validated email draft only. Sending/booking/backend not connected and explicitly not implied. Preserve that truthfulness; converting to live delivery would be a separate implementation/data-handling scope |

Fresh page pairs: screenshots/jovex-home-{1440,390}.jpg; jovex-services-{1440,390}.jpg; jovex-services-website-design-{1440,390}.jpg; jovex-work-{1440,390}.jpg; jovex-work-fieldwork-{1440,390}.jpg; jovex-work-orbit-{1440,390}.jpg; jovex-about-{1440,390}.jpg; jovex-contact-{1440,390}.jpg. All 13 routes have full-page captures at both widths.

## 4. Confirmed defects and specific shortcomings

### F01 — P0 / Reference evidence incomplete

No directly comparable approved Flow Ninja screenshot or accessible current site. This blocks legitimate reference-fidelity percentages, exact section/layout/color differences, motion matching and font identification. Do not start reference-led visual development by guessing. Obtain dated original approved desktop/mobile files and separately capture the live site once the permitted environment can reach it.

### F02 — P1 / Deliverable grids overflow narrow screens

Fresh viewport checks detect three failures:

| Page | Requested width | document clientWidth | document scrollWidth / innerWidth |
| --- | ---: | ---: | ---: |
| /services/redesign-rebranding/ | 320 | 320 | 344 |
| /services/lead-generation/ | 320 | 320 | 373 |
| /services/lead-generation/ | 375 | 375 | 377 |

The two-column deliverable grid retains content-sized columns. Text such as 'CRM-ready workflow specification' and 'Testing & optimization recommendations' expands the right column. The actual list item's right edge reaches ~373px in a 320px viewport. Source targets: public/styles.css .deliverable-grid and its narrow-screen rules; src/site.mjs servicePage deliverable markup. Decorative out-of-bounds glows are clipped and are not, by themselves, proof of page overflow.

Old QA compares document scrollWidth to innerWidth; mobile shrink-to-fit can inflate both and hide this failure. Future checks must compare clientWidth and scrollWidth against the configured viewport. Do not just add overflow:hidden to mask inaccessible content. Evidence: overflow-growth-320.jpg, overflow-growth-375.jpg, overflow-rebranding-320.jpg, targeted-findings.json.

### F03 — P1 / Growth illustration loses its meaning

'01 Discover' and '02 Understand' resolve to foreground **rgb(241,243,246)** on background **rgb(241,243,246)** at both desktop and mobile: contrast **1:1**. The numbers are also pale. '03 Take the next step' remains readable on the darker row. The artifact is original, but the first two stages are visually lost. Source targets: public/identity.css .journey>div and later .journey>div:last-child override. The illustration is aria-hidden, so an automated accessibility scan alone does not establish visual readability. Evidence: growth-illustration-390.jpg and growth-illustration-1440.jpg; selected-service captures; computed colors in targeted-findings.json.

### F04 — P1 / Miniature browser label contrast and scale

Axe flags .browser-bar > span on home and service index at both 390 and 1440: #746A70 on #E0E4EA, **4.07:1**, 6px text, below the normal-text 4.5:1 threshold. Four scan occurrences are one repeated component issue, not four unrelated defects. This is a remaining wine/gray micro-label in an otherwise chrome system. Source target: public/styles.css .browser-bar and public/identity.css illustration overrides. Evidence: browser-audit.json. Text is too small for useful merchandising/showcase detail even if nominal contrast is repaired.

### F05 — P1 / Original portfolio lacks rich visual evidence

Only two CSS-composed concepts exist. No actual product-screen sequence, photography-led composition, large device/storytelling set or case-study visual progression exists. Keep the concepts and honest labels; improve their own artifacts/story only after approval. Do not use Flow Ninja clients, logos, photos, awards or numbers to fill the gap. This is an assessed quality gap against the user's premium immersive target, not a numerical likeness claim.

### F06 — P2 / Repetition and material hierarchy

The hero, service detail pages, About and closing sections repeatedly use large two-part headings, restrained dark fills and similar geometry. Gloss is concentrated in CTAs and headline emphasis. Long repeated process/FAQ blocks make detail pages tall without matching richness in project imagery. Current home is 5,977px tall at 1440 and 6,559px at 390 in these captures. Reassess content/visual rhythm after real reference capture; do not delete valid sections or add arbitrary 3D effects now.

### F07 — P2 / Token documentation drift

public/identity.css declares surface-raised twice: #1C2027 and then a color-mix based on the dark surface/chrome-muted. The latter wins; the design document lists #1C2027. This is a maintenance inconsistency, not evidence that the whole theme is wrong. Compatibility red/wine variable names and historical CSS values need a documented cascade audit, not a blanket string replacement.

### F08 — P2 / Bounded functional verification, not reference-motion equivalence

All 15 new interaction checks pass, with fine-pointer behavior additionally observed. The baseline is functional. It is not verified to share Flow Ninja's spatial layouts, easing, hero imagery or case-study transitions. Physical iPhone Safari, Firefox, assistive technology and composited/translucent contrast remain untested. Do not label this audit an accessibility certification or a cross-browser pass.

### Legacy contamination check

No old problem-card homepage, outdated-storefront comparison, Riverton, Willow & Stone, footwear cart or former package modules were found in rendered main-page text or current route data. The offered 'custom business & e-commerce websites' service deliverable is relevant agency copy, not an imported store feature. Historical docs, compatibility token names and the separate UI Lab exist in history; they do not change the approved baseline. No old feature was reinstated.

## 5. Evidence-backed scorecard

### Direct fidelity to Flow Ninja / approved screenshots

Scale intended: 0 = verified absent/incompatible; 5 = strong measured alignment. **N/E = not evaluable; it is not zero and is not a pass.**

| Dimension | Fidelity score | Reason and available evidence |
| --- | --- | --- |
| Structure | N/E / 5 | Historical text supports broad funnel mapping; no current/approved full reference capture verifies actual order, density or navigation. JOVEX 13-route inventory is verified |
| Visuals | N/E / 5 | JOVEX dark/chrome colors and actual screenshots verified; source reference pixels, geometry, type and version missing |
| Imagery | N/E / 5 | JOVEX uses original CSS/SVG and no photo/video nodes; reference crops/assets unavailable. Premium imagery gap is identified without pretending to compare unseen assets |
| Responsiveness | N/E / 5 | JOVEX tested at six widths, three route/width failures; reference mobile layouts and physical Safari absent |
| Interactions | N/E / 5 | JOVEX actions/motion observed, all 15 checks pass; actual reference menu/scroll/transition behavior unavailable |

**No aggregate fidelity percentage is defensible.** A low or high numeric score here would invent certainty. Replace N/E only after both reference versions have labeled evidence.

### Separate JOVEX implementation checks (not fidelity scores)

- Route/width checks: **75/78 pass**; all 78 return HTTP 200 and have one h1; the three failures are viewport bounds.
- Interaction scenarios: **15/15 pass**, plus a recorded real fine-pointer hover; browser reduced-motion and no-JavaScript fallbacks checked.
- Automated accessibility: **8 scans**, four color-contrast occurrences of the same component; not a clean accessibility result. Growth art defect is separately visually verified.
- Runtime errors and external requests: **0 observed** in the bounded local run.
- `npm run lint`: passed (Node syntax checks, not ESLint/TypeScript).
- `npm test`: four source-test groups passed.
- Existing local server built all 13 routes from unmodified source. No new application code, live service, integration or production deployment was introduced.

Machine results: evidence/browser-audit.json and evidence/targeted-findings.json. Fresh full-page capture scrolls through the actual document to reveal portfolio content before returning to the top; it does not edit the site or inject replacement visuals.

## 6. Prioritized implementation plan — proposals only

| Priority / sequence | Proposed work after separate implementation authorization | Exact scope / preserve | Acceptance evidence |
| --- | --- | --- | --- |
| P0 / evidence gate | Restore permitted reference access and obtain original approved screenshot files | Keep today's Flow Ninja and earlier approved version in separately dated folders; capture home, nav closed/open, service detail, work, case detail and conversion at 1440, 768, 390, 375; document URLs, viewport, scroll/state and motion preference. Do not silently select a newer design | Dated screenshots and interaction recordings for both versions; exact approved-version selection documented |
| P0 / baseline lock | Pin 131d184 as compatible starting point | Preserve 13 routes, offerings, concept identities, keyboard interactions, unsent inquiry and existing history; verify source branch authority with owner if newer unseen approvals surface | Before/after route map, source hashes, no imports from old storefront or lab |
| P1 / reliability | Fix the confirmed deliverable-grid sizing and both illustration contrast defects | public/styles.css grid/browser label; public/identity.css journey/illustration foregrounds. Prefer minmax(0,1fr), suitable wrapping or a deliberate one-column mobile rule after review; no production code changed now | All 13 routes at 320/375/390/430/768/1440: scrollWidth <= clientWidth <= configured width; 4.5:1 labels; readable Discover/Understand in actual selected-tab screenshots |
| P1 / premium art direction | Define one original JOVEX opening composition and coherent project-art system | Keep JOVEX brand and copy; use owned/licensed imagery or original high-quality concept artifacts. Preserve dark role hierarchy and readable chrome accents. Do not copy Flow Ninja visuals or automatically integrate a UI Lab effect | One approved hero and one approved project preview at desktop/mobile; provenance, crop plan and fixed dimensions; no unearned client claims |
| P1 / concept evidence | Expand Fieldwork/Orbit visual narratives using their own artifacts | Original question/approach/scope stay; add only genuine concept screens, responsive views, decisions and honest sample behavior. No fabricated outcomes, real client attribution or unrelated storefront | Distinct project-specific sequence and legible device/interface views, clearly labeled concept, keyboard/contact/next-project flow retained |
| P2 / typography and rhythm | Establish a deliberate JOVEX type/spacing/media hierarchy against the verified reference version | Audit font availability/rights if a new font is proposed; use system fallback. Tune line length, small labels, vertical section rhythm, content density and material contrast. No indiscriminate black/silver fill or copied brand typography | Side-by-side evidence for approved reference role mapping; 200% zoom, narrow wrapping, actual measured section hierarchy |
| P2 / interaction direction | Map observed reference purposes into original restrained JOVEX motion | Keep functional tabs, filters and focus; choose only justified transitions after reference observation and owner approval. Preserve 180/280/550ms baseline until approved; no autoplay audio, scroll hijacking or paid libraries | State-by-state comparison, finite motion, reduced-motion equivalence, touch/fine-pointer/keyboard evidence; no new lab feature inferred as approved |
| P2 / cascade | Align semantic tokens/documentation and remove conflicting presentation rules only in a later scoped change | Resolve surface-raised definition and document aliases; preserve separate concept artwork roles; no blanket replacement of historical strings | Computed-color inventory matches design tokens and screenshots on each route |
| P3 / release readiness | Repeat browser/visual/accessibility testing and separate production/content approval | Physical iPhone Safari, Firefox, keyboard and screen reader; verify real operator/contact details independently. Backend delivery/CRM/analytics remain out of scope | Passing verified routes, contrast, touch, inquiry disclosure, image budgets, static route hosting. No production deployment authorized by this plan |

The first two plan rows are prerequisites for a defensible reference-led visual change, not a request to recreate an unseen reference. Missing social proof/awards/metrics and a URL-audit tool are not automatic implementation tickets. Either provide genuine evidence/capability or retain truthful alternatives.

## 7. Deliverables, publication safety and limits

- Audit branch: review/jovex-flow-fidelity-audit-20261027, from the pinned Obsidian implementation. Only this audit's report, evidence and screenshot materials are committed there. Existing design/source/test files are unchanged.
- Public preview path: previews/jovex-flow-audit-20261027/ in jovex-visual-preview. Allowlisted original-site screenshots, audit prose, safe results and static review HTML only. No private application modules, stylesheets, JavaScript runtime, built application routes, source archive, credentials or user data are copied. Public review HTML is a static document, not a deployment of the agency website.
- Screenshot inquiry sample uses Audit Example and audit@example.invalid; no real customer data and no submission.
- Prior eight-experiment gallery at the public repository root is preserved.
- Public HTTPS accessibility is not inferred from a Git push. Pages/API access must be independently checked; any proxy block is reported separately.
- **Remaining deliverable gap:** actual Flow Ninja-versus-JOVEX side-by-side reference screenshots and direct fidelity scores cannot be completed without the missing/live reference evidence. Current-vs-historical JOVEX pairs do not close that gap.
