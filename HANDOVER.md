# Handover: Session 3 → Session 4

**From**: Claude Code (VS Code Extension) - Opus 4.5, Session 3
**Date**: 2026-01-21
**To**: Next AI session (any tool)

---

## Current Project State

**Phase**: Phase 1 in progress (foundational content)
**Next Task**: Write Section 4.1 (Core Techniques)
**Status**: Sections 1 and 2 complete, voice/tone established, "structured collapse" concept introduced, ready for practical techniques

---

## What Was Accomplished (Session 3)

### Section 2: The Communication Mismatch - COMPLETE
- Created `content/section-02-communication-mismatch.md` (~1,800 words)
- Explained WHY "simple" questions aren't simple (the structural mismatch)
- Fully introduced "structured collapse" as the solution framework
- Addressed "lossy compression is not lying" concept
- Used new canonical example: "Are you free Saturday?" multi-dimensional expansion

### Key Decisions Made This Session
1. **New primary example**: "Are you free Saturday?" shows mismatch in lower-stakes context
2. **Focus on mismatch mechanism**: Section 2 doesn't repeat phenomenology from Section 1—focuses on the gap between questioner expectations and responder experience
3. **"Structured collapse" fully developed**: Now ready for Section 4 to provide specific techniques
4. **Duck-rabbit analogy**: Introduced to explain why "just answer simply" doesn't work

### Files Updated
- `content/section-02-communication-mismatch.md` (NEW - second content section)
- `workflow/SPEC.md` - Section 2 status → Complete
- `workflow/DEVLOG.md` - Session 3 entry added
- `workflow/voice-samples.md` - 3 new voice samples from Section 2
- `workflow/examples-bank.md` - "Are you free Saturday?" example added

---

## What Section 4.1 Needs (Next Session's Task)

**Target**: Section 4.1 (Core Techniques)
**Location in SPEC.md**: Part II, Section 4.1
**Status**: Needs expansion from genesis_document.md
**Dependencies**: Sections 1-2 (reader understands the problem being solved)

**Success Criteria** (from SPEC.md):
- Reader can use all six techniques in next conversation
- Can choose appropriate technique for the situation
- Can recognize when a technique isn't working and adjust

**Content Requirements** (per technique):
- Clear definition
- Mechanism explanation (WHY it reduces cognitive load)
- 3-5 concrete examples across different contexts (professional, intimate, casual)
- When to use this technique vs others
- Common failure modes and corrections

**The Six Core Techniques** (from genesis_document.md):
1. **Domain-binding** - Restrict which layer of reality is being queried
2. **Uncertainty permission** - Explicitly allow provisional/incomplete answers
3. **Forced-slice** - Ask for one factor rather than full explanation set
4. **Counterfactual anchoring** - Ask what difference would change outcome
5. **Output-format constraints** - Define structure before answer is given
6. **Role-locking** - Specify which internal role/perspective should answer

**Template to Use** (from voice-samples.md):
```
**Technique Name**: Brief definition (1 sentence)

**Mechanism**: Why this reduces cognitive load / dimensionality (1-2 sentences)

**Examples**:
- **Professional context**:
  - Instead of: [problematic question]
  - Use: [improved question]

- **Intimate context**:
  - Instead of: [problematic question]
  - Use: [improved question]

- **Casual context**:
  - Instead of: [problematic question]
  - Use: [improved question]

**When to Use**: Specific situations where this technique works best (2-3 sentences)

**Failure Modes**: What goes wrong and how to correct (2-3 common failure modes with fixes)
```

**Approach Recommendation**:
- This is a substantial section (6 techniques × detailed template = ~3,000+ words)
- May need to prioritize depth per technique vs completing all six
- Start with the most intuitive techniques (Domain-binding, Forced-slice) then move to subtler ones
- Use existing canonical examples from examples-bank.md where applicable
- Generate new examples for contexts not yet covered

---

## Session Protocol for Next Writer

