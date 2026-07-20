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

**Handover**: Created HANDOVER.md for Session 2 (next writer gets oriented in 10 minutes)

---

## Session 2: Write Section 1 (Core Cognitive Profile)

**Date**: 2026-01-21
**Session Type**: Writing New Section
**Agent**: Claude Code (VS Code Extension) - Opus 4.5

### What Was Done

1. Read all preparatory files per handover protocol:
   - HANDOVER.md (session entry point)
   - SPEC.md Section 1 requirements
   - genesis_document.md (source material)
   - voice-samples.md (tone calibration)
   - examples-bank.md (canonical examples)
   - DEVLOG.md Sessions 0-1

2. Wrote Section 1: Core Cognitive Profile
   - Created `section-01-core-cognitive-profile.md`
   - Approximately 2,000 words
   - Covers all success criteria from SPEC.md

3. Updated SPEC.md to mark Section 1 complete

### Key Decisions Made

**Decision**: Use "Why didn't you call?" multi-dimensional expansion in Section 1

- **Rationale**: This example best illustrates what the cognitive experience actually IS. Section 2 can reference this and explain why it creates communication mismatch.
- **Impact**: Section 2 should not repeat the full expansion but can reference "as described in Section 1"

**Decision**: Create standalone section file (section-01-core-cognitive-profile.md)

- **Rationale**: Keeps each section independently editable, allows parallel work on different sections
- **Impact**: Will need compilation step later. File naming convention: `section-NN-kebab-case-title.md`

**Decision**: Structure with subsection headers for each major topic

- **Rationale**: Makes section navigable, allows readers to jump to "Common Misinterpretations" or "Strengths" directly
- **Impact**: Establishes formatting pattern for other sections to follow

**Decision**: Include cross-reference to Section 2 at end

- **Rationale**: Provides navigation, signals continuation
- **Impact**: Will need to maintain these cross-refs as section files are created

### Content Structure Used

1. **Opening**: What problem, who should read, what they'll be able to do
2. **What It Feels Like From the Inside**: Phenomenological description (the missing layer from genesis_document.md)
3. **How This Presents in Daily Life**: Observable patterns with "looks like / actually happening" framing
4. **The Strengths**: Systems thinking, diagnostic ability, sensitivity, honest uncertainty, deep modeling
5. **Common Misinterpretations**: Not anxiety, not indecisiveness, not evasion, not pedantry, not arrogance
6. **When Friction Occurs**: Speed, emotional reassurance, authority, social coordination, layer mismatch
7. **Living With This Style**: Brief frame-setting for rest of document

### Conceptual Continuity Notes

**Key phrases established**:

- "amputates uncertainty" - appears in phenomenological section, exactly as canonical
- "structured collapse" - introduced in final section
- "communicable stability, not perfect truth" - introduced in final section

**Examples used**:

- "Why didn't you call?" full multi-dimensional expansion (canonical from examples-bank.md)
- "How was your weekend?" - new example for "too much" pattern
- "Do you love me?" - new example for emotional reassurance friction
- "What do you want for dinner?" - new example for speed friction

**Three-layer communication model**: Mentioned in "When Friction Occurs" (layer mismatch subsection) without full explanation - Section 3.3 will provide the theory.

### Tone/Voice Observations

**Strong patterns that emerged**:

- "What it looks like / What's actually happening" structure works well for the misinterpretation section
- Using "these individuals" rather than "people with this disorder" maintains non-pathologizing frame
- Prose paragraphs feel right for the phenomenological description; bullets would fragment it

**Passages to consider for voice-samples.md**:

- The opening two paragraphs of "What It Feels Like From the Inside"
- The "amputates uncertainty" paragraph
- The "Not Anxiety" distinction paragraph

### Open Questions / Blockers

**Q: How much phenomenological detail for other sections?**
Section 1 went fairly deep into the subjective experience. Later sections (especially practical techniques) should stay more surface-level. The phenomenological foundation is now established; don't need to repeat it.

**Q: Cross-reference format?**
Used markdown link style at end: `[Section 2: The Communication Mismatch](section-02-communication-mismatch.md)`. This assumes standalone files. Will need updating if we compile into single document.

**Q: Section 2 approach?**
Should Section 2 reference Section 1's example and go deeper into the mechanism, or use a fresh example? Recommendation: Reference Section 1 ("As we saw in Section 1...") and use the same "Why didn't you call?" example to show the communication MISMATCH aspect, not just the cognitive experience aspect.

### Next Session Recommendations

**Immediate next task**: Section 2 (The Communication Mismatch)

- Can reference Section 1's phenomenological description
- Focus on WHY this creates communication problems
- Explain why "just give a simple answer" fails
- Introduce "structured collapse" more fully as the solution approach

**Preparation needed for Section 2**:

- Re-read Section 1 to maintain voice continuity
- SPEC.md Section 2 requirements (already read)
- No additional source material needed - conceptual work

**Alternative**: If someone else writes Section 2 in fresh session, they should read Section 1 first to maintain continuity.

### Current Status

**Completed**:

- Section 1: Core Cognitive Profile (first content section)
- Non-pathologizing frame established
- Phenomenological layer added (not in genesis_document.md)
- 4 new daily life examples created
- 5 friction context examples created

**In progress**:

- DEVLOG entry (completing now)

**Next up**:

- Phase 1 continues: Section 2 (Communication Mismatch)
- Then Section 4.1 (Core Techniques)

**Overall progress**: Phase 1 in progress (1 of 3 sections complete)

---

## Session 3: Write Section 2 (The Communication Mismatch)

**Date**: 2026-01-21
**Session Type**: Writing New Section
**Agent**: Claude Code (VS Code Extension) - Opus 4.5

### What Was Done

1. Read all preparatory files per handover protocol:
   - HANDOVER.md (session entry point)
   - onboarding.md (project philosophy refresh)
   - Section 1 (voice continuity)
   - SPEC.md Section 2 requirements
   - voice-samples.md (tone calibration)
   - examples-bank.md (canonical examples)

2. Wrote Section 2: The Communication Mismatch
   - Created `section-02-communication-mismatch.md`
   - Approximately 1,800 words
   - Covers all success criteria from SPEC.md

3. Updated workflow files:
   - SPEC.md Section 2 status → Complete
   - This DEVLOG entry

### Key Decisions Made

**Decision**: Use "Are you free Saturday?" as primary new example

- **Rationale**: Simpler than "Why didn't you call?" but still shows multi-dimensional expansion. Demonstrates mismatch in lower-stakes context.
- **Impact**: Added to examples-bank.md as new canonical mismatch example

**Decision**: Focus on the MISMATCH, not repeat phenomenology

- **Rationale**: Section 1 established what the experience IS. Section 2 explains why it creates communication breakdown—the gap between questioner expectations and responder experience.
- **Impact**: Section 2 stays complementary, not redundant. References Section 1 rather than repeating content.

**Decision**: Introduce "structured collapse" as solution framework

- **Rationale**: This is the core solution concept. Section 1 mentioned it; Section 2 develops it fully.
- **Impact**: Section 4 will provide the specific techniques; Section 2 provides the conceptual framework for why they work.

**Decision**: Include summary table (questioner vs responder experience)

- **Rationale**: Visual summary reinforces the mismatch concept. Provides reference point readers can return to.
- **Impact**: Table format works here; not overused.

**Decision**: Address "lossy compression is not lying" concept

- **Rationale**: Key insight for responders who experience simplification as dishonesty.
- **Impact**: Concept now introduced; Section 3.2 (Information Theory) will develop it further.

### Content Structure Used

1. **Opening**: What problem, who should read, what they'll be able to do
2. **The Structural Mismatch**: Single-slot vs multi-dimensional perception of same question
3. **Why "Just Give a Simple Answer" Fails**: The instruction doesn't address the perceptual difference
4. **The Dishonesty Problem**: Why lossy answers feel like lying to the responder
5. **The Cost of Context-Switching**: Cognitive load of forced collapse under time pressure
6. **What the Questioner Experiences**: Outside view of the behaviors (pause, hedge, counter-question)
7. **What Actually Works: Structured Collapse**: The solution framework
8. **Structured Collapse Is Not Simpler Thinking**: Key distinction
9. **The Mismatch in Summary**: Table comparing experiences
10. **What Comes Next**: Navigation to Section 3 (theory) or Section 4 (practical techniques)

### Conceptual Continuity Notes

**Key phrases used**:

- "amputates uncertainty" - referenced as established concept
- "structured collapse" - fully introduced and explained
- "lossy compression is not lying" - introduced, to be developed in Section 3.2
- "reduce dimensionality" - implicit in structured collapse explanation

**New examples created**:

- "Are you free Saturday?" multi-dimensional expansion
- Before/after comparison: unbounded vs bounded question

**Cross-references established**:

- Links to Section 1 (already written)
- Forward links to Section 3, 4, 5 (to be written)

### Tone/Voice Observations

**Voice continuity maintained**:

- Direct and precise, no hedging
- Non-pathologizing (describes mismatch as structural, not personal)
- "Looks like / actually happening" pattern reused briefly
- Prose paragraphs for conceptual content; bullets only for actual dimension lists

**Strong passages for voice-samples.md**:

- "They're not adding complexity to a simple question. They're perceiving complexity that the question, as asked, genuinely contains."
- "Telling them to 'just answer simply' is like telling someone to 'just see the duck' when they're looking at a duck-rabbit illusion and seeing the rabbit."
- "The transmission is appropriately lossy for the stated purpose. Lossy compression is not lying when both parties agree on the compression level."

### Open Questions / Blockers

**Q: Should Section 4.1 come next or Section 3?**
Per SPEC.md Phase 1 order: Section 4.1 (Core Techniques) should come next. This completes the foundational practical content before going into theory. Section 3 can reference the techniques as concrete examples.

**Q: How much technique detail in Section 4.1?**
SPEC.md specifies: 3-5 examples per technique across professional/intimate/casual contexts. This will be a longer section. May need to decide how much depth per technique vs breadth across all six.

### Next Session Recommendations

**Immediate next task**: Section 4.1 (Core Techniques)

- Expand the six techniques from genesis_document.md
- Use template from voice-samples.md (Name → Mechanism → Examples → When to Use → Failure Modes)
- Generate 3-5 examples per technique across context types
- This is a substantial section—may span multiple sessions

**Preparation needed for Section 4.1**:

- Re-read genesis_document.md technique definitions
- Review examples-bank.md canonical examples
- Check voice-samples.md technique template

**Alternative path**: If context runs low, Phase 1 goal (establish voice/tone/core concepts) is now largely achieved. Could continue to Section 4.1 or shift to Phase 2 Section 5.1 (Response Protocols) which is more immediately practical for responders.

### Current Status

**Completed**:

- Section 1: Core Cognitive Profile
- Section 2: The Communication Mismatch
- "Structured collapse" concept fully introduced
- Mismatch mechanism explained

**In progress**:

- Voice samples and examples-bank updates (this session)

**Next up**:

- Section 4.1: Core Techniques (Phase 1 completion)
- Or Section 5.1: Response Protocols (Phase 2 start, if practical utility prioritized)

**Overall progress**: Phase 1 in progress (2 of 3 sections complete)

---

## Session 4: Write Section 4.1 (Core Techniques)

**Date**: 2026-01-21
**Session Type**: Writing New Section
**Agent**: Claude Code (VS Code Extension) - Sonnet 4.5

### What Was Done

