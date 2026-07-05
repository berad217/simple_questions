# Handover: Editorial Verification Pass

## 1. Orientation
New AI: Start with `workflow/onboarding.md`, then this file. Continue the chapter-by-chapter verification pass.

## 2. The Delta
- Reviewed and lightly revised Sections 1-12 for correctness, coherence, concision, and spec coverage. The current dirty working tree contains those edits plus regenerated `build/simple-questions-framework.md` and `build/simple-questions-framework-sections.zip`.
- Section 7 edits added the missing relationship-specific pieces: meta-problem/trust erosion, legitimate "I don't know yet" criteria, calibration ritual, repair script, and protocol template.
- Section 8 edits removed stray line-number artifacts and expanded professional/social coverage: stakeholder reassurance, performance reviews, collaborative decision-making, court/compliance/audit contexts, organizational trust, structural supports, and explanation cost-benefit.
- Section 9 edits completed the self-advocacy guide and wrote the previously missing Section 9.2 practice exercises; `workflow/SPEC.md` now marks 9.2 complete.
- Section 10 edits completed the interpretation guide for questioners and wrote the previously missing Section 10.2 question-design practice; `workflow/SPEC.md` now marks 10.2 complete.
- Section 11 edits fixed small artifacts/wording issues and added a Pattern Index that makes reusable move-selection patterns explicit across the 10 worked examples.
- Section 12 edits softened one over-absolute framing sentence and removed a stray line-number artifact; Section 12 already covered the required edge-case distinctions.
- Remaining unreviewed content files from the handover queue: none.
- Build caveat: `python build.py` regenerates markdown and ZIP, but HTML/PDF fail because `pandoc` is not installed in this environment. Do not treat that as a content regression.
- Workflow trap from this session: several files use em dashes/UTF-8; `apply_patch` sometimes failed on exact encoded lines. Line-level PowerShell edits were used carefully, then checked with `git diff --check` and diffs.
- Current verification status: latest `python build.py` succeeded for markdown/ZIP and failed only for expected missing `pandoc`; latest `git diff --check` reported no whitespace errors, only CRLF normalization warnings.

## 3. Next Steps
1. Decide whether to stop the verification pass here, commit the current dirty tree, or continue into optional placeholder sections and appendices.
2. If continuing, inspect `workflow/SPEC.md` for remaining placeholder/needs-writing items outside the original Sections 1-12 verification queue.
3. After any edit batch, run `python build.py`, note the expected `pandoc` HTML/PDF failure, and check `git diff --check`.
