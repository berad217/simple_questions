# Development Log: High-Uncertainty Cognitive Style Communication Framework

## Purpose
This log tracks session-by-session development, key decisions, conceptual continuity, and open questions. It serves as the ephemeral context that lives between writing sessions.

---

## Session 0: Workflow Foundation Setup
**Date**: 2026-01-21
**Session Type**: Infrastructure setup
**Agent**: Claude Code (VS Code Extension)

### What Was Done
1. Created comprehensive SPEC.md with:
   - Complete section outline (35+ sections across 5 parts)
   - Success criteria for each section (what reader should be able to DO)
   - Dependency map (which sections need others before writing)
   - Recommended writing order (5 phases, spiral development approach)
   - Document-wide consistency requirements

2. Renamed preamble.md → onboarding.md and enhanced with:
   - Session-specific instructions (writing, revising, continuity checking, handover)
   - Key project files reference
   - Clear workflow for each session type

3. Initialized this DEVLOG.md

4. Next: Create voice-samples.md and examples-bank.md

### Key Decisions Made

**Document Structure**:
- Chose to make SPEC.md extremely detailed with success criteria and dependencies rather than just an outline
- Decision rationale: Non-coding project spanning many sessions needs strong structural support to prevent drift

**Writing Order - Spiral Development**:
- Phase 1: Sections 1, 2, 4.1 (foundational concepts + core techniques)
- Phase 2: Sections 5.1, 6.2, 11 (immediate practical utility)
- Phase 3: Section 3.1-3.4 (theory grounded in concrete examples)
- Phase 4: Sections 7-8 (relationship-specific applications)
- Phase 5: Polish and remaining sections

**Decision rationale**:
- Establish voice/tone early (Phase 1)
- Make immediately useful before going theoretical (Phase 2 before 3)
- Theory can reference concrete examples from Phase 2
- Relationship applications benefit from full framework being established

**Session-Based Workflow**:
- Each session: Orient (read DEVLOG/SPEC) → Write → Document (update DEVLOG/SPEC)
- Handover protocol: DEVLOG captures ephemeral context between sessions
- Voice-samples.md prevents tone drift across multiple sessions/agents

### Conceptual Foundations Established

**Core insights from genesis_document.md** (must permeate final work):
- "Amputates uncertainty" - why forced collapse feels dishonest
- "Structured collapse not simpler thinking" - solution approach
- "Reduce dimensionality" - what techniques actually do
- "Lossy compression is not lying" - reframe communication
- "Communicable stability not perfect truth" - goal of framework

**Three-layer communication model**:
1. Literal information (explicit content)
2. Relationship signal (trust, priority, care)
3. Common knowledge (what both know they both know)

High-uncertainty individuals over-optimize for layer 1, under-weight layers 2-3.

**The dimensionality problem**:
Questions automatically expand across causal, emotional, moral, strategic, reputational dimensions simultaneously. Techniques work by **specifying which dimensions to evaluate**, not eliminating dimensional thinking.

### Tone/Voice Standards Set

From onboarding.md:
- Direct and precise (no corporate-speak)
- Intellectually honest (acknowledge complexity)
- Practically grounded (show what to do, then why)
- Examples-rich (minimum 3 per technique, before/after format)

**GOOD example standard**:
> Domain-binding: Restrict which layer of reality is being queried.
> Instead of: "Why didn't you call?"
> Use: "Logistically only—what stopped you from calling yesterday?"

Concrete, shows before/after, immediately usable, explains mechanism.

### Open Questions / Decisions Needed

1. **Document compilation approach**:
   - Option A: Write sections as standalone files (section-01.md, section-02.md, etc.), compile later
   - Option B: Write directly into single growing document
   - Option C: Hybrid (standalone for active development, merge when section complete)

   **Recommendation**: Defer until Phase 1 section 1 is written - see which feels more natural

2. **Example format standardization**:
   - Should all before/after examples follow identical formatting?
   - How to handle context-setting (professional vs intimate scenarios)?

   **Recommendation**: Let first few sections establish natural format, then codify in voice-samples.md

3. **Cross-reference notation**:
   - How to reference other sections (by number, by name, both)?
   - Inline references vs footnotes vs "See Section X"?

   **Recommendation**: Establish during Phase 1 when first cross-references appear

4. **Theoretical frameworks depth**:
   - Section 3.1-3.4 are "Placeholder" status
   - How deep to go on neurodevelopmental, information theory, game theory, linguistics?
   - Balance: accessible to non-experts but satisfying to physician/engineer audience

   **Recommendation**: Write Phase 2 practical sections first; this will reveal what theoretical depth is needed

### Next Session Recommendations

**Immediate next steps**:
1. Complete infrastructure: create voice-samples.md and examples-bank.md
2. Begin Phase 1 writing with Section 1 (Core Cognitive Profile)

**Section 1 writing approach**:
- Pull heavily from genesis_document.md "Brief Description" section
- Expand strengths/difficulties lists with concrete examples
- Add phenomenological description (what it FEELS like to experience this)
- Establish non-pathologizing frame that pervades entire document
- Generate 3-5 daily life examples showing when this style creates friction

**Success criteria for Section 1**:
- Reader can recognize pattern in themselves or others
- Can distinguish from anxiety/indecisiveness/evasion
- Understands strengths and friction points
- Feels understood, not pathologized

### Continuity Notes

**Watch for these across sections**:
- Consistent use of key phrases (amputates uncertainty, structured collapse, reduce dimensionality)
- "Why didn't you call?" example appears in multiple places - track canonical version
- Non-pathologizing frame must be maintained throughout
- Balance questioner/responder perspectives in every practical section

### Current Status

**Completed**:
- Infrastructure (SPEC.md, onboarding.md, DEVLOG.md)
- Writing order planned
- Core concepts identified