1. Read all preparatory files per handover protocol:
   - HANDOVER.md (session entry point)
   - genesis_document.md (source material for six techniques)
   - SPEC.md Section 4.1 requirements
   - voice-samples.md (tone calibration and technique template)
   - examples-bank.md (canonical examples)
   - Sections 1-2 (voice continuity)

2. Wrote Section 4.1: Core Techniques
   - Created `section-04-1-core-techniques.md`
   - Approximately 4,200 words
   - All six techniques with full template (definition, mechanism, 3-5 examples, when to use, failure modes)
   - Covers all success criteria from SPEC.md

3. Updated workflow files:
   - SPEC.md Section 4.1 status → Complete
   - This DEVLOG entry (in progress)

### Key Decisions Made

**Decision**: Provide 4-5 examples per technique across diverse contexts

- **Rationale**: Genesis document had only 1 example per technique. Need to show techniques work across professional, intimate, casual, medical, diagnostic, planning contexts.
- **Impact**: Section is longer (~4,200 words) but readers get immediate sense of versatility. Can see themselves using techniques in their specific contexts.

**Decision**: Include 3 detailed failure modes per technique with fixes

- **Rationale**: SPEC.md required failure modes. Real value is in the correction strategies, not just cataloging what goes wrong.
- **Impact**: Readers learn troubleshooting, not just technique application. Builds confidence that techniques are recoverable when misapplied.

**Decision**: Add "Using These Techniques Together" section before closing

- **Rationale**: Techniques aren't mutually exclusive. Real questions often stack multiple techniques.
- **Impact**: Demonstrates that combining techniques compounds effectiveness. Shows 4-technique stack example.

**Decision**: Explain mechanism before examples for each technique

- **Rationale**: "Show why, then show how" matches project philosophy. Readers who understand mechanism can adapt techniques to new contexts.
- **Impact**: Each technique becomes a generative pattern, not just a script to memorize.

### Content Structure Used

For each technique:

1. **Name & Definition**: One-sentence clear definition
2. **Mechanism**: WHY it reduces cognitive load / dimensionality (1-2 sentences)
3. **Examples**: 4-5 before/after pairs across contexts (professional, intimate, casual, medical, diagnostic, planning)
4. **When to Use**: Specific situations where this technique works best
5. **Failure Modes**: 3 common failures with corrections

Overall section structure:

