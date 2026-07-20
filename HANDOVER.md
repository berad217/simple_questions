# Handover: Sections 1-13 + Appendices A & C Done (Cross-Vendor Reviewed)

## 1. Orientation
New AI: Start with `workflow/onboarding.md`, then this file. Sections 1-13 and Appendices A & C are written, cross-vendor reviewed, and verified. What remains is optional back-matter only.

## 2. The Delta
- Session 25 editorial pass (Sections 1-12) committed (`5d98b31`). Section 13 committed (`564d82f`). Appendix A committed (`2df7859`).
- **Appendix C: Glossary** written (`content/appendix-c-glossary.md`, ~1,800 words, ~40 alphabetical terms with cross-links + section pointers).
- **Cross-vendor review**: drove the Codex CLI headlessly with **gpt-5.6-sol** (read-only, high reasoning) over Section 13 + Appendices A & C. High-signal — caught real defects. Applied the well-founded ones:
  - **Section 13 was rewritten.** Most important fix: the law subsection previously conflated *advocate* with *witness* and effectively advised collapsing qualified testimony to "Yes" (misleading; contradicted Section 8). Now splits advocate/witness/expert/analyst registers. Also: Hall reframed as a contested heuristic (not a national taxonomy); gender section un-fused into behavior vs. audience-bias vs. backlash; medicine de-romanticized; engineering examples fixed (margin vs. measured-max vs. probabilistic bound; "worst case" no longer misused); 13.4 scoped to *asynchronous text*; added an honest "A Note on Evidence" limits section.
  - **Appendix A**: "a pause is processing" softened to a hypothesis; flowchart rebuilt in **true ASCII** (was Unicode box-drawing) with a new "genuinely don't know" branch; trap→"trauma not style" corrected to coexistence.
  - **Glossary**: fixed the "lossy compression" one-way logic; "not anxiety" → "may coexist with"; added missing **diagnostic intent** entry.
  - Declined: changing a Card 2 script that quotes Section 6.1 verbatim (would cause drift); pasting the reviewer's unverified citations (deferred to Section 14).
- `build.py` `SECTION_ORDER` includes section-13, appendix-a, appendix-c (**hardcoded — new content files must be added or the build silently skips them**). SPEC marks all three Complete.
- Build regenerated: markdown + ZIP OK (20 sections, ~53,852 words). HTML/PDF fail **only** on the missing `pandoc` — not a regression. `git diff --check` clean; no Unicode box chars remain in Appendix A.
- The Appendix C work + the review revisions (Section 13 rewrite, Appendix A/glossary edits, build.py, SPEC, DEVLOG, HANDOVER, build/ artifacts) are **not yet committed** — commit next.

## 3. State of Remaining Work (from SPEC audit)
Sections 1-13 + Appendices A & C are content-complete and reviewed. Still unwritten, both optional:
- **Appendix B**: Customization Templates — Needs creation. Fillable protocol builder, style assessment, intent-declaration templates.
- **Section 14**: Research Connections & Further Reading — Placeholder. Section 13's "A Note on Evidence" now explicitly points here for sourced citations; **watch for reference fabrication** — verify anything cited.

## 4. Next Steps
1. Commit the current tree: `git add -A && git commit` (Session 26 cont. — Appendix C + review revisions).
2. Then choose: (a) Appendix B (fillable templates) — low-risk distillation; (b) Section 14 — needs real, verified research; (c) declare content-complete and explicitly defer the rest in SPEC.
3. **Repeatable win**: the headless GPT-5.6 review (`codex exec --ignore-user-config -s read-only -m gpt-5.6-sol -c 'model_reasoning_effort="high"' -o REVIEW.md "<prompt>" < /dev/null`) is worth re-running on any future empirically-loaded section (esp. Section 14). Treat findings as advisory — verify against our own sections before applying.
4. Housekeeping still not done: `workflow/onboarding.md` Step 1 status line says "~19,600 words, Section 5 complete" — stale since Session 6; its file-structure diagram also omits most sections and all appendices. Worth a cleanup.
5. After any edit batch: `python build.py` (expect the `pandoc` failure), then `git diff --check`.