**Before you start**:
1. Read this HANDOVER.md (you're doing that now)
2. Read genesis_document.md technique definitions (source material)
3. Read `workflow/SPEC.md` Section 4.1 entry (success criteria, template)
4. Check `workflow/voice-samples.md` (especially technique template)
5. Check `workflow/examples-bank.md` (canonical examples to reference)
6. Skim Sections 1-2 for voice continuity (don't need full re-read)

**During writing**:
- Follow the technique template consistently for all six techniques
- Generate 3-5 examples per technique across professional/intimate/casual contexts
- Explain the MECHANISM (why it works), not just the technique
- Include failure modes (when it doesn't work, what to do instead)
- Maintain voice: direct, precise, non-pathologizing

**After writing**:
- Update `workflow/SPEC.md`: Change Section 4.1 status to "Complete"
- Log to `workflow/DEVLOG.md`: Session 4 entry
- Add any strong passages to `workflow/voice-samples.md`
- Add new canonical examples to `workflow/examples-bank.md`
- Update cross-references if needed (Section 2 links to Section 4)

---

## Conceptual Threads to Maintain

**Key Phrases Already Established** (use exactly):
- "Amputates uncertainty" - the discomfort of forced collapse
- "Structured collapse" - the solution framework (NOT simpler thinking)
- "Reduce dimensionality" - what techniques do
- "Lossy compression is not lying" - when both parties agree on compression level
- "Communicable stability, not perfect truth" - the goal

**Canonical Examples Available** (in examples-bank.md):
- "Why didn't you call?" → Domain-binding (primary)
- "Are you free Saturday?" → Multi-technique (introduced in Section 2)
- Core technique examples from genesis_document.md (see examples-bank.md)

**Three-Layer Communication Model**:
1. Literal information (explicit content)
2. Relationship signal (trust, priority, care)
3. Common knowledge (what both parties know they both know)

Mentioned but not fully explained. Section 3.3 will provide theory.

---

## Tone Calibration

**Voice established in Sections 1-2** (maintain this):
- Direct and precise, no corporate-speak
- Non-pathologizing (structural mismatch, not personal failure)
- Prose paragraphs for conceptual content; bullets only for actual lists
- Before/after examples as primary teaching tool
- Explain mechanism, not just technique

**Strong passages from Section 2** (in voice-samples.md):
- The perception reframe ("perceiving complexity, not adding it")
- Duck-rabbit analogy (why "just answer simply" fails)
- Lossy compression agreement formulation

---

## Project File Structure

```
simple_questions/
├── content/                    # Written sections (the actual document)
│   ├── section-01-core-cognitive-profile.md
│   └── section-02-communication-mismatch.md
│
├── workflow/                   # AI workflow infrastructure
│   ├── SPEC.md                # Section outline, success criteria, dependencies
│   ├── DEVLOG.md              # Session-by-session development log
│   ├── voice-samples.md       # Tone reference library
│   ├── examples-bank.md       # Canonical examples tracker
│   └── onboarding.md          # Agent entry point (philosophy, protocols)
│
├── source/                     # Reference material
│   └── genesis_document.md    # Original conceptual seed (technique source)
│
├── HANDOVER.md                # Current session handover (root for visibility)
├── README.md                  # GitHub project overview
├── workflow-wisdom.md         # Generalized workflow guide (standalone)
└── .gitignore
```

---

## Git Status

**Current branch**: `master`
**Last commit**: Session 2 - Section 1 complete
**Uncommitted changes**: Session 3 work (Section 2 + workflow updates)

**Next commit should be**:
```
Session 3: Write Section 2 (The Communication Mismatch)

- Explains WHY "simple" questions aren't simple
- Fully introduces "structured collapse" as solution framework
- New canonical example: "Are you free Saturday?" expansion
- Duck-rabbit analogy for why "just answer simply" fails

Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>
```

---

## What Success Looks Like (Session 4)

**Minimum viable**:
- Section 4.1 drafted with all six core techniques
- Each technique has: definition, mechanism, 3+ examples, when to use, failure modes
- SPEC.md updated (Section 4.1 status = Complete)
- DEVLOG.md Session 4 entry logged
- Git commit created

**Stretch goals**:
- Phase 1 complete (all three sections polished)
- Begin Phase 2 with Section 5.1 (Response Protocols)
- Strong technique examples added to voice-samples.md

---

## Open Questions from Session 3

**Q1: How much depth per technique?**
Six techniques with full template could be 3,000+ words. May need to balance depth vs completion. All six techniques should be covered; depth per technique can vary based on complexity.

**Q2: Phase 1 completion**
After Section 4.1, Phase 1 is complete (Sections 1, 2, 4.1). Consider whether to polish these three or move to Phase 2 (practical depth).

**Q3: Context window management**
Section 4.1 is substantial. If context runs low mid-section, commit partial progress and handover with notes on which techniques are complete.

---

## Phase 1 Progress

| Section | Status | File |
|---------|--------|------|
| Section 1: Core Cognitive Profile | ✅ Complete | `content/section-01-core-cognitive-profile.md` |
| Section 2: Communication Mismatch | ✅ Complete | `content/section-02-communication-mismatch.md` |
| Section 4.1: Core Techniques | ⏳ Next | `content/section-04-1-core-techniques.md` |

**Phase 1 Goal**: Establish voice, tone, and core concepts + practical techniques foundation

---

**Ready to write Section 4.1. The foundation is solid. Build the technique toolkit.**

**— End of Handover —**