1. Opening (what problem, who should read, what they'll be able to do)
2. "What These Techniques Do" (conceptual frame)
3. Six techniques with full template
4. "Using These Techniques Together" (combination strategies)
5. "What Comes Next" (navigation)

### Conceptual Continuity Notes

**Key phrases used consistently**:

- "Reduce dimensionality" - established as what techniques actually do
- "Amputates uncertainty" - referenced in mechanism explanations
- "Communicable stability, not perfect truth" - reinforced as goal
- "Lossy compression" - referenced in uncertainty permission and output-format constraints

**New examples created** (24 total new before/after pairs):

- Domain-binding: project deadline, phone call (canonical), dinner, medical treatment
- Uncertainty permission: server outage, upset feelings, restaurant preference, diagnosis, plan viability
- Forced-slice: lost client, partner stress, movie reaction, symptom diagnosis, decision-making
- Counterfactual anchoring: project decline, party attendance, place preference, deadline negotiation, medication adherence
- Output-format constraints: client meeting, holiday plans, weekend plans, meeting feedback, document review
- Role-locking: feature launch, city move, movie interest, advisory urgency, surgery decision

**Cross-references established**:

- Forward links to Section 4.2 (Additional Techniques)
- Forward links to Section 4.3 (Technique Selection)
- Forward links to Section 5.1 (Response Protocols)

### Tone/Voice Observations

**Voice continuity maintained**:

- Direct and precise definitions
- Mechanism explanations focus on cognitive load reduction
- Before/after format for all examples
- Non-pathologizing frame throughout
- Prose for conceptual content, bullets only for actual lists

**Strong passages for voice-samples.md**:

- "These six techniques don't reduce intelligence or nuance. They reduce dimensionality."
- "Domain-binding explicitly names one dimension and temporarily excludes the others, telling the cognitive system 'evaluate only this layer.'"
- "Uncertainty permission removes the demand for certainty by explicitly acknowledging that you're asking for the responder's current model, not eternal truth."
- "The responder isn't claiming their answer is complete, just that it's one true factor among others." (forced-slice)
- "Counterfactual framing also reduces defensiveness because it's forward-looking rather than backward-looking."
- "Output-format constraints externalize that decision [about scope]."
- "Role-locking specifies which perspective to use, eliminating the meta-question of 'which version of me is being asked?'"

**Formatting pattern established**:

- Consistent technique template (can be reused in Section 4.2)
- Context labels in bold for examples (Professional context:, Intimate context:, etc.)
- Failure modes numbered 1-3 with "Fix:" for each
- "Instead of: / Use:" format for all before/after pairs

### Open Questions / Blockers

**Q: Section 4.2 (Additional Techniques) depth?**
SPEC.md lists 6 additional techniques (scope-locking, reversibility framing, confidence calibration, intent declaration, acceptable error tolerance, iteration permission). Should these get the same level of detail as core six, or lighter treatment since they're more specialized?

**Recommendation**: Use same template for consistency, but 3 examples instead of 4-5. They're "additional" so slightly less depth is appropriate.

**Q: Should examples-bank.md track all 24 new examples?**
That's a lot. Maybe track only the best 1-2 per technique as canonical, note others are "context variations."

**Recommendation**: Add 6 canonical examples (one per technique, strongest one) to examples-bank.md. Note file location for the full set.

**Q: Phase 1 complete—what next?**
Phase 1 goal was "establish voice, tone, and core concepts + practical techniques foundation." Sections 1, 2, 4.1 now complete. This meets Phase 1 goals.

**Options**:

- Continue to Phase 2: Section 5.1 (Response Protocols) - practical depth
- Polish Phase 1 sections before moving on
- Write Section 4.2 (Additional Techniques) to complete Part II Section 4

**Recommendation**: Phase 1 is solid foundation. Move to Phase 2 Section 5.1 (Response Protocols) to provide responder-side tools, making document immediately useful for both questioners and responders.

### Next Session Recommendations

**Immediate next task**: Update voice-samples.md and examples-bank.md with Session 4 strong passages

**Then choose path**:

**Path A - Phase 2 Practical Depth**: Section 5.1 (Response Protocols for High-Uncertainty Responders)

- Provides the responder-side complement to Section 4.1 questioner techniques
- Makes document immediately useful for both audiences
- Can reference Section 4.1 techniques when explaining what to request

**Path B - Complete Section 4**: Section 4.2 (Additional Techniques)

- Finishes the question design toolkit
- Maintains momentum in Part II
- Provides fuller question design resource before switching to response protocols

**Recommendation**: Path A (Phase 2, Section 5.1). Document is most useful when it serves both questioners and responders. Section 5.1 provides the responder toolkit that pairs with Section 4.1's questioner toolkit.

**Preparation needed for Section 5.1**:

- Review SPEC.md Section 5.1 requirements (scripts, provisional commitment language, meta-honesty)
- Review Section 4.1 to reference techniques responders can request
- Review voice-samples.md for tone continuity

### Current Status

**Phase 1 COMPLETE**:

- Section 1: Core Cognitive Profile ✅
- Section 2: The Communication Mismatch ✅
- Section 4.1: Core Techniques ✅
- Voice and tone established
- Core concepts introduced (amputates uncertainty, structured collapse, reduce dimensionality)

**In progress**:

- Voice-samples.md and examples-bank.md updates (this session)
- HANDOVER.md update for Session 5

**Next up**:

- Phase 2 begins: Section 5.1 (Response Protocols) OR
- Section 4.2 (Additional Techniques) to complete Part II Section 4

**Overall progress**: Phase 1 complete (~8,000 words of foundational content), ready for Phase 2 (practical depth)

### Session 4 Addendum: Onboarding Optimization

**What Was Done**:

- Rewrote onboarding.md as single entry point (~225 lines, down from 390)
- Slimmed HANDOVER.md to only ephemeral/in-flight content (~67 lines, down from 270)
- New flow: "read onboarding.md" → discovers handover → knows what else to read

**Token savings**: ~60-70% reduction in required reading for typical new session (onboarding + handover now ~300 lines vs previous ~660 lines)

**Decision rationale**: Context was filling up; project growing large enough to need efficient onboarding. Static info (key phrases, templates, file structure) now in onboarding.md; temporal info (what just happened, what's next) in HANDOVER.md.

---

## Session 5: Write Section 5.1 (Response Protocols)

**Date**: 2026-01-22
**Session Type**: Writing New Section
**Agent**: Claude Code (VS Code Extension) - Sonnet 4.5

### What Was Done

1. Read all preparatory files per handover protocol:
   - HANDOVER.md (session entry point)
   - onboarding.md (project philosophy)
   - SPEC.md Section 5.1 requirements
   - DEVLOG.md (last 2-3 sessions for context)
   - voice-samples.md (tone calibration)
   - examples-bank.md (canonical examples)
   - Section 4.1 (techniques to reference)

2. Wrote Section 5.1: Response Protocols for High-Uncertainty Responders
   - Created `section-05-1-response-protocols.md`
   - Approximately 5,200 words
   - Five protocol categories with concrete scripts
   - Covers all success criteria from SPEC.md

3. Updated workflow files:
   - SPEC.md Section 5.1 status → Complete
   - voice-samples.md (6 new strong passages)
   - examples-bank.md (5 canonical response protocol patterns)
   - This DEVLOG entry

### Key Decisions Made

**Decision**: Structure as five protocol categories rather than individual techniques

- **Rationale**: Response protocols are more fluid than question techniques. Responders need to understand when to signal, when to provide provisional answers, when to request restructuring, when to name process, and when to make strategic choices. These are categories of response, not discrete techniques.
- **Impact**: Section feels less prescriptive, more judgment-building. Responders learn a framework, not just scripts.

**Decision**: Include "Strategic Choices" as final protocol

- **Rationale**: Not every poorly-structured question needs restructuring. Responders need judgment about when precision matters vs when social flow matters more.
- **Impact**: Prevents "always restructure everything" approach. Acknowledges context and trade-offs. Makes framework practical rather than idealistic.

**Decision**: Emphasize "information, not apology" throughout

- **Rationale**: High-uncertainty responders often over-apologize for processing time. Signals work better as information ("I need 30 seconds to map this") than apology ("Sorry I'm so slow").
- **Impact**: Reframes processing as legitimate, not problematic. Helps responders reduce unnecessary apology language.

**Decision**: Provide multiple script variations for each protocol

- **Rationale**: People need to adapt scripts to their own voice. Multiple variations show the pattern rather than single "correct" phrasing.
- **Impact**: ~50 total scripts/variations across five protocols. Responders can find phrasing that fits their context and voice.

**Decision**: Include "combining protocols" example at end

- **Rationale**: Real conversations require multiple protocols. Need to show how they stack.
- **Impact**: Example of manager question ("Why is project behind?") shows processing signal → restructuring request → provisional answer → meta-honesty in sequence. Demonstrates protocol fluidity.

### Content Structure Used

1. **Opening**: What problem, who should read, what they'll be able to do
2. **What These Protocols Do**: Conceptual frame (responder complement to Section 4.1 questioner techniques)
3. Five protocol categories:
   - Signaling Processing Needs
   - Provisional Commitment Language
   - Requesting Question Restructuring
   - Meta-Honesty: Naming the Process
   - Strategic Choices: When to Push Back vs Give Lossy Answer
4. **Combining These Protocols**: Multi-protocol example
5. **What Comes Next**: Navigation

Each protocol section includes:

- Definition
- Why it works (mechanism)
- 10-15 scripts/examples across contexts
- When to use
- 3 failure modes with fixes

### Conceptual Continuity Notes

**Key phrases used consistently**:

- "Amputates uncertainty" - referenced in provisional commitment and meta-honesty sections
- "Communicable stability" - referenced in opening frame
- "Lossy compression" - central to provisional commitment and strategic choices
- "Reduce dimensionality" - referenced when discussing Section 4.1 techniques

**New patterns established**:

- "Based on X, my current answer is Y" - canonical provisional commitment format
- "I'm [struggling/hesitating/stuck] because..." - meta-honesty framing pattern
- Processing signals as information, not apology
- Strategic choice framework: when to push back vs give lossy answer

**Cross-references established**:

- References to Section 4.1 techniques (when explaining restructuring requests)
- Forward links to Section 5.2 (questioner-side complement)
- Forward links to Section 6.1 (shared real-time negotiation protocols)
- Forward links to Section 6.3 (confidence expression systems)

### Tone/Voice Observations

**Voice continuity maintained**:

- Direct and precise definitions
- Non-pathologizing throughout ("legitimate space to process" not "fixing your delays")
- Practically grounded with ready-to-use scripts
- Intellectually honest about trade-offs (strategic choice framework)
- Prose for conceptual content, bullets only for actual script lists

**Strong passages for voice-samples.md** (6 added):

- Processing signals convert ambiguous silence into informative communication
- Provisional commitment separates "current model" from "eternal truth"
- Restructuring requests as collaborative problem-solving
- Meta-honesty makes internal process external
- Strategic choice framework (relationship cost vs information cost)
- "You don't have to choose between honesty and clarity" (closing insight)

**Pattern established**:

- Each protocol section follows: Definition → Mechanism → Scripts (with context labels) → When to Use → Failure Modes (numbered 1-3 with fixes)
- Consistent with Section 4.1 technique template structure
- Can be reused for Section 5.2 and other protocol sections

### Open Questions / Blockers

**Q: Should Section 5.2 (For Questioners) or Section 6.2 (Question Intent Taxonomy) come next?**

Per SPEC.md Phase 2 priority order:

1. Section 5.1 (Response Protocols) ✅ DONE
2. Section 6.2 (Question Intent Taxonomy)
3. Section 11 (Worked Examples)

However, Section 5.2 (For Questioners) is the natural complement to 5.1 and completes the Section 5 pairing.

**Recommendation**: Write Section 5.2 next to complete the bilateral response protocol coverage. Then proceed to Section 6.2 (Question Intent Taxonomy) per Phase 2 order. This gives responders and questioners paired tools before moving to intent classification.

**Q: How much overlap should Section 5.2 have with Section 4.1?**

Section 4.1 taught questioners how to structure questions. Section 5.2 should teach questioners how to:

- Read processing signals accurately
- Declare intent upfront
- Distinguish "needs time" from "refusing to answer"
- Follow up without creating more load

This is complementary but distinct from technique design. Section 5.2 is about questioner responses to responder behaviors, not question structure.

### Next Session Recommendations

**Immediate next task**: Section 5.2 (Response Protocols: For Questioners)

- Provides questioner-side complement to Section 5.1 responder tools
- Completes bilateral protocol coverage in Section 5
- Can reference both Section 4.1 techniques and Section 5.1 responder signals

**Preparation needed for Section 5.2**:

- Review SPEC.md Section 5.2 requirements (intent declaration, signal recognition, patience vs enabling)
- Review Section 5.1 to reference responder protocols questioners will encounter
- Review voice-samples.md for tone continuity

**Alternative**: If pivoting to Section 6.2 (Question Intent Taxonomy) per Phase 2 order:

- Taxonomy of question intents (logistical, emotional, diagnostic, planning, social)
- Calibrating expectations for each type
- Mixed-intent recognition
- Can reference Section 4.1 techniques mapped to intents

**Current recommendation**: Complete Section 5 with 5.2, then proceed to Phase 2 Section 6.2.

### Current Status

**Phase 2 PROGRESS**:

- Section 5.1: Response Protocols (responder-side) ✅
- Section 5.2: Response Protocols (questioner-side) - Next
- Section 6.2: Question Intent Taxonomy - After 5.2

**Completed Sections** (4 total, ~13,200 words):

- Section 1: Core Cognitive Profile ✅
- Section 2: The Communication Mismatch ✅
- Section 4.1: Core Techniques ✅
- Section 5.1: Response Protocols (For High-Uncertainty Responders) ✅

**In progress**:

- HANDOVER.md update (next)

**Next up**:

- Section 5.2 (For Questioners) to complete bilateral protocols OR
- Section 6.2 (Question Intent Taxonomy) per Phase 2 order

**Overall progress**: Phase 2 in progress (1 of 3 priority sections complete), document provides tools for both questioners and responders

---

## Session 6: Write Section 5.2 (Response Protocols for Questioners)

**Date**: 2026-01-22
**Session Type**: Writing New Section
**Agent**: Claude Code (VS Code Extension) - Sonnet 4.5

### What Was Done

1. Optimized onboarding.md to make self-executing nature explicit
   - Added upfront notice that reading means executing instructions
   - Changed passive "you need to read" to active "ACTION: Read NOW"
   - Updated final section to confirm completion rather than assign next steps

2. Read all preparatory files per handover protocol:
   - HANDOVER.md (session entry point)
   - SPEC.md Section 5.2 requirements
   - DEVLOG.md (last 2-3 sessions for context)
   - voice-samples.md (tone calibration)
   - examples-bank.md (canonical examples)
   - Section 5.1 (responder protocols to complement)

3. Wrote Section 5.2: Response Protocols for Questioners
   - Created `section-05-2-response-protocols-questioners.md`
   - Approximately 6,400 words
   - Five protocol categories with scripts and examples
   - Covers all success criteria from SPEC.md

4. Updated workflow files:
   - SPEC.md Section 5.2 status → Complete
   - voice-samples.md (6 new strong passages)
   - This DEVLOG entry

### Key Decisions Made

**Decision**: Structure as five protocol categories mirroring the questioner's journey

- **Rationale**: Questioners need temporal framework (before/during/after asking) plus strategic judgment (when to wait/intervene/accept). Categories follow natural question lifecycle rather than matching Section 5.1's structure.
- **Impact**: Section 5.2 feels complementary but distinct from Section 5.1. Both are practical protocols but serve different sides of the exchange.

**Decision**: Include "Patience vs Enabling Analysis-Paralysis" as dedicated protocol

- **Rationale**: This is the hardest calibration for questioners—when to wait vs when to help. Deserves full protocol treatment, not just a note.
- **Impact**: Gives questioners decision framework with clear triggers for each mode. Prevents both impatience (interrupting legitimate processing) and enabling (allowing endless spiraling).

**Decision**: Provide signal recognition guide with behavioral distinctions

- **Rationale**: Questioners often misread pauses as avoidance. Need concrete behavioral markers to distinguish processing from evasion.
- **Impact**: Guide lists specific signals for "working on this," "too many dimensions," "uncertain," "don't know," and "avoiding." Questioners can observe behavior, not mind-read.

**Decision**: Include combined protocols example at end

- **Rationale**: Real conversations stack multiple protocols. "Project status" example shows all five working together.
- **Impact**: Demonstrates protocol integration, not just isolated techniques. Shows how protocols compound effectiveness.

**Decision**: Emphasize collaboration frame throughout

- **Rationale**: Questioners can read protocols as "dealing with difficult people." Need consistent framing: responders aren't being difficult, they're processing complexity.
- **Impact**: Every protocol section includes language like "collaborative problem-solving," "the responder isn't being difficult," "they're signaling what they need."

### Content Structure Used

1. **Opening**: What problem, who should read, what they'll be able to do
2. **What These Protocols Do**: Conceptual frame (complements Section 4.1 and 5.1)
3. Five protocol categories:
   - Declaring Intent Upfront
   - Reading Processing Signals
   - Patience vs Enabling Analysis-Paralysis
   - Responding to Restructuring Requests
   - Following Up Without Adding Load
4. **Combining These Protocols**: Multi-protocol example showing integration
5. **What Comes Next**: Navigation

Each protocol section includes:

- Definition
- Why it works (mechanism)
- Scripts/templates or recognition patterns
- Examples across contexts (professional, intimate, medical, casual)
- When to use
- 3 failure modes with fixes

### Conceptual Continuity Notes

**Key phrases used consistently**:

- "Reduce dimensionality" - what structured questions do
- "Multi-dimensional expansion" - what poorly-structured questions trigger
- "Processing complexity you may not see" - non-judgmental frame for responder behavior
- "Collaborative problem-solving" - frame for restructuring requests

**New patterns established**:

- Intent declaration templates for 5 intent types (logistical, emotional, diagnostic, decision, social)
- Signal recognition guide with behavioral markers
- Patience/intervention/acceptance decision framework
- Low-load vs high-load follow-up patterns

**Cross-references established**:

- References to Section 4.1 techniques (domain-binding, forced-slice, etc.)
- References to Section 5.1 responder signals
- Forward links to Section 6.1 (shared real-time negotiation)
- Forward links to Section 6.2 (question intent taxonomy)
- Forward links to Section 6.3 (confidence expression systems)

### Tone/Voice Observations

**Voice continuity maintained**:

- Direct and precise definitions
- Non-pathologizing throughout ("they're processing complexity," not "they're being difficult")
- Practically grounded with ready-to-use scripts and templates
- Intellectually honest about trade-offs (patience vs enabling, restructuring costs)
- Examples-rich (5+ examples per protocol across contexts)

**Strong passages for voice-samples.md** (6 added):

- Before/during/after temporal framework for questioner protocols
- Intent declaration mechanism (eliminates meta-processing)
- Signal reading to prevent misattributing motives
- Patience/intervention/acceptance tri-part framework
- Restructuring as collaboration not criticism
- Follow-up load management (build vs create new load)

**Pattern consistency**:

- Each protocol section follows: Definition → Mechanism → Scripts/Patterns → Examples → When to Use → Failure Modes (numbered 1-3 with fixes)
- Consistent with Section 5.1 structure
- Can be reused for future protocol sections

### Open Questions / Blockers

**Q: Should Section 6.2 (Question Intent Taxonomy) or Section 6.1 (Real-Time Negotiation) come next?**

Per SPEC.md Phase 2 priority order:

1. Section 5.1 (Response Protocols - Responders) ✅ DONE
2. Section 6.2 (Question Intent Taxonomy)
3. Section 11 (Worked Examples)

However, Section 6.1 (Real-Time Negotiation) is the natural next step now that both sides have their protocols (5.1 and 5.2). It provides the shared vocabulary for protocol negotiation.

**Recommendation**: Write Section 6.2 (Question Intent Taxonomy) per Phase 2 order. Intent taxonomy provides framework for calibrating expectations around different question types (logistical vs emotional vs diagnostic). This complements the protocols we've just established. Section 6.1 can come after 6.2.

**Q: Should intent declaration templates from Section 5.2 be tracked in examples-bank.md?**

These are patterns/templates rather than specific before/after examples. The "project status" combined example could be canonical.

**Recommendation**: Add the combined "project status" example to examples-bank.md as canonical demonstration of all questioner protocols working together. Intent templates are patterns, not examples to track.

### Next Session Recommendations

**Immediate next task**: Section 6.2 (Question Intent Taxonomy)

- Provides framework for intent types (logistical, emotional, diagnostic, planning, social)
- Helps both questioners and responders calibrate expectations
- Maps to Section 4.1 techniques and Section 5 protocols
- Can reference Section 5.2 intent declarations

**Preparation needed for Section 6.2**:

- Review SPEC.md Section 6.2 requirements (intent types, expectations, mixed-intent handling)
- Review Section 4.1 to map techniques to intent types
- Review Section 5.2 intent declaration examples
- Review voice-samples.md for tone continuity

**Alternative**: If pivoting to Section 6.1 (Real-Time Negotiation):

- Shared signaling vocabulary for both parties
- Protocol negotiation phrases
- Emergency simplification strategies
- Meta-communication ("let's talk about how we're talking")
- Can reference both Section 5.1 and 5.2 protocols

**Current recommendation**: Proceed to Section 6.2 (Question Intent Taxonomy) per Phase 2 order, then return to Section 6.1 (Real-Time Negotiation) to complete Section 6.

### Current Status

**Section 5 COMPLETE**:

- Section 5.1: Response Protocols (For High-Uncertainty Responders) ✅
- Section 5.2: Response Protocols (For Questioners) ✅
- Bilateral protocol coverage complete

**Completed Sections** (5 total, ~19,600 words):

- Section 1: Core Cognitive Profile ✅
- Section 2: The Communication Mismatch ✅
- Section 4.1: Core Techniques ✅
- Section 5.1: Response Protocols (For High-Uncertainty Responders) ✅
- Section 5.2: Response Protocols (For Questioners) ✅

**In progress**:

- HANDOVER.md update (next)
- examples-bank.md update (add combined protocol example)

**Next up**:

- Section 6.2 (Question Intent Taxonomy) per Phase 2 order
- Section 6.1 (Real-Time Negotiation) to complete Section 6
- Section 11 (Worked Examples) to complete Phase 2

**Overall progress**: Section 5 complete, Phase 2 in progress (1 of 3 priority sections complete), document now serves both questioners and responders with practical protocols

### Session 6 Addendum: Onboarding Optimization

**What Was Done**:

- Updated onboarding.md to make self-executing nature explicit
- Changed from "you should read" to "ACTION: Read NOW before continuing"
- Added upfront notice: "Reading this document means FOLLOWING the instructions in it"

**Token efficiency impact**: Makes expectation clearer—when you finish reading onboarding.md, you've already done all prep work, not just learned about what to do. Reduces "I'm ready" → "did you read the files?" → "oh, I'll read them now" cycles.

**User feedback**: Direct request to make onboarding more explicit that reading = executing instructions.

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

## Session 7: Write Section 6.2 (Question Intent Taxonomy)

**Date**: 2026-01-22
**Session Type**: Writing
**Agent**: Claude Code (Sonnet 4.5)

### What Was Done

- Wrote Section 6.2: Question Intent Taxonomy (~5,900 words)
- Created content/section-06-2-question-intent-taxonomy.md
- Updated SPEC.md to mark Section 6.2 complete

### Key Decisions Made

**Decision**: Structure around five intent types (logistical, emotional, diagnostic, planning, social)
**Rationale**: These categories are exhaustive for practical purposes and map clearly to different technique/protocol selections
**Impact**: Gives both questioners and responders vocabulary to identify and name what a question is really asking for

**Decision**: Give diagnostic intent equal treatment rather than framing as "the problem"
**Rationale**: High-dimensional processing is *appropriate* for diagnostic intent; the issue is when it's applied to other intent types
**Impact**: Maintains non-pathologizing frame—the cognitive style has a place, just needs intent calibration

**Decision**: Include extensive mixed-intent section
**Rationale**: Real questions (especially in relationships) carry multiple intents; acknowledging this prevents oversimplification
**Impact**: Makes framework more realistic and gives repair strategies when intent is ambiguous

**Decision**: Connect each intent type back to Section 4.1 techniques and Section 5 protocols
**Rationale**: Intent taxonomy is the selection layer—tells you *which* technique or protocol to use
**Impact**: Makes previous sections more usable; provides the "when to use what" guidance

### Conceptual Continuity Notes

- Intent taxonomy is the bridge between techniques (Section 4) and protocols (Section 5)
- Sets up Section 6.1 (Real-Time Negotiation) by establishing shared vocabulary
- Sets up Section 6.3 (Confidence Expression) by showing how certainty calibration differs per intent
- Sets up Section 7 (Intimate Relationships) by showing how intent complexity increases in high-trust contexts

### Tone/Voice Observations

- Maintained example-rich approach (3+ examples per intent type across contexts)
- Used consistent key phrases ("reduce dimensionality", "structured collapse")
- Kept non-pathologizing frame (diagnostic intent is *appropriate* depth, not "overthinking")
- Balanced responder and questioner perspectives throughout

### Recognition Pattern Additions

Each intent type now includes:

- What questioner needs vs what responder hears
- Expectation calibration (what each party naturally expects/provides)
- Recognition signals (how to identify this intent type)
- 3+ concrete examples across professional/intimate/casual contexts
- Mapping to Section 4.1 techniques
- Connection to Section 5 protocols
- Common failure modes

### Next Session Recommendations

**Recommended: Section 6.1 (Real-Time Negotiation)**

- Now that Section 6.2 establishes intent taxonomy, Section 6.1 can show how to negotiate intent mismatches in the moment
- Provides shared signaling vocabulary that uses intent categories from 6.2
- Completes Section 6 theoretical/framework layer
- Dependencies all met (Section 5.1, 5.2, and 6.2 complete)

**Alternative: Section 6.3 (Confidence Expression Systems)**

- Shows how to calibrate confidence claims per intent type (uses 6.2 taxonomy)
- Completes Section 6
- Dependencies met

**Alternative: Section 11 (Worked Examples)**

- Per Phase 2 order (third priority)
- Can now reference Sections 1, 2, 4.1, 5.1, 5.2, and 6.2
- Shows techniques + protocols + intent recognition in realistic scenarios

**Current recommendation**: Section 6.1 to complete Section 6 framework layer, then either 6.3 (complete Section 6) or Section 11 (Phase 2 priority).

### Current Status

**Section 6 progress**:

- Section 6.1: Real-Time Negotiation - Needs writing
- Section 6.2: Question Intent Taxonomy - ✅ COMPLETE
- Section 6.3: Confidence Expression Systems - Needs writing

**Completed Sections** (6 total, ~25,500 words):

- Section 1: Core Cognitive Profile ✅
- Section 2: The Communication Mismatch ✅
- Section 4.1: Core Techniques ✅
- Section 5.1: Response Protocols (For High-Uncertainty Responders) ✅
- Section 5.2: Response Protocols (For Questioners) ✅
- Section 6.2: Question Intent Taxonomy ✅

**Phase 2 progress**: 2 of 3 priority sections complete (5.1 ✅, 6.2 ✅, 11 remaining)

**Next up**:

- Section 6.1 (Real-Time Negotiation) - recommended
- Section 6.3 (Confidence Expression) - alternative
- Section 11 (Worked Examples) - Phase 2 third priority

**Overall progress**: Framework layer now includes techniques (4.1), protocols for both parties (5.1, 5.2), and intent taxonomy (6.2). Ready for real-time negotiation (6.1) or applied examples (11).

## Session 7 Continued: Write Section 6.1 (Real-Time Negotiation)

**Date**: 2026-01-22 (same session, second section)
**Session Type**: Writing
**Agent**: Claude Code (Sonnet 4.5)

### What Was Done

- Wrote Section 6.1: Real-Time Negotiation (~6,800 words)
- Created content/section-06-1-real-time-negotiation.md
- Updated SPEC.md to mark Section 6.1 complete

### Key Decisions Made

**Decision**: Structure as signaling vocabulary for both parties (responders + questioners) separately
**Rationale**: Real-time negotiation requires both sides to have vocabulary; splitting by role makes it immediately clear which phrases to use
**Impact**: Makes section scannable—responders can find their phrases, questioners can find theirs

**Decision**: Include extensive "emergency simplification" section with 5+ techniques
**Rationale**: Sometimes standard techniques/protocols fail and communication is actively breaking down; need escape hatches
**Impact**: Provides safety valve for worst-case scenarios, acknowledges that structure doesn't always work

**Decision**: Dedicate major section to meta-communication ("talking about how we're talking")
**Rationale**: Meta-level moves are the most powerful negotiation tool but least commonly taught; needed detailed treatment
**Impact**: Gives both parties permission and vocabulary to pause and diagnose communication patterns

**Decision**: Include full worked example of meta-communication exchange (partner asking "Do you want kids?")
**Rationale**: Meta-communication is abstract and can feel awkward; showing complete exchange demonstrates it's practical
**Impact**: Makes meta-communication concrete and usable, shows repair pattern in high-stakes emotional context

**Decision**: Add "graceful exit" strategies for when negotiation fails
**Rationale**: Not all questions are answerable even with perfect negotiation; needed honest acknowledgment and exit paths
**Impact**: Removes pressure to answer every question, provides honorable ways to say "I can't answer this"

### Conceptual Continuity Notes

- Real-time negotiation is the "lubricant" that makes techniques (Section 4.1) and protocols (Sections 5.1, 5.2) usable in messy reality
- Uses intent taxonomy from Section 6.2 extensively ("I'm hearing logistical intent—is that right?")
- Sets up Section 6.3 (Confidence Expression) by mentioning uncertainty negotiation
- Sets up Section 7 (Intimate Relationships) by showing negotiation in emotional contexts
- Sets up Section 11 (Worked Examples) by providing repair vocabulary that examples can reference

### Tone/Voice Observations

- Maintained example-rich approach (3+ examples per technique)
- Used consistent non-pathologizing frame ("you're stuck" vs "you're overthinking")
- Balanced responder and questioner perspectives throughout
- Meta-communication example was vulnerable and emotionally honest (maintains intellectual honesty value)

### Section Structure Pattern

Each negotiation phrase includes:

- When to use it
- What it communicates (subtext/intent)
- Concrete example in context
- Why it works (mechanism)

Emergency simplification techniques include:

- When to use
- How it works
- Example
- Failure mode or critical caveat

### Integration Achievements

- Section 6.1 references Section 6.2 intent taxonomy throughout
- References Section 5.1 and 5.2 protocols as things being negotiated
- References Section 4.1 techniques as tools that negotiation makes selectable
- Creates shared vocabulary that upcoming sections can build on

### Next Session Recommendations

**Options for completing Section 6**:

**Option A: Section 6.3 (Confidence Expression Systems)**

- Completes Section 6 framework
- Shows how to calibrate confidence claims per intent type
- Natural follow-on from negotiation (negotiating certainty levels)
- Dependencies: Section 3.2 (lossy compression), Section 5.1 (responder tools), Section 6.2 (intent taxonomy)

**Option B: Section 11 (Worked Examples & Case Studies)**

- Per Phase 2 order (third priority, after 5.1 and 6.2)
- Now has full framework to demonstrate: techniques (4.1), protocols (5.1, 5.2), intent taxonomy (6.2), negotiation (6.1)
- Can show complete exchanges with negotiation moments, intent recognition, protocol switching
- Dependencies: Sections 1, 2, 4.1, 5.1, 5.2, 6.1, 6.2

**Option C: Theory sections (Section 3.1-3.4)**

- Theory can now reference concrete examples from Sections 4, 5, and 6
- Section 3.3 (Three-Layer Communication Model) particularly relevant after Section 6 work

**Current recommendation**: Either Section 6.3 (complete Section 6 framework) or Section 11 (Phase 2 priority). Section 6.3 if you want tight conceptual closure before examples; Section 11 if you want to demonstrate everything we've built before adding more theory.

### Current Status

**Section 6 progress**:

- Section 6.1: Real-Time Negotiation - ✅ COMPLETE
- Section 6.2: Question Intent Taxonomy - ✅ COMPLETE
- Section 6.3: Confidence Expression Systems - Needs writing

**Completed Sections** (7 total, ~32,300 words):

- Section 1: Core Cognitive Profile ✅
- Section 2: The Communication Mismatch ✅
- Section 4.1: Core Techniques ✅
- Section 5.1: Response Protocols (For High-Uncertainty Responders) ✅
- Section 5.2: Response Protocols (For Questioners) ✅
- Section 6.1: Real-Time Negotiation ✅
- Section 6.2: Question Intent Taxonomy ✅

**Phase 2 progress**: 2 of 3 priority sections complete (5.1 ✅, 6.2 ✅, 11 remaining)

**Next up**:

- Section 6.3 (Confidence Expression) - completes Section 6
- Section 11 (Worked Examples) - Phase 2 third priority
- Section 3.x (Theoretical Frameworks) - can now reference practical sections

**Overall progress**: Complete practical framework now exists—techniques, bilateral protocols, intent taxonomy, and negotiation vocabulary. Ready for either confidence expression (6.3), worked examples (11), or theory (3.x).

---

## Session 8: Section 6.3 (Confidence Expression Systems)

**Date**: 2026-01-22
**Model**: Sonnet 4.5
**Files Modified**: content/section-06-3-confidence-expression.md (NEW), workflow/SPEC.md, workflow/DEVLOG.md, HANDOVER.md
**Word Count**: ~5,325 words
**Session Focus**: Complete Section 6 framework by writing confidence expression systems

### What Was Written

Section 6.3: Confidence Expression Systems—showing responders and questioners how to make uncertainty informative rather than paralyzing.

**Major content blocks**:

1. **Numerical vs. Verbal Confidence Scales** - When to use percentages vs words like "probably," with pros/cons and failure modes for each
2. **Modal Answer + Uncertainty Bounds Format** - Structure for giving best answer + confidence level + specific uncertainty source
3. **Confident But Wrong vs. Uncertain But Useful** - Why calibrated uncertainty is more valuable than false certainty
4. **Making Uncertainty Informative** - Four patterns for explaining why you're uncertain in ways that reveal useful information
5. **Calibrating to Intent Type** - How to express confidence differently for logistical/emotional/diagnostic/planning/social questions
6. **Practical Scripts** - Ready-to-use formats for common scenarios (advice, timelines, emotional topics, 50-50 decisions, confidence updates)
7. **Common Failure Modes** - Seven patterns to avoid (confidence without bounds, hedging inflation, false precision, hiding behind uncertainty, overconfidence signaling, mismatched format)

### Key Decisions & Rationale

**Decision**: Structure around numerical vs verbal confidence as primary organizing dimension
**Rationale**: This is the most common responder question ("Should I use numbers or words?"), and the answer depends on context
**Impact**: Makes the choice criteria immediately clear; readers can quickly find their situation

**Decision**: Create "Modal Answer + Uncertainty Bounds" as a structured format pattern
**Rationale**: Most confidence expression failures come from either (1) giving answer without confidence, or (2) expressing uncertainty without specificity
**Impact**: Provides template that prevents both failures: "[Answer], [confidence], [specific uncertainty source]"

**Decision**: Dedicate major section to "Confident But Wrong vs. Uncertain But Useful"
**Rationale**: High-uncertainty responders often think expressing doubt makes answers less valuable, when calibrated uncertainty actually increases utility
**Impact**: Reframes uncertainty as competence signal rather than weakness; reduces pressure to fake certainty

**Decision**: Four-pattern structure for "Making Uncertainty Informative"
**Rationale**: Generic "I'm uncertain" is useless; needed concrete patterns for making uncertainty diagnostic
**Impact**: Converts "I don't know" into actionable information (reveals missing data, competing factors, time dependency, processing state)

**Decision**: Calibrate all guidance to Section 6.2 intent taxonomy
**Rationale**: Appropriate confidence expression depends on question intent—logistical needs binary "confident enough to act," emotional needs warm certainty, diagnostic needs reasoning transparency
**Impact**: Integrates Section 6.3 tightly with intent taxonomy; reinforces that technique selection depends on context

**Decision**: Include "Scenario 5: Previously Confident Answer Now Seems Wrong"
**Rationale**: High-uncertainty responders often feel shame when updating confidence; needed explicit permission and scripts
**Impact**: Frames confidence calibration as strength; provides honorable way to correct overconfident prior claims

**Decision**: Seven specific failure modes with fixes
**Rationale**: Confidence expression has many subtle ways to fail; needed concrete examples of what not to do
**Impact**: Helps readers recognize their own patterns and correct them

### Conceptual Continuity Notes

- Section 6.3 completes the Section 6 framework (6.1 negotiation + 6.2 intent taxonomy + 6.3 confidence expression)
- Builds directly on Section 5.1 provisional commitment language by showing how to calibrate those commitments
- Uses Section 6.2 intent taxonomy to determine which confidence format to use
- References Section 6.1 negotiation for when confidence is too low ("I'm only 40% confident—do you want my uncertain take or should we find better information?")
- Uses established "lossy compression" concept (from SPEC for Section 3.2, used throughout framework)
- Sets up Section 11 (Worked Examples) by providing confidence expression patterns that examples can demonstrate

### Tone/Voice Observations

- Maintained example-rich approach (25+ concrete examples across professional/intimate/casual contexts)
- Used consistent non-pathologizing frame (uncertainty as information, not weakness)
- Balanced responder and questioner perspectives throughout
- Examples show both what works and what fails, with specific reasoning
- Minimal bullet abuse—used prose for conceptual explanations, bullets only for actual lists

### Section Structure Pattern

Each confidence format (numerical/verbal/modal+bounds) includes:

- When this works well (context/intent types)
- Examples in multiple contexts (professional/intimate/casual)
- When this fails (anti-patterns)
- Specific failure modes with fixes

Each "Making Uncertainty Informative" pattern includes:

- Pattern description
- What it accomplishes
- Three concrete examples across contexts

Each scenario script includes:

- Poor approach (what not to do)
- Better approaches (2+ options with reasoning)

### Integration Achievements

- Section 6 framework now complete: Real-time negotiation (6.1) + Intent taxonomy (6.2) + Confidence expression (6.3)
- Confidence expression integrates all prior framework pieces: techniques (4.1), protocols (5.1, 5.2), intent recognition (6.2), negotiation vocabulary (6.1)
- Creates vocabulary for worked examples to reference in Section 11
- Establishes that uncertainty is informative (supports eventual Section 3.2 lossy compression theory)

### Writing Efficiency Notes

- Single-session completion of Section 6.3 (~5,325 words)
- Section 6 fully complete in 2 sessions (Session 7: 6.1 + 6.2, Session 8: 6.3)
- Total Section 6 word count: ~19,025 words (6.1: 6,800 + 6.2: 5,900 + 6.3: 5,325)

### Next Session Recommendations

**Strong recommendation: Section 11 (Worked Examples & Case Studies)**

**Why Section 11 now**:

- Section 6 framework complete—we have everything needed to demonstrate
- Phase 2 third priority (after 5.1 ✅ and 6.2 ✅, which are complete)
- Complete practical toolkit now exists to show in action:
  - Techniques (Section 4.1)
  - Bilateral protocols (Sections 5.1, 5.2)
  - Intent taxonomy (Section 6.2)
  - Real-time negotiation (Section 6.1)
  - Confidence expression (Section 6.3)
- Worked examples will reveal integration gaps and improve framework coherence
- Demonstrates framework is practical, not just theoretical

**What to read for Section 11**:

- SPEC.md Section 11 (10+ examples requirement, before/after redesigns, multiple approach options, failure mode recognition)
- All practical sections (1, 2, 4.1, 5.1, 5.2, 6.1, 6.2, 6.3) for technique/protocol references
- examples-bank.md (canonical examples to expand)
- voice-samples.md (tone continuity)

**Estimated scope**: Large section (~8-10k words for 10+ worked examples showing complete exchanges)

**Alternative paths**:

- Section 3.3 (Three-Layer Communication Model) - Theory section that can now reference extensive practical examples
- Section 7.1 or 7.2 (Intimate Relationships) - Apply framework to high-stakes emotional contexts
- Section 4.2 (Advanced Techniques) - More dimensionality reduction techniques

**Current recommendation**: Section 11. Complete practical framework deserves demonstration through worked examples before adding more sections. This reveals whether framework actually hangs together in real scenarios.

### Current Status

**Section 6 status**: ✅ COMPLETE

- Section 6.1: Real-Time Negotiation - ✅ COMPLETE
- Section 6.2: Question Intent Taxonomy - ✅ COMPLETE
- Section 6.3: Confidence Expression Systems - ✅ COMPLETE

**Completed Sections** (8 total, ~37,625 words):

- Section 1: Core Cognitive Profile ✅
- Section 2: The Communication Mismatch ✅
- Section 4.1: Core Techniques ✅
- Section 5.1: Response Protocols (For High-Uncertainty Responders) ✅
- Section 5.2: Response Protocols (For Questioners) ✅
- Section 6.1: Real-Time Negotiation ✅
- Section 6.2: Question Intent Taxonomy ✅
- Section 6.3: Confidence Expression Systems ✅

**Phase 2 progress**: 2 of 3 priority sections complete (5.1 ✅, 6.2 ✅), Section 11 ready to write

**Next up**: Section 11 (Worked Examples) strongly recommended to demonstrate complete framework before expanding further.

---

## Session 13: Write Section 4.2 (Advanced Techniques)

**Date**: 2026-01-22
**Session Type**: Writing New Section
**Agent**: Antigravity

### What Was Done

1. Reviewed `HANDOVER.md` and `SPEC.md`.
2. Wrote **Section 4.2: Advanced Techniques** (`content/section-04-2-advanced-techniques.md`).
3. Defined 6 new meta-parameter techniques: Scope-Locking, Reversibility Framing, Confidence Calibration Requests, Intent Declaration, Acceptable Error Tolerance, Iteration Permission.
4. Updated `SPEC.md` to mark 4.2 as Complete.

### Key Decisions Made

**Decision**: Use "Iteration Permission" as the 6th technique.

- **Rationale**: The "blank page problem" is a variation of "Answer = Commitment" paralysis.
- **Impact**: Provides a specific tool for getting started, complementing the refinement tools.

**Decision**: Numbering Continuation (Technique 7-12)

- **Rationale**: Continues from Section 4.1's core six (1-6).
- **Impact**: Creates a unified 12-technique toolkit across Section 4.

### Content Structure Used

Followed the rigorous template from Section 4.1: Name, Mechanism, Examples (Pro/Int/Cas), When to Use, Failure Modes.

### Conceptual Continuity Notes

- **"Risk-detection system"**: Used in Reversibility Framing to explain why the brain freezes.
- **"Existential weight"**: Used in Scope-Locking to explain the burden of infinite-time answers.

### Next Session Recommendations

**Recommendation**: The "Question Design" toolkit (Section 4) is now robust (12 techniques). The logical next step is **Section 4.3: When to Use Which Technique** (decision tree/guide) OR moving to **Section 9: Self-Advocacy** if we want to switch to the responder's perspective again. Given the extensive toolkit, Section 4.3 would be valuable to prevent analysis paralysis in choosing a technique.

---

## Session 14: Write Section 4.3 (Technique Selection)

**Date**: 2026-01-22
**Session Type**: Writing New Section
**Agent**: Antigravity

### What Was Done

1. Wrote **Section 4.3: When to Use Which Technique** (`content/section-04-3-technique-selection.md`).
2. Created a "Diagnostic Map" matching 5 common symptoms (Paralysis, Rambling, Defensiveness, Info-Loop, Role Conflict) to 12 techniques.
3. Added a troubleshooting guide ("If X fails, try Y").
4. Defined "Technique Stacking" with examples.

### Key Decisions Made

**Decision**: Frame as "Symptom Diagnosis" rather than "Technique Catalog".

- **Rationale**: In real-time conversation, you notice the failure mode (silence, anger) first.
- **Impact**: Makes the section actionable under pressure.

**Decision**: Include "Technique Stacking".

- **Rationale**: Advanced users need to know how to combine tools (e.g. Safety + Focus + Action) for complex problems.

### Next Session Recommendations

**Recommendation**: **Section 9: For High-Uncertainty Individuals**. Now that the Question Design toolkit (Part II) is complete, switch to the Responder's side (Part IV) to give them self-advocacy tools. This balances the framework.

---

## Session 15: Write Section 9 (Self-Advocacy)

**Date**: 2026-01-22
**Session Type**: Writing New Section
**Agent**: Antigravity

### What Was Done

1. Wrote **Section 9: Self-Advocacy Toolkit** (`content/section-09-self-advocacy.md`).
2. Created scripts for "Explaining the Style" (The High-Resolution metaphor).
3. Created "Real-Time Restructuring Requests" tables (Don't say "Bind Domain", Say "Are you asking logistically?").
4. Defined "Energy Management" (The Amputation Budget).

### Key Decisions Made

**Decision**: Use the "User Manual" metaphor.

- **Rationale**: Frames the issue as an input requirement, not a defect.
- **Impact**: Reduces shame and defensiveness.

**Decision**: Translate jargon to natural language.

- **Rationale**: Responders can't ask their boss to "Grant Uncertainty Permission." They need normal English equivalents.

### Next Session Recommendations

**Recommendation**: **Section 10: Interpretation Guide**. We have empowered the Questioner (Part II) and the Responder (Part IV - Sec 9). Now we need to help the Questioner *interpret* the signals (Part IV - Sec 10).

---

## Session 16: Write Section 10 (Interpretation Guide)

**Date**: 2026-01-22
**Session Type**: Writing New Section
**Agent**: Antigravity

### What Was Done

1. Wrote **Section 10: Interpretation Guide** (`content/section-10-interpretation-guide.md`).
2. Created the "Signal Interpretation Dictionary" (Silence = Loading, Hedging = Calibration).
3. Defined "Patience Calibration" (The Three-Second Rule).
4. Provided intervention criteria for "Stuck vs. Unwilling."

### Key Decisions Made

**Decision**: Reframe "Panic" as "System Overload."

- **Rationale**: Removes the moral judgment ("they are being dramatic") and replaces it with a mechanical one ("capacity exceeded").
- **Impact**: Encourages helpful intervention (lowering load) rather than frustration.

### Next Session Recommendations

**Recommendation**: **Section 11: Worked Examples**. We now have the complete theoretical and practical toolkit (Sections 1, 2, 4, 5, 6, 9, 10). It is time to show it all working together in full-scale dialogues.

---

## Sessions 16.5-16.9: Gemini Content Sprint (Unlogged)

**Date**: 2026-01-22
**Agent**: Gemini (external)
**Note**: These sessions were not logged in DEVLOG but produced significant content.

### What Was Done

1. Wrote **Section 11: Worked Examples** (10 examples across 4 categories)
2. Wrote **Section 3.2** (Information Theory) and **Section 3.3** (Game Theory/Signaling)
3. Wrote **Section 7** (Intimate Relationships) - all subsections (7.1, 7.2, 7.3)
4. Wrote **Section 8** (Professional Contexts) - all subsections (8.1, 8.2)
5. Updated SPEC.md to mark these sections complete

### Content Quality Notes

All Gemini-written sections maintain project voice and follow established templates:
- Section 11 uses consistent before/after format with internal trace explanations
- Section 3 introduces "lossy compression" and three-layer model with strong examples
- Sections 7-8 apply framework to specific contexts with practical protocols
- All use canonical key phrases ("amputates uncertainty," "structured collapse")

---

## Session 17: Audit & Handover Update

**Date**: 2026-01-22
**Session Type**: Audit/Review
**Agent**: Claude Code (Opus 4.5)

### What Was Done

1. Ran onboarding protocol per HANDOVER.md instructions
2. Discovered Section 11 already written by Gemini (unlisted in DEVLOG)
3. Audited all content files to discover full project state
4. Confirmed 16 major sections complete (~50,000+ words)
5. Updated workflow files:
   - SPEC.md: Verified Section 11 status as Complete
   - HANDOVER.md: Rewrote to reflect actual project state
   - DEVLOG.md: Added Gemini sessions retroactively + this entry

### Key Findings

**Project is essentially complete.** Core framework covers:
- Understanding the pattern (Sections 1-2)
- Theoretical grounding (Sections 3.2, 3.3)
- Question design toolkit (Sections 4.1, 4.2, 4.3)
- Bilateral protocols (Sections 5.1, 5.2)
- Shared protocols (Sections 6.1, 6.2, 6.3)
- Context applications (Sections 7, 8)
- Self-help tools (Sections 9.1, 10.1)
- Worked examples (Section 11)

**Remaining work is optional polish**:
- Theoretical stubs (3.1, 3.4)
- Practice exercises (9.2, 10.2)
- Advanced topics (12, 13, 14)
- Appendices (A, B, C)

### Recommendations for Next Session

| Path | Description | When to Choose |
|------|-------------|----------------|
| **Compilation** | Merge sections into single document, cross-reference check | Want finished product |
| **Practice Exercises** | Write 9.2 and 10.2 | Want workbook format |
| **Edge Cases** | Write Section 12 | Want intellectual completeness |
| **Theory** | Complete 3.1 and 3.4 | Want academic rigor |

### Current Status

**Completed**: 16 major sections, ~50,000+ words
**Remaining**: 8 optional sections/appendices
**Phase**: Core complete, entering polish/expansion phase

---

## Session 18: Complete Theory Sections (3.1 and 3.4)

**Date**: 2026-01-22
**Session Type**: Writing New Content
**Agent**: Claude Code (Opus 4.5)

### What Was Done

1. Read onboarding protocol and all required files
2. Wrote **Section 3.1: Neurodevelopmental Perspective** (~850 words)
   - Detail-focused processing and "weak central coherence"
   - Executive function load and working memory constraints
   - Theory of Mind and deliberate intent inference
   - Non-pathologizing frame maintained throughout
3. Wrote **Section 3.4: Linguistic/NLP Perspective** (~900 words)
   - Semantic content vs. pragmatic intent
   - Presupposition and scope control
   - Gricean maxims and conversational implicature
   - Speech acts: what questions actually DO
4. Updated workflow files:
   - SPEC.md: Marked 3.1 and 3.4 as Complete
   - This DEVLOG entry
   - HANDOVER.md (next)

### Key Decisions Made

**Decision**: Frame neurodevelopmental patterns as explanatory, not diagnostic
- **Rationale**: Maintains non-pathologizing philosophy; avoids "you have X condition" framing
- **Impact**: Readers can understand cognitive mechanics without self-diagnosis pressure

**Decision**: Connect cognitive patterns directly to framework techniques
- **Rationale**: Theory should explain WHY techniques work, not just describe mechanisms in isolation
- **Impact**: Section 3.1 explicitly maps detail-focus → why Domain-Binding helps; executive load → why Forced-Slice reduces burden

**Decision**: Use Gricean maxims to explain high-uncertainty "Quality obsession"
- **Rationale**: Linguistic theory provides precise vocabulary for what responders do (over-optimize Quality at expense of Quantity/Manner)
- **Impact**: Reframes "lossy compression is not lying" in formal linguistic terms

**Decision**: Include speech act theory
- **Rationale**: Questions DO things beyond asking; high-uncertainty individuals see multiple possible speech acts
- **Impact**: Explains why specifying intent (Context-Framing, Explicit Stakes) works—it names the speech act being performed

### Conceptual Continuity Notes

**Section 3.1 establishes**:
- Detail-focused processing explains why summaries require active construction
- Executive function load explains why "just answer quickly" adds burden rather than reducing it
- Deliberate ToM explains why clarifying questions feel necessary, not pedantic

**Section 3.4 establishes**:
- Semantic/pragmatic split explains "which question are you actually asking?"
- Presupposition management explains why some questions feel trap-like
- Gricean maxims explain over-hedging as Quality maximization
- Speech acts explain why intent specification reduces load

**Cross-references achieved**:
- Both sections reference Section 4.1 techniques and explain WHY they work
- Both sections connect to Section 2's "structured collapse" concept
- Section 3 theoretical framework now complete (3.1, 3.2, 3.3, 3.4 all written)

### Tone/Voice Observations

- Maintained non-pathologizing frame ("difference in cognitive organization, not deficit")
- Connected theory directly to practical implications
- Used clear structure: mechanism → practical implication → how techniques address this
- Avoided academic jargon unless it serves clarity

### Current Status

**Section 3 status**: ✅ COMPLETE
- Section 3.1: Neurodevelopmental Perspective ✅
- Section 3.2: Information Theory Perspective ✅ (previous session)
- Section 3.3: Game Theory & Signaling ✅ (previous session)
- Section 3.4: Linguistic/NLP Perspective ✅

**Completed Sections**: 18 total
- Part I: Sections 1, 2 ✅
- Part II (Theory): Sections 3.1, 3.2, 3.3, 3.4 ✅ (ALL COMPLETE)
- Part II (Techniques): Sections 4.1, 4.2, 4.3 ✅
- Part III: Sections 5.1, 5.2, 6.1, 6.2, 6.3 ✅
- Part IV: Sections 7, 8, 9.1, 10.1, 11 ✅

**Remaining work** (optional polish):
- Practice exercises (9.2, 10.2)
- Edge Cases (Section 12)
- Cultural Factors (Section 13)
- Research/Reading (Section 14)
- Appendices (A, B, C)

**Overall progress**: Theoretical framework now complete. All major content sections written.

---

## Session 19: Write Section 12 (Edge Cases & Complications)

**Date**: 2026-01-22
**Session Type**: Writing New Section
**Agent**: Claude Code (Opus 4.5)

### What Was Done

1. Read onboarding protocol and required files
2. Wrote **Section 12: Edge Cases & Complications** (~3,200 words)
   - When uncertainty IS the problem (commitment avoidance)
   - Cognitive style vs anxiety disorders
   - Trauma responses vs information processing style
   - When simplification is truly necessary vs accommodatable
   - Red flags and when to seek professional help
   - Meta-problem: uncertainty about which category you're in
3. Updated workflow files:
   - SPEC.md: Marked Section 12 as Complete
   - This DEVLOG entry
   - HANDOVER.md (next)

### Key Decisions Made

**Decision**: Structure around distinguishing genuine cognitive style from other patterns
- **Rationale**: The framework assumes high-uncertainty processing is a valid cognitive style, but that assumption isn't always correct. Readers need tools to identify when the framework applies and when it doesn't.
- **Impact**: Section provides concrete markers for distinguishing cognitive style from commitment avoidance, anxiety disorders, and trauma responses.

**Decision**: Include "The Key Test" for commitment avoidance
- **Rationale**: The most practical distinction is whether structure enables commitment or just shifts uncertainty elsewhere.
- **Impact**: Gives readers a concrete diagnostic: "Does providing structure and boundaries enable commitment, or does it just shift the uncertainty?"

**Decision**: Distinguish cognitive style from anxiety by function and origin
- **Rationale**: They can look identical from outside but function entirely differently (engaging with complexity vs defending against threat).
- **Impact**: Table of markers helps readers identify physical/content/response patterns that distinguish the two.

**Decision**: Address trauma responses as separate category
- **Rationale**: Trauma creates question-difficulty that functions completely differently from processing style (hypervigilance about safety, not complexity engagement).
- **Impact**: Provides "relational test"—trauma responses are often relationship-specific while cognitive style is relatively consistent.

**Decision**: Include "When Simplification Is Truly Necessary" section
- **Rationale**: Framework generally treats forced simplification as problematic, but emergencies/legal contexts/resource constraints may legitimately require it.
- **Impact**: Acknowledges when the framework's usual advice doesn't apply; provides navigation for those situations.

**Decision**: Add "Red Flags and When to Seek Help" with concrete criteria
- **Rationale**: Framework is communication protocols, not therapy. Important to name when professional support is needed.
- **Impact**: Creates clear boundary for framework's scope; encourages appropriate help-seeking.

**Decision**: Conclude with meta-problem acknowledgment
- **Rationale**: Many readers will be uncertain which category they're in—that uncertainty is itself informative.
- **Impact**: Provides practical approach: try the framework, observe what shifts, adjust based on results.

### Conceptual Continuity Notes

**Key distinctions established**:
- Processing vs protection (cognitive style engages with complexity; avoidance/anxiety/trauma defend against perceived threat)
- Structure enables vs structure shifts (key test for commitment avoidance)
- Relationship-specific vs consistent (test for trauma patterns)
- Information processing vs threat detection (cognitive style vs anxiety)

**Framework scope clarified**:
- Applies when: uncertainty reflects actual information processing, structure enables commitment
- May not apply when: uncertainty serves protective functions, structure doesn't help
- Not sufficient when: significant distress, clinical factors primary, patterns worsen despite effort

### Tone/Voice Observations

- Maintained non-pathologizing frame while acknowledging that sometimes patterns ARE problematic
- Used concrete markers and tests rather than abstract descriptions
- Avoided diagnostic language while being clear about when professional help is needed
- Acknowledged complexity without creating more paralysis about which category one is in

### Current Status

**Completed Sections**: 19 total
- Part I: Sections 1, 2 ✅
- Part II (Theory): Sections 3.1, 3.2, 3.3, 3.4 ✅
- Part II (Techniques): Sections 4.1, 4.2, 4.3 ✅
- Part III: Sections 5.1, 5.2, 6.1, 6.2, 6.3 ✅
- Part IV: Sections 7, 8, 9.1, 10.1, 11 ✅
- Part V: Section 12 ✅

**Remaining work** (optional):
- Practice exercises (9.2, 10.2)
- Cultural Factors (Section 13)
- Research/Reading (Section 14)
- Appendices (A, B, C)

**Overall progress**: Edge cases section complete. Framework now addresses both when it applies and when it doesn't.

---

## Session 20: Editorial Verification Pass - Section 7

**Date**: 2026-07-03
**Session Type**: Editorial verification / polish
**Agent**: Codex Desktop (GPT-5)

### What Was Done

1. Continued the chapter-by-chapter editorial verification pass from the handover.
2. Compared **Section 7: Intimate Relationships Layer** against the Section 7.1-7.3 slice in `workflow/SPEC.md`.
3. Lightly revised `content/section-07-intimate-relationships.md` to cover missing spec requirements:
   - Added the meta-problem: difficulty answering can be read as deprioritization.
   - Expanded trust erosion from a single paragraph into concrete relationship mechanisms.
   - Added criteria distinguishing legitimate "I don't know yet" from avoidant non-answering.
   - Added calibration ritual, repair script, and a customizable relationship protocol template.
4. Regenerated build artifacts with `python build.py`.

### Key Decisions Made

**Decision**: Keep the pass editorial rather than structural.

- **Rationale**: Section 7 already had the right concept and voice. The gap was coverage: several success criteria were present only implicitly.
- **Impact**: The section now satisfies the spec without changing its basic shape or adding a new chapter architecture.

**Decision**: Soften overstatements about intimate relationships.

- **Rationale**: The original opening and summary made the relationship layer sound universally dominant. The framework is stronger if it says "often" and explains when Layer 2 must be protected first.
- **Impact**: More precise, less absolute, and more consistent with the document's intellectual honesty.

### Verification

- `python build.py`: Markdown and sections ZIP regenerated successfully.
- HTML/PDF generation: Failed for expected environment reason, `pandoc` is not installed.
- `git diff --check`: No whitespace errors; only CRLF normalization warnings from Git.

### Current Status

**Editorial verification completed**:

- Sections 1-6: completed in previous session
- Section 7: completed this session

**Next up**:

- Resume verification with `content/section-08-professional-contexts.md`, comparing against the Section 8 slice in `workflow/SPEC.md`.

---

## Session 21: Editorial Verification Pass - Section 8

**Date**: 2026-07-03
**Session Type**: Editorial verification / polish
**Agent**: Codex Desktop (GPT-5)

### What Was Done

1. Continued the chapter-by-chapter editorial verification pass.
2. Compared **Section 8: Professional & Social Contexts** against the Section 8.1-8.2 slice in `workflow/SPEC.md`.
3. Revised `content/section-08-professional-contexts.md` to fix defects and complete spec coverage:
   - Removed stray line-number artifacts (`64:` and `87:`).
   - Expanded professional friction examples to cover stakeholder reassurance, performance reviews, collaborative decision-making, and formal contexts such as court/compliance/audit.
   - Added adaptation strategies for organizational trust, structural support for complexity, and deciding when full explanation is worth the cost.
   - Tightened the professional framing from "masking uncertainty" to "making uncertainty actionable."
4. Regenerated build artifacts with `python build.py`.

### Key Decisions Made

**Decision**: Treat Section 8 as a coverage repair rather than a line edit.

- **Rationale**: The original section had the right thesis but missed multiple explicit SPEC requirements. Small sentence edits would not cover stakeholder reassurance, court testimony/formal contexts, organizational trust, structural support, or cost-benefit analysis for explanation depth.
- **Impact**: The section is longer but now functions as a usable professional-context guide rather than a short concept sketch.

**Decision**: Preserve uncertainty in formal contexts instead of applying the executive-summary pattern universally.

- **Rationale**: Court testimony, compliance, audit, safety, and similar settings legitimately require precision over reassurance.
- **Impact**: The section now distinguishes appropriate business compression from contexts where compression can become distortion.

### Verification

- `python build.py`: Markdown and sections ZIP regenerated successfully.
- HTML/PDF generation: Failed for expected environment reason, `pandoc` is not installed.
- `git diff --check`: No whitespace errors; only CRLF normalization warnings from Git.

### Current Status

**Editorial verification completed**:

- Sections 1-6: completed in previous session
- Section 7: completed in Session 20
- Section 8: completed this session

**Next up**:

- Resume verification with `content/section-09-self-advocacy.md`, comparing against the Section 9 slice in `workflow/SPEC.md`.

---

## Session 22: Editorial Verification Pass - Section 9

**Date**: 2026-07-03
**Session Type**: Editorial verification / polish plus missing subsection completion
**Agent**: Codex Desktop (GPT-5)

### What Was Done

1. Continued the chapter-by-chapter editorial verification pass.
2. Compared **Section 9: Self-Advocacy Toolkit** against the Section 9.1-9.2 slice in `workflow/SPEC.md`.
3. Reworked `content/section-09-self-advocacy.md` to complete the full Section 9 requirements:
   - Expanded self-explanation scripts for bosses, partners, and casual contexts.
   - Added push-vs-adapt decision criteria.
   - Expanded energy management from a short list into a practical "amputation budget" strategy.
   - Added relationship-building habits for making uncertainty acceptable.
   - Wrote the previously missing **Section 9.2: Practice Exercises** covering forced-slice calibration, speed drills, meta-communication rehearsal, role-switching, and push-or-adapt review.
4. Updated `workflow/SPEC.md` to mark Section 9.2 complete.
5. Regenerated build artifacts with `python build.py`.

### Key Decisions Made

**Decision**: Complete Section 9.2 during the verification pass.

- **Rationale**: This was not just a polish issue. The SPEC explicitly listed Section 9.2 as "Needs writing," and the current Section 9 file only covered the self-advocacy toolkit.
- **Impact**: Section 9 is now a complete implementation guide rather than a partial self-explanation script.

**Decision**: Add a push-vs-adapt rule instead of only adding more scripts.

- **Rationale**: The most important self-advocacy skill is deciding when to request structure and when to provide a compressed answer.
- **Impact**: The section now prevents self-advocacy from becoming automatic resistance to every unstructured question.

### Verification

- `python build.py`: Markdown and sections ZIP regenerated successfully.
- HTML/PDF generation: Failed for expected environment reason, `pandoc` is not installed.
- `git diff --check`: No whitespace errors; only CRLF normalization warnings from Git.

### Current Status

**Editorial verification completed**:

- Sections 1-6: completed in previous session
- Section 7: completed in Session 20
- Section 8: completed in Session 21
- Section 9: completed this session

**Next up**:

- Resume verification with `content/section-10-interpretation-guide.md`, comparing against the Section 10 slice in `workflow/SPEC.md`.

---

## Session 23: Editorial Verification Pass - Section 10

**Date**: 2026-07-03
**Session Type**: Editorial verification / polish plus missing subsection completion
**Agent**: Codex Desktop (GPT-5)

### What Was Done

1. Continued the chapter-by-chapter editorial verification pass.
2. Compared **Section 10: Interpretation Guide for Questioners** against the Section 10.1-10.2 slice in `workflow/SPEC.md`.
3. Reworked `content/section-10-interpretation-guide.md` to complete the full Section 10 requirements:
   - Tightened the opening and reframes to avoid overly mechanical or pathologizing language.
   - Expanded signal recognition for processing silence, hedging, too much detail, and defensive explanation.
   - Added distinctions for appropriate complexity vs. unhelpful over-expansion, and evasion vs. refusing false certainty.
   - Expanded patience calibration into wait / restructure / accept-uncertainty decision guidance.
   - Wrote the previously missing **Section 10.2: Question-Design Practice** covering bounded-question rewrites, intent declaration practice, emotional vs. analytical recognition, patience vs. enabling drills, and low-load follow-ups.
4. Updated `workflow/SPEC.md` to mark Section 10.2 complete.
5. Regenerated build artifacts with `python build.py`.

### Key Decisions Made

**Decision**: Complete Section 10.2 during the verification pass.

- **Rationale**: Like Section 9.2, the SPEC explicitly listed Section 10.2 as "Needs writing," while the content file only contained the interpretation guide.
- **Impact**: Section 10 now serves both as an interpretation guide and a practice guide for questioners.

**Decision**: Replace the "system loading / CPU / RAM" metaphor with plainer interpretation language.

- **Rationale**: The metaphor was vivid but risked making people sound like machines. The project voice works better when it stays practical and non-pathologizing.
- **Impact**: The section keeps the same signal-reading function with more human, direct language.

### Verification

- `python build.py`: Markdown and sections ZIP regenerated successfully.
- HTML/PDF generation: Failed for expected environment reason, `pandoc` is not installed.
- `git diff --check`: No whitespace errors; only CRLF normalization warnings from Git.

### Current Status

**Editorial verification completed**:

- Sections 1-6: completed in previous session
- Section 7: completed in Session 20
- Section 8: completed in Session 21
- Section 9: completed in Session 22
- Section 10: completed this session

**Next up**:

- Resume verification with `content/section-11-worked-examples.md`, comparing against the Section 11 slice in `workflow/SPEC.md`.

---

## Session 24: Editorial Verification Pass - Section 11

**Date**: 2026-07-03
**Session Type**: Editorial verification / polish
**Agent**: Codex Desktop (GPT-5)

### What Was Done

1. Continued the chapter-by-chapter editorial verification pass.
2. Compared **Section 11: Worked Examples & Case Studies** against the Section 11 slice in `workflow/SPEC.md`.
3. Verified the section has 10 worked examples across professional, intimate, casual, and breakdown/recovery categories.
4. Lightly revised `content/section-11-worked-examples.md`:
   - Fixed typo/artifact issues in Example 2 and Example 7.
   - Added a compact **Pattern Index: Choosing the Move** to make the "multiple approach options" and cross-context success patterns explicit.
5. Regenerated build artifacts with `python build.py`.

### Key Decisions Made

**Decision**: Keep Section 11 as a light polish pass.

- **Rationale**: The section already met the major SPEC requirements: 10 examples, before/after exchanges, multiple relationship types, and recovery examples.
- **Impact**: The edit improves usability and cleanup without disturbing the existing examples.

**Decision**: Add a pattern index rather than more examples.

- **Rationale**: The SPEC asks readers to see common scenarios with multiple approach options. The existing examples showed this implicitly, but a short chooser makes it easier to apply.
- **Impact**: Readers now have a bridge from individual case studies to reusable decision patterns.

### Verification

- `python build.py`: Markdown and sections ZIP regenerated successfully.
- HTML/PDF generation: Failed for expected environment reason, `pandoc` is not installed.
- `git diff --check`: No whitespace errors; only CRLF normalization warnings from Git.

### Current Status

**Editorial verification completed**:

- Sections 1-6: completed in previous session
- Section 7: completed in Session 20
- Section 8: completed in Session 21
- Section 9: completed in Session 22
- Section 10: completed in Session 23
- Section 11: completed this session

**Next up**:

- Resume verification with `content/section-12-edge-cases.md`, comparing against the Section 12 slice in `workflow/SPEC.md`.

---

## Session 25: Editorial Verification Pass - Section 12

**Date**: 2026-07-03
**Session Type**: Editorial verification / polish
**Agent**: Codex Desktop (GPT-5)

### What Was Done

1. Completed the chapter-by-chapter editorial verification pass requested in the handover.
2. Compared **Section 12: Edge Cases & Complications** against the Section 12 slice in `workflow/SPEC.md`.
3. Verified Section 12 covers the required edge cases:
   - When uncertainty itself is the problem, including commitment avoidance.
   - Cognitive style vs. anxiety patterns.
   - Trauma responses vs. information-processing style.
   - When simplification is truly necessary vs. merely demanded.
4. Lightly revised `content/section-12-edge-cases.md`:
   - Softened the opening claim so it does not imply the framework can always cleanly exclude symptom, avoidance, or dysfunction.
   - Removed a stray line-number artifact in the simplification section.
5. Regenerated build artifacts with `python build.py`.

### Key Decisions Made

**Decision**: Keep Section 12 as a minimal cleanup pass.

- **Rationale**: The section already met the SPEC requirements and had strong scope boundaries around anxiety, trauma, avoidance, and professional support.
- **Impact**: The edits reduce overstatement and remove an artifact without changing the section structure.

### Verification

- `python build.py`: Markdown and sections ZIP regenerated successfully.
- HTML/PDF generation: Failed for expected environment reason, `pandoc` is not installed.
- `git diff --check`: No whitespace errors; only CRLF normalization warnings from Git.

### Current Status

**Editorial verification completed**:

- Sections 1-6: completed in previous session
- Section 7: completed in Session 20
- Section 8: completed in Session 21
- Section 9: completed in Session 22
- Section 10: completed in Session 23
- Section 11: completed in Session 24
- Section 12: completed this session

**Next up**:

- The handover verification queue is complete. Decide whether to stop, commit the current pass, or continue into optional placeholder sections and appendices.

---

## Session 26: Write Section 13 (Cultural & Contextual Factors)

**Date**: 2026-07-20
**Session Type**: Writing New Section
**Agent**: Claude Code - Opus 4.8

### What Was Done

1. Oriented via /start: onboarding, HANDOVER, DEVLOG, then audited SPEC.md for unfinished items. Confirmed Sections 1-12 all Complete; remaining work is Section 13 (Placeholder), Section 14 (Placeholder), and Appendices A/B/C (Needs creation).
2. Wrote **Section 13: Cultural & Contextual Factors** (~2,800 words), `content/section-13-cultural-contextual-factors.md`. Structured to match its Part V sibling (Section 12): "What This Section Is For" opening, numbered subsections, closing summary.
   - 13.1 High-context vs. low-context cultures (Hall) — including the counterintuitive point that high-context cultures can *also* penalize the style, by misreading epistemic hedging as strategic indirection.
   - 13.2 Gender socialization effects — the double-bind / asymmetric penalty on hedging; two socialization-driven failure modes (under-collapsing vs. over-collapsing).
   - 13.3 Professional domain expectations — medicine (structured uncertainty), law (adversarial collapse + two registers), engineering (bounded precision); the cross-domain trap.
   - 13.4 Digital communication — what async text strips (processing signal, tone, real-time negotiation, permanence) and what it gives back (time, editability, native structure).
3. Registered `section-13-cultural-contextual-factors.md` in `build.py` SECTION_ORDER (hardcoded list; new files are silently skipped otherwise).
4. Marked Section 13 Complete in `workflow/SPEC.md`.
5. Regenerated build artifacts.

### Key Decisions Made

**Decision**: Added an explicit "Tendencies, Not Verdicts" preamble before the culture/gender material.

- **Rationale**: Sections on culture and gender socialization risk stereotyping. The intellectually honest framing is population-level tendencies with large individual variation; the framework operates on the individual regardless. This also matches the project's non-pathologizing, non-tribal voice.
- **Impact**: Lets the section discuss real contextual variables without reading as essentialist. Worth preserving if the section is revised.

**Decision**: Framed the whole section as "context sets the price, not the pattern."

- **Rationale**: Keeps continuity with the core thesis — the cognitive style is invariant; only the social/reputational cost of expressing it changes. Avoids implying culture/gender/domain *cause* the style.
- **Impact**: Gives the section a single through-line and a memorable summary handle.

**Decision**: Used law's "two registers" (courtroom vs. memo) as the generalizable lesson.

- **Rationale**: Reinforces that keeping dimensional thinking internal and delivering a collapse is register-matching, not dishonesty — consistent with "structured collapse" and "lossy compression is not lying."

### Conceptual Continuity Notes

- Key phrases used: "amputates uncertainty," "structured collapse," "reduce dimensionality," "communicable stability, not perfect truth," three-layer model (Section 3.3).
- Cross-references: Section 3.3 (three layers), 4 (techniques), 5.1/5.2 (responder/questioner protocols, intent declaration), 6.1 (real-time negotiation), 6.3 (confidence expression), 8.1 (false confidence), and a closing pointer to Section 12 (style vs. anxiety/trauma/avoidance).
- No new canonical before/after examples added to examples-bank.md — the section's examples are context-illustrations rather than reusable canonical pairs.

### Verification

- `python build.py`: markdown + sections ZIP regenerated (18 sections, ~49,821 words). HTML/PDF failed only for the expected missing `pandoc`.
- `git diff --check`: clean (no whitespace errors).
- Confirmed Section 13 present in compiled `build/simple-questions-framework.md`.

### Current Status

**Completed Sections**: 1-13 all Complete.

**Remaining optional/back-matter** (per SPEC audit):
- Section 14: Research Connections & Further Reading — Placeholder
- Appendix A: Quick Reference Cards — Needs creation
- Appendix B: Customization Templates — Needs creation
- Appendix C: Glossary — Needs creation (now unblocked; depended on "all sections complete")

**Next up**:
- Appendix A (Quick Reference Cards) is the highest utility-per-effort remaining item — pure distillation of finished sections. Section 14 and the other appendices are lower priority. Or declare content-complete and defer 14/appendices explicitly.

---

## Session 26 (cont.): Write Appendix A (Quick Reference Cards)

**Date**: 2026-07-20
**Session Type**: Writing New Section (back-matter / distillation)
**Agent**: Claude Code - Opus 4.8

### What Was Done

1. Committed Section 13 (`564d82f`) before starting.
2. Extracted exact technique/protocol names and canonical phrasings from the source sections (4.1, 4.2, 5.1, 5.2, 6.1, 6.3, 6.2 intent types) rather than reconstructing from memory — accuracy of the distilled names is the whole point of a reference card.
3. Wrote **Appendix A: Quick Reference Cards** (~1,500 words), `content/appendix-a-quick-reference.md`, delivering all four SPEC items:
   - **Card 1 — Questioner Guide**: intent declaration + 5 intent types, the 6 core techniques (table), stall/expand fixes, "don't" list.
   - **Card 2 — Responder Guide**: signal-don't-apologize, provisional commitment, confidence expression, restructuring requests, push-back-vs-lossy strategic choice, required-simplification script.
   - **Card 3 — Common Patterns Cheat Sheet**: the 6 additional techniques (4.2, table), a symptom→move lookup table, the 5 key phrases, the technique-stack example.
   - **Card 4 — Protocol Negotiation Flowchart**: ASCII decision trees for responder ("can't collapse") and questioner ("stalled response") paths, plus the meta-escape hatch. Used ASCII rather than mermaid because the pandoc build has no mermaid filter.
4. Registered `appendix-a-quick-reference.md` in `build.py` SECTION_ORDER and marked Appendix A Complete in `workflow/SPEC.md`.
5. Rebuilt.

### Key Decisions Made

**Decision**: Reference cards are deliberately table/bullet-dense, breaking the project's usual "minimal bullet abuse" rule.

- **Rationale**: A quick-reference card is a lookup artifact, not prose. Dense tables are the *correct* format here; flowing paragraphs would defeat the purpose. This is the documented exception, not voice drift.
- **Impact**: If a future editor "fixes" the bullets into prose, they've misread the intent. Noted here to prevent that.

**Decision**: Every card points back to its source section ("Full detail: Section X").

- **Rationale**: Keeps the cards honestly positioned as compression, not replacement, and gives the reader a path to the reasoning/failure-modes the card omits.

**Decision**: ASCII flowcharts, not mermaid.

- **Rationale**: `build.py` runs plain pandoc with no diagram filter; mermaid fences would render as raw code blocks in HTML/PDF. ASCII trees render everywhere.

### Verification

- `python build.py`: markdown + ZIP regenerated (19 sections, ~51,341 words). HTML/PDF still fail only for the expected missing `pandoc`.
- `git diff --check`: clean.
- Confirmed Appendix A present in compiled `build/simple-questions-framework.md`.

### Current Status

**Completed**: Sections 1-13 + Appendix A.

**Remaining optional back-matter**:
- Section 14: Research Connections & Further Reading — Placeholder (needs real citations; fabrication risk)
- Appendix B: Customization Templates — Needs creation
- Appendix C: Glossary — Needs creation

**Next up**: Appendix C (Glossary) is now the natural companion to Appendix A and similarly low-risk. Appendix B (fillable templates) and Section 14 remain. Or declare content-complete.
