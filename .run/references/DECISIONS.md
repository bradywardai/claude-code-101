# Architectural Decisions

Append-only log of key decisions and their rationale.

### Classified as J (Planning, J3-RFC)
- **Date:** 2026-06-06
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** Plan-only phase to decide new-repo-vs-rearchitect + target architecture + content rewrites for the CC-for-Business lab rebuild; grounded in repo review + ecosystem research + approved milestone blueprint. Distribution: unblocks cash-path P1.

### Lab rebuild — approach locked
- **Date:** 2026-06-06
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** NEW repo claude-code-for-business, harvest curriculum, old repo frozen as A/B arm. Duolingo-style gamification (XP/streak/celebration, no characters/avatars). Auth via Claude Pro/Max OAuth. Distribution: non-dev business owners find it via warm outreach + live workshop.

### Build strategy: NEW repo over in-place
- **Date:** 2026-06-06
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** New claude-code-for-business repo. Clean buyer clone, less rework than de-RPG'ing 194 files, old repo doubles as RPG A/B arm. Research-backed (architecture audit + RPG-efficacy).

### Gamification: Duolingo-style, cut characters/avatars
- **Date:** 2026-06-06
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** Keep XP/streaks/clean completion celebration/badges; cut classes/avatars/skill-trees/aura-shop/over-the-top. Evidence: credibility risk + competence-null concentrated in the character/meme layer, not XP/celebration. Brady's call.

### Auth: Claude Pro/Max OAuth, not API key
- **Date:** 2026-06-06
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** Lowest non-dev friction, no billing setup, matches free competitor. Old lab's API-key lesson is outdated.

### Audience + pricing flagged to milestone
- **Date:** 2026-06-06
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** Audience research recommends lead-narrow-vertical + widen-broad-later; generic business-owner is crowded cheap, broad+premium collides w/ free+Maven. Positioning + pricing each get their own milestone-level phase. Lab v1 = general + vertical-ready.