**In progress**:
- Infrastructure completion (voice-samples.md, examples-bank.md)

**Next up**:
- Phase 1, Section 1: Core Cognitive Profile

**Overall progress**: Foundation complete, ready to begin content development

---

## Session 1: GitHub Setup & Workflow Generalization
**Date**: 2026-01-21
**Session Type**: Infrastructure enhancement
**Agent**: Claude Code (VS Code Extension)

### What Was Done
1. Prepared project for GitHub:
   - Created `.gitignore` (excludes .history/, editor files, drafts)
   - Created `README.md` with project overview and core techniques preview
   - Initialized git repository
   - Created initial commit with all foundation files

2. Expanded `workflow-wisdom.md` into comprehensive standalone resource:
   - Generalized from writing project to all non-coding AI projects
   - Added adaptations for 5 project types (academic research, courses, documentation, policy, books)
   - Added "When to Use" guidelines and Minimal Viable Workflow
   - Added cross-tool compatibility notes
   - Added common challenges & solutions
   - Added git integration strategies
   - Added evolution path (how to scale workflow with project complexity)
   - Added quick start guide

### Key Decisions Made

**Decision**: Make workflow-wisdom.md project-agnostic
- **Rationale**: This workflow pattern is valuable beyond this specific project. Generalizing it creates reusable resource for future non-coding work.
- **Impact**: workflow-wisdom.md can now be used as template/guide for other projects (research papers, course development, documentation, etc.)

**Decision**: Document minimal viable workflow (3 files vs 5)
- **Rationale**: Full 5-document foundation might intimidate small projects. Provide scaling path.
- **Impact**: Users can start simple (outline + log + style guide) and scale up as needed

**Decision**: Include cross-tool compatibility section
- **Rationale**: Workflow should work in Claude Code, Desktop, web, ChatGPT, Cursor, etc.
- **Impact**: Markdown-based approach makes this tool-agnostic

### Conceptual Continuity Notes

**workflow-wisdom.md structure mirrors onboarding.md philosophy**:
- Immediately practical (Quick Start Guide)
- Theoretically grounded (why the 5-document foundation works)
- Honest about limitations (when NOT to use this workflow)
- Accumulates wisdom (will update with real lessons from this project)

**Key addition**: Project type adaptations show how same foundation applies to:
- Academic research (hypotheses, methodology, argument dependencies)
- Course curricula (learning objectives, skill dependencies)
- Technical docs (user journeys, API coverage)
- Policy frameworks (stakeholder needs, implementation guidelines)
- Books (argument flow, reader journey)

### Tone/Voice Observations

workflow-wisdom.md successfully maintains the project's voice:
- Direct and precise
- Intellectually honest about trade-offs
- Practically grounded (30 min setup vs 5-10 hours fixing inconsistencies)
- Examples-rich (shows template patterns, not just abstract advice)

Strong passage added to workflow:
> "Rule of thumb: If you'll come back to this in a week and need to remember context, use the workflow."

Simple, actionable heuristic for when to use vs skip.

### Open Questions / Blockers

**Q: Should workflow-wisdom.md become its own standalone repo?**
- Pro: Makes it reusable across projects, easier to find/share
- Pro: Can accept contributions from other non-coding projects
- Con: Adds maintenance overhead
- Con: This project serves as living example/case study

**Current stance**: Keep in this repo for now. As it proves valuable and gets contributions, could split into standalone repo later.

**Q: How to handle workflow updates discovered during content development?**
- Add lessons to workflow-wisdom.md "Lessons Learned" section
- Add anti-patterns to "Anti-Patterns Observed" section
- Update "Real-World Case Study" with actual metrics

**Plan**: After Phase 1-2 complete, update workflow-wisdom.md with real productivity numbers and challenges encountered.

### Next Session Recommendations

**Option A: Begin content development**
- Start Phase 1, Section 1 (Core Cognitive Profile)
- This will test the workflow in practice
- Discoveries will inform workflow-wisdom.md updates

**Option B: Create project-specific `.claude/CLAUDE.md`**
- Override global workflow with project-specific instructions
- Point future agents to this non-coding workflow

**Recommendation**: Option A. The workflow is ready. Time to use it and see how it performs in practice.

### Current Status

**Completed**:
- Full infrastructure (5-document foundation)
- GitHub setup (git initialized, README.md, committed)
- Workflow generalization (workflow-wisdom.md expanded)

**Ready to begin**:
- Phase 1, Section 1: Core Cognitive Profile
- Real content development

**Next up**:
- First actual writing session using the workflow
- Test the "Session Type: Writing New Section" protocol
- Discover if SPEC.md success criteria are specific enough
- See if voice-samples.md prevents tone drift

**Overall progress**: Foundation complete, workflow documented and generalized, ready for content development

---

## Template for Future Session Entries

```
## Session [N]: [Brief Description]
**Date**: YYYY-MM-DD
**Session Type**: [Writing/Revising/Continuity/Handover]
**Agent**: [Claude Code/Desktop/Web/Other]

### What Was Done
- Bullet list of sections written/revised
- Files created/modified

### Key Decisions Made
- Decision: [what was decided]
- Rationale: [why]
- Impact: [what this affects]

### Conceptual Continuity Notes
- New concepts introduced that need to appear elsewhere
- Cross-references established
- Examples added to examples-bank.md

### Tone/Voice Observations
- Strong passages added to voice-samples.md
- Tone drift noticed/corrected
- Formatting patterns established

### Open Questions / Blockers
- What needs clarification
- What needs research/thought
- What's blocking progress

### Next Session Recommendations
- Suggested next section(s)
- Specific focus areas
- Preparation needed

### Current Status
**Completed**:
**In progress**:
**Next up**:
```

---
