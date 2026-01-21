# Workflow Wisdom: AI-Assisted Non-Coding Projects

## Purpose

This document captures lessons learned and patterns discovered while developing a large-scale writing project with AI assistance. It generalizes insights that may apply to other non-coding collaborative projects (books, frameworks, research, documentation).

---

## The Core Challenge

**Problem**: Writing a 100+ page structured document across multiple AI sessions over weeks/months

**Risks**:
- Conceptual drift (same term means different things in different sections)
- Tone drift (voice changes across sessions or AI tools)
- Inconsistent examples (same scenario used differently)
- Lost context (next session doesn't know what previous session decided)
- Dependency confusion (writing Section 5 before Section 2, which it depends on)

**Solution**: Adapt sprint-based development workflow from software projects to writing projects

---

## Key Insight: Treat Writing Like Code

The same problems that plague large codebases without version control and documentation also plague large writing projects:
- How do you maintain consistency?
- How do you track decisions?
- How do you enable collaboration (human-AI or human-human)?
- How do you know what to work on next?

The same solutions work too:
- Specification documents (SPEC.md)
- Session logs (DEVLOG.md)
- Style guides (voice-samples.md)
- Canonical references (examples-bank.md)
- Onboarding docs (onboarding.md)

---

## The Five-Document Foundation

### 1. SPEC.md - The "What to Build" Document

**Purpose**: Complete outline with success criteria, dependencies, and writing order

**Key Elements**:
- Section-by-section outline with status tracking
- **Success criteria** for each section (what should reader be able to DO afterward?)
- **Dependency map** (which sections need others before writing)
- Recommended writing order with phases
- Document-wide consistency requirements (key phrases, tone standards)

**Why This Matters**:
- Prevents "what should I work on next?" paralysis
- Ensures sections are written in logical dependency order
- Makes success measurable (not just "write Section 3" but "reader should be able to X")
- Allows any session to pick up where previous left off

**Template Pattern**:
```markdown
### Section X: Title
**Status**: Needs writing / In progress / Complete
**Dependencies**: Sections Y, Z (must be written first)
**Success Criteria**: Reader can:
- Specific action 1
- Specific action 2

**Content Requirements**:
- Specific elements that must appear
- Structure to follow
```

---

### 2. onboarding.md - The Universal Agent Entry Point

**Purpose**: Philosophy, tone, writing standards, and session-specific instructions

**Key Elements**:
- Project overview (what problem this solves, core solution)
- Document philosophy (what this is and is NOT)
- Tone and style guidelines
- Quality standards with good/bad examples
- **Session-specific instructions** (writing new section, revising, continuity checking, handover)
- Key concepts to understand before writing
- Questions to ask before writing

**Why This Matters**:
- Works across all AI tools (Claude Code, Desktop, Cursor, web Claude, GPT, etc.)
- Any agent can get oriented in 5 minutes
- Prevents tone drift by setting clear standards
- Provides workflow for different session types

**Critical Section - Session Type Instructions**:
- Writing New Section (before/during/after protocol)
- Revising Existing Section (what to check, how to maintain consistency)
- Continuity Check (verify cross-section consistency)
- Handover (how to end session for next agent to resume)

---

### 3. DEVLOG.md - Session-by-Session Development Log

**Purpose**: Capture ephemeral context that doesn't live in the content files

**Key Elements**:
- What was done this session
- Key decisions made (and rationale)
- Conceptual continuity notes (new concepts that need to appear elsewhere)
- Tone/voice observations
- Open questions and blockers
- Next session recommendations

**Why This Matters**:
- Next session reads last 2-3 entries to get oriented
- Captures "why did we choose X over Y?" decisions
- Tracks conceptual threads across sections
- Prevents re-litigating already-settled questions

**Template for Each Entry**:
```markdown
## Session N: Brief Description
**Date**: YYYY-MM-DD
**Session Type**: Writing/Revising/Continuity/Handover
**Agent**: Claude Code/Desktop/Web/Other

### What Was Done
### Key Decisions Made
### Conceptual Continuity Notes
### Tone/Voice Observations
### Open Questions / Blockers
### Next Session Recommendations
### Current Status
```

---

### 4. voice-samples.md - Tone Reference Library

**Purpose**: Show-don't-tell guide for maintaining consistent voice

**Key Elements**:
- **GOOD examples** (with explanation of why they work)
- **BAD examples** (with explanation of what's wrong)
- Tone calibration guidelines
- Key phrases to use consistently
- Section opening templates
- Technique description templates

**Why This Matters**:
- Prevents tone drift across sessions
- Gives AI concrete examples to emulate
- Makes "direct and precise" concrete, not abstract
- Accumulates strong passages as document develops

**Pattern**:
```markdown
### GOOD Example: [Title]
> [Example passage]

**Why this works**:
- Concrete reason 1
- Concrete reason 2

### BAD Example: [Title]
> [Example passage]

**Why this doesn't work**:
- Concrete reason 1
- Concrete reason 2
```

---

### 5. examples-bank.md - Canonical Examples Tracker

**Purpose**: Ensure same scenario is used consistently across sections

**Key Elements**:
- Canonical formulation of each major example
- Where example is used (cross-reference tracking)
- Context variations (professional/intimate/casual adaptations)
- Notes on what makes it work

**Why This Matters**:
- "Why didn't you call?" appears in 5 sections—needs to be identical
- Prevents contradictions (Section 3 says X, Section 7 says Y about same example)
- Allows deliberate variations while tracking canonical version

**Pattern**:
```markdown
### Example: [Title]

**Canonical Formulation**:
- Instead of: [problematic version]
- Use: [improved version]

**Technique Demonstrated**: [name]

**Used In**:
- Section X
- Section Y
- [Updated as sections reference it]

**Notes**: What makes this work, key elements to preserve
```

---

## Writing Order Strategy: Spiral Development

**Don't write linearly** (Section 1 → 2 → 3 → ...).

**Do write in conceptual phases**:

### Phase 1: Foundational Clarity
- Core concepts and first examples
- Establishes voice/tone for everything that follows
- Goal: "Now we know how to write the rest"

### Phase 2: Practical Depth
- Immediately useful techniques
- Rich examples across contexts
- Goal: Make it useful before making it complete

### Phase 3: Theoretical Grounding
- Now theory can reference concrete examples from Phase 2
- Readers who skipped theory can go back if interested
- Goal: Explain why techniques work

### Phase 4: Specialized Applications
- Apply core framework to specific contexts
- Goal: Context-specific guidance

### Phase 5: Polish & Completeness
- Fill remaining sections
- Cross-reference verification
- Consistency pass
- Goal: Make it comprehensive

**Why This Works**:
- Establishes voice early (Phase 1)
- Makes useful before theoretical (Phase 2 before 3)
- Theory benefits from concrete examples to reference
- Specialized sections benefit from full framework being established

---

## Session-Based Workflow Protocol

### Every Session Follows Same Pattern

**1. ORIENT (5 min)**:
- Read onboarding.md (refresh philosophy)
- Read last 2-3 DEVLOG entries (what's fresh, what's pending)
- Check SPEC.md for target section (status, dependencies, success criteria)

**2. CONTEXT GATHERING (variable)**:
- Read any prerequisite sections
- Review relevant examples from examples-bank.md
- Check voice-samples.md for tone standard

**3. WRITE (main work)**:
- Draft the section
- Test against quality standards from onboarding.md
- Generate minimum required examples

**4. DOCUMENT (5-10 min)**:
- Update SPEC.md section status
- Log to DEVLOG.md (what was written, decisions, open questions)
- Add strong examples to voice-samples.md
- Add reusable examples to examples-bank.md
- Flag any conceptual drift or cross-section issues

**Why This Works**:
- Prevents "lost context" problem
- Makes each session productive (no time wasted re-orienting)
- Builds institutional knowledge in files, not just AI memory
- Works across different AI tools and sessions

---

## Lessons Learned (Will Grow With Project)

### Lesson 1: Dependency Maps Are Critical

**Problem**: Wanted to write Section 7 (relationships) before Section 3 (theory).

**Why It Matters**: Section 7 references "three-layer communication model" from Section 3.3.

**Solution**: SPEC.md dependency map showed Section 7 depends on Section 3.3. Write Phase 3 first, or write Section 7 with placeholder reference to be filled later.

**Generalization**: For any multi-section document, map dependencies before writing. Some sections can be written in any order, others can't.

---

### Lesson 2: Examples Need Central Tracking

**Problem**: "Why didn't you call?" is the canonical example. What if Section 2 writes it one way, Section 7 writes it differently?

**Solution**: examples-bank.md tracks canonical formulation and all uses.

**Generalization**: Any example that appears in multiple places needs:
- Canonical version
- Usage tracking
- Variation guidelines (when is it OK to adapt?)

---

### Lesson 3: Tone Drift Is Real

**Problem**: Different AI sessions (or same AI on different days) produce different writing styles without concrete examples to emulate.

**Solution**: voice-samples.md with GOOD/BAD examples. Not abstract rules ("be direct") but concrete passages ("like this, not like that").

**Generalization**: Style guides need examples, not just principles. "Write clearly" is useless. "Like Example A, not like Example B" is actionable.

---

### Lesson 4: Success Criteria > Word Count

**Problem**: "Write Section 4" is vague. Done when? How do you know it's good?

**Solution**: SPEC.md defines success as "reader can DO X afterward." Section 4 is done when reader can use 6 techniques in next conversation.

**Generalization**: For each section/chapter, define what reader should be able to DO after reading. This makes "done" measurable.

---

### Lesson 5: Session Logs Are Memory

**Problem**: Session 1 decides "we're using domain-binding not scope-restriction as the term." Session 5 (two weeks later, different AI) doesn't know this.

**Solution**: DEVLOG.md captures decision with rationale. Session 5 reads last few entries, sees the decision.

**Generalization**: Don't rely on AI memory (or human memory). Log decisions with rationale. Future sessions read logs to maintain continuity.

---

## Open Questions (To Be Resolved As Project Progresses)

### Q1: Document Compilation Approach?

**Options**:
- A: Write sections as standalone files (section-01.md, section-02.md), compile at end
- B: Write directly into single growing document
- C: Hybrid (standalone during development, merge when complete)

**Current Status**: Deferred until Section 1 is written. Will choose based on what feels natural.

**Decision Criteria**: Which approach makes cross-referencing easier? Which makes continuity checking easier?

---

### Q2: How Deep on Theory Sections?

**Context**: Audience is physician + engineer + partners. Theory sections (neurodevelopmental, information theory, game theory, linguistics) could go shallow or deep.

**Current Status**: Write Phase 2 (practical) first. This will reveal what theoretical depth is needed to explain "why it works."

**Principle**: Theory serves practice. If practice doesn't need it, don't force it.

---

### Q3: How to Handle Edge Cases?

**Context**: Framework has limits. When does it not apply? When is uncertainty actually avoidance, not cognitive style?

**Current Status**: Section 12 (Edge Cases & Complications) is Phase 5 (late). Will accumulate edge cases in DEVLOG as we encounter them in earlier writing.

**Principle**: Edge cases become clearer after core framework is established.

---

## Anti-Patterns Observed (Things That Didn't Work)

### Anti-Pattern 1: Starting Without Structure

**What happened**: Initial impulse was "just start writing Section 1."

**Why it failed**: Without SPEC.md, wouldn't know what Section 1 needs to accomplish, what depends on it, what tone to use.

**Lesson**: Infrastructure first, content second. The setup overhead pays off immediately.

---

### Anti-Pattern 2: Abstract Style Guidance

**What happened**: Early draft of onboarding.md said "be direct and precise, avoid corporate-speak."

**Why it's weak**: Different people/AIs interpret "direct" differently.

**Fix**: voice-samples.md with concrete GOOD/BAD examples. Now "direct" means "like Example A, not like Example B."

**Lesson**: Show don't tell applies to writing instructions too.

---

## Generalizable Patterns

### Pattern 1: The Five-Document Foundation

For any large-scale AI-assisted writing project:
1. **SPEC** (what to build, success criteria, dependencies)
2. **Onboarding** (philosophy, tone, session workflows)
3. **DEVLOG** (session-by-session decisions and continuity)
4. **Voice samples** (concrete good/bad examples)
5. **Examples bank** (canonical formulations for consistency)

### Pattern 2: Session-Based Incremental Development

- Orient → Context → Write → Document
- Every session follows same protocol
- Logs maintain continuity across sessions
- Works across different AI tools

### Pattern 3: Spiral Development Over Linear

- Phase 1: Foundation (voice, core concepts)
- Phase 2: Practical utility
- Phase 3: Theoretical depth
- Phase 4: Specialized applications
- Phase 5: Polish

### Pattern 4: Success Criteria As Definition of Done

- Not "write 2000 words"
- But "reader can DO X afterward"
- Makes quality measurable

---

## Future Additions to This Document

As the project progresses, capture:
- New lessons learned
- Resolved open questions (with outcomes)
- Additional anti-patterns discovered
- Refinements to the five-document foundation
- Session workflow optimizations
- Cross-tool insights (does this work in Cursor? GPT? Web Claude?)

---

## Meta-Note

This document itself demonstrates the philosophy: **immediately practical, theoretically grounded, honest about limitations, accumulates wisdom as it goes**.

It's not a prescription ("do it this way"). It's a pattern library ("here's what worked for this project, adapt as needed").

---

**Current Status**: Foundation established, first writing session pending. Will update with real-world insights as development proceeds.