### Lab effort decomposed into phases
- **Date:** 2026-06-07
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** Curriculum Design (A) → Build (B) → Learning Intelligence (C) → ongoing currency; +milestone follow-ups (positioning, pricing). Open questions baked into named phases, not resolved in this RFC (Brady's directive).

### Curriculum = shared backbone for 3 surfaces
- **Date:** 2026-06-07
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** One curriculum design drives lab lessons + Brightly Academy video shot-list + Skool free funnel. Matches blueprint two-layer model.

### Naming deferred
- **Date:** 2026-06-07
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** Repo name decided in Phase B (avoid claude-code-for-business — namesake collision + trademark); public brand decided in positioning phase (likely Brightly-branded, not 'Claude Code for Business').

### Brady approved skip: ship/deploy/measure for J plan-only phase
- **Date:** 2026-06-07
- **Phase:** cc-for-business-lab-rebuild-plan
- **Rationale:** Brady explicitly approved closing the lab-planning phase at the checkpoint ('Close lab-plan → do positioning/strategy next', 2026-06-06). J bucket = plan-only; PLAN.md is the deliverable; no code/PR/deploy/measure applies.

### Classified as J (Planning, J3-RFC) — positioning/strategy
- **Date:** 2026-06-07
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** Strategic positioning phase: audience narrow-vs-broad, validation-engine moat (incl. standalone-product option, folded in per CTO call), capstone breadth, differentiation vs commoditized mechanic. Gates pricing + curriculum. Distribution: gates the whole go-to-market.

### Positioning — approach locked
- **Date:** 2026-06-08
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** Sell narrow (ship an automation for the business you run, 1 week, live), deliver flexible (capstone flexes broader via guided-project). Differentiation = transformation + 4-way bundle, never 'learn Claude Code'. General biz owners v1.

### Wedge: sell narrow / deliver flexible
- **Date:** 2026-06-08
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** Chose narrow sales promise over broad D11 pitch. Narrow converts + defends premium + beats free 'build an app' competitor; D11 aspiration preserved in delivery via guided-project scoping.

### Audience: general business owners for v1
- **Date:** 2026-06-08
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** Chose general over committing a beachhead vertical. Admin-heavy service businesses are the natural lean; sharpen later if referral compounding needs it.

### Brand collision → naming task
- **Date:** 2026-06-08
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** The $997-vs-$30 'Claude Code for Business' search/price collision is the real threat. Flagged must-resolve; direction (likely distinct Brightly brand) decided in a dedicated naming task.

### Capstone = 3-5 automation archetypes
- **Date:** 2026-06-08
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** Template family (email triage/calendar/CRM onboarding/data extraction/scheduled report) de-risks the 1-week-ship guarantee + concretizes validator output. Flexes broader per wedge.

### Validator = moat now, product later
- **Date:** 2026-06-08
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** Claude-Code-fit scoring + build-plan routing as the course's core differentiator for launch; standalone SKU + lead magnet evaluated post-first-sale. Don't split focus pre-cash.

### Brady approved skip: ship/deploy/measure for positioning J phase
- **Date:** 2026-06-08
- **Phase:** positioning-strategy-cc-for-business
- **Rationale:** Brady explicitly approved closing at the plan approval gate ('Approved — lock + close', 2026-06-07). J bucket = plan-only; positioning brief is the deliverable.

### Classified as J (Planning, J1-Spec)
- **Date:** 2026-06-08
- **Phase:** claudecode101-4
- **Rationale:** Design-only phase producing a curriculum spec doc; no code (roadmap pre-tagged C but C is the next item, claudecode101-5 Build the lab). Signals: design/spec/architecture/content-map, no new runtime behavior. Distribution: gates the whole lab + Academy content for the $997-1497 offer.

### Curriculum design — approach locked
- **Date:** 2026-06-08
- **Phase:** claudecode101-4
- **Rationale:** Full curriculum spec (8+-module spine, 31-topic placement, archetype-routed capstone, 2-layer teaching arch). Distribution: non-dev owner finds it via Academy video content-map; success = capstone_shipped.

### Auth path = Claude Pro/Max subscription
- **Date:** 2026-06-08
- **Phase:** claudecode101-4
- **Rationale:** Chose subscription login over API-key paste. Deletes M2.L1; fewer first-session support tickets; acceptable sub assumption for a paid-course audience.

### Capstone archetypes trimmed to 3
- **Date:** 2026-06-08
- **Phase:** claudecode101-4
- **Rationale:** Chose 3 (email triage/Gmail, calendar follow-up/Calendar, scheduled report/scheduler) over the 5 in research. Lighter to author + maintain; spine teaches the student's one.

### Spine cap = allow >8 where justified
- **Date:** 2026-06-08
- **Phase:** claudecode101-4
- **Rationale:** Brady overrode the hard 8-module cap from research. Default lean, but a topic that genuinely needs its own module may add one. Still resist breadth-as-filler.

### Capstone = archetype-routed, not open-ended
- **Date:** 2026-06-08
- **Phase:** claudecode101-4
- **Rationale:** M0 validation routes to 1 of 3 archetype paths; M13 = 4-lesson guided path. Kills the CC-for-Everyone open-ended-app scope-creep trap the positioning rejects.

### Brady approved curriculum spec — lock + close
- **Date:** 2026-06-08
- **Phase:** claudecode101-4
- **Rationale:** J plan-only phase. CURRICULUM-SPEC.md is the deliverable; PLAN.md hands 7 build tasks to claudecode101-5. Approved 'lock + close' 2026-06-08.
- 2026-06-08 — Bound milestone `cc-for-business` to persistent workspace `/Users/bradyward/Developer/projects/claude-code-101/.worktrees/build-the-lab-implement-curriculum-spec.md-new-cla` (F2 milestone-worktree). [start-phase]

### Classified as C (New Feature)
- **Date:** 2026-06-08
- **Phase:** build-the-lab
- **Rationale:** New product surface — entire terminal lab repo. C1 subtype (new surface). Distribution: direct revenue tie to $997-1497 offer. Linked to cc-for-business milestone. needs_frame=true (C+ bucket).

### Architecture: NEW repo (reaffirmed)
- **Date:** 2026-06-08
- **Phase:** build-the-lab
- **Rationale:** Locked in cc-for-business-lab-rebuild-plan phase (2026-06-06). Research-backed: RPG can't be flag-gated (138 lines in teaching loop), clean buyer-facing clone, old repo doubles as RPG A/B arm. Explore agent contradicted this due to worktree archive symlink gap (phases/archive not shared) — bug filed separately.

### MCP setup: honest GCP walkthrough
- **Date:** 2026-06-08
- **Phase:** build-the-lab
- **Rationale:** Chose honest step-by-step GCP Console walkthrough over pre-configured OAuth app or Composio abstraction. No dependencies on us maintaining anything. Adds ~20 min to S6 but teaches real process.

### Capstone done bar: ran once on real data
- **Date:** 2026-06-08
- **Phase:** build-the-lab
- **Rationale:** Chose 'ran once on real data' over 'actually scheduled' or 'saved as reusable prompt'. Scheduling adds real complexity for non-devs. Realistic for week 1 delivery.

### Build paused — curriculum spec revision needed
- **Date:** 2026-06-08
- **Phase:** build-the-lab
- **Rationale:** CURRICULUM-SPEC.md missing the setup/configuration layer (CLAUDE.md setup, USER.md, hooks, skills, file org, security). Brady identified that the real product is walking zero-background users through the FULL Claude Code setup experience, not just terminal + prompting + MCP. J-bucket revision phase before build.

### Classified as J (Planning, J1-Spec) — curriculum revision
- **Date:** 2026-06-08
- **Phase:** curriculum-spec-revision

### Curriculum spine: 8 → 13 modules
- **Date:** 2026-06-09
- **Phase:** curriculum-spec-revision
- **Rationale:** Added 5 modules: S4 Configure Claude (CLAUDE.md/init/USER.md/memory), S5 Power Setup (security/auto-mode/file-org/PRD), S6 Context Mgmt (continue/compact/naming), S9 Git Basics (promoted from drip), S11 Routines (scheduled automation). Brady identified the setup layer as the product differentiator — nobody else teaches Claude Code configuration.

### Brady approved skip: design→measure for J plan-only phase
- **Date:** 2026-06-09
- **Phase:** curriculum-spec-revision
- **Rationale:** Brady explicitly approved closing the curriculum spec revision phase ('Approved -- lock it', 2026-06-08). J bucket = plan-only; CURRICULUM-SPEC-v2.md is the deliverable; no code/PR/deploy/measure applies.

### Ambition: 1x + 2 cherry-picks from 10x
- **Date:** 2026-06-09
- **Phase:** build-the-lab
- **Rationale:** Shipped 1x (11 tasks) + archetype-gated examples + /stuck coaching bridge from 10x. Total 13 tasks. Deferred: zero-to-output sprint, proof artifacts, ROI calculator (V2). 100x/unbeatable ideas (certification, gallery, alumni, cohorts, guarantee) backlogged to milestone roadmap.

### Ship new repo on its own (Brady-delegated)
- **Date:** 2026-06-09
- **Phase:** build-the-lab
- **Rationale:** Brady asked 'your call, best option' on the cross-repo gate; chose to ship claude-code-for-business as its own private GitHub repo and skip the in-worktree review→measure steps (they can't run against an empty worktree diff).

### Classified as J (Planning) / work-type=plan
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Pricing is a strategy decision not a code build; deliverable is a pricing PLAN.md. Distribution filter passes full — pricing gates the entire $997-1497 offer + sales page + checkout. Linked to cc-for-business milestone.

### CC-for-Business pricing — approach locked
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Cohort 1 at $997 founding rate, $1,497 anchored for cohort 2+, pay-in-full, 60-day guarantee. Distribution: non-tech SMB warm list finds it via direct outreach + one live workshop.

### Price point: $997 founding not $1,497
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Chose $997 founding (cohort 1) over $1,497-now and $1,247-middle. WTP at $1k+ is 6/10; $997 defended vs $2k workshop/$500-5k consultant benchmarks, $1,497 cohort-1 unproven. Founding-rate telegraphs value escalation.

### Pay-in-full only (no 3-pay plan)
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Brady's call: pay-in-full for cohort 1 over visible payment plan. Trades the +15-30% conversion lift for simplicity; revisit if cohort-1 close rate is weak.

### 60-day guarantee on offer
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Risk-reversal for first-time high-ticket buyer; research-recommended conversion lift.

### Payment terms revised: add 3-pay
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Pre-mortem flagged pay-in-full-only as a blocker (chokes WTP soft spot for cash-flow-sensitive SMB owners). Brady reversed: $997 PIF stays headline, added $375x3=$1,125 plan. Near-zero default risk on warm 60-day-guarantee offer.

### Guarantee made conditional
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Changed unconditional 60-day to conditional: 'attend + ship one automation, or refund'. Filters tire-kickers, raises completion + testimonials.

### Conversion reframed to workshop-fill
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Dropped 1.5-2% list% frame for workshop-room model: 8-12% list->attend, 15% room close floor/25% target. Locates risk on fill, not price.

### Value stack re-stacked to 3-4x + dated anchor
- **Date:** 2026-06-17
- **Phase:** pricing-set-wtp-price-for-the-cc-for-business-offe
- **Rationale:** Stack $3-4k stated -> $997 (was thin 1.2x $1,196). $1,497 cohort-2 made a public dated commitment so founding scarcity is real.
