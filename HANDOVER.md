# Handover: Sections 1-13 + Appendices A/B/C Done. Only Section 14 Remains.

## 1. Orientation
New AI: Start with `workflow/onboarding.md`, then this file. Sections 1-13 and Appendices A, B, and C are written, cross-vendor reviewed, and verified. The ONLY remaining SPEC item is Section 14 (Research Connections). Everything else is Complete.

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

- **Appendix B: Customization Templates** written (`content/appendix-b-customization-templates.md`) and GPT-5.6-reviewed. Four fillable templates (style assessment, protocol builder, intent-declaration, confidence-format guide). Review caught taxonomy-merging (B2 had overwritten 7.3's "Question type" with 6.2 intents + an invented "conflict" intent; B4 had invented confidence "formats"); both fixed to quote the source taxonomies exactly. Registered in build.py, marked Complete in SPEC.

## 3. State of Remaining Work (from SPEC audit)
Sections 1-13 + Appendices A, B, C are content-complete and cross-vendor reviewed. **Only one SPEC item is unwritten:**
- **Section 14**: Research Connections & Further Reading — Placeholder. Section 13's "A Note on Evidence" explicitly points here for sourced citations. **This needs REAL, VERIFIED citations** — use the browser/WebSearch to confirm each source; do not paste unverified reference strings (standing project caution). The GPT-5.6 reviews already surfaced candidate literatures (Hall's critics, gender-language meta-analyses, medical-uncertainty reviews) but those must be independently verified before citing.

## 4. Next Steps
1. Commit the current tree: `git add -A && git commit` (Session 26 cont. — Appendix B + review revisions).
2. Then: (a) **Section 14** with verified web-sourced citations — the last item, closes the loop Section 13 opened; or (b) declare the book content-complete and explicitly defer Section 14 in SPEC.
3. **Repeatable win**: the headless GPT-5.6 review (`codex exec --ignore-user-config -s read-only -m gpt-5.6-sol -c 'model_reasoning_effort="high"' -o REVIEW.md "<prompt>" < /dev/null`) has earned its keep twice — re-run it on Section 14. Treat findings as advisory; verify against our own sections before applying.
4. Housekeeping still not done: `workflow/onboarding.md` Step 1 status line says "~19,600 words, Section 5 complete" — stale since Session 6; its file-structure diagram also omits most sections and all appendices. Worth a cleanup.
5. After any edit batch: `python build.py` (expect the `pandoc` failure), then `git diff --check`.
