# Onboarding: High-Uncertainty Cognitive Style Communication Framework

## Quick Start

**Current Status**: Phase 1 in progress (Section 1 complete, Section 2 next)

**Entry Points**:
- **Returning to project?** → Read `HANDOVER.md` first (root directory)
- **First time?** → Continue reading this file
- **Writing a section?** → Check `workflow/SPEC.md` for requirements

**File Locations**:
```
simple_questions/
├── content/                    # Written sections (the actual document)
├── workflow/                   # AI workflow infrastructure
│   ├── SPEC.md                # Section requirements & status
│   ├── DEVLOG.md              # Development history
│   ├── voice-samples.md       # Tone reference
│   ├── examples-bank.md       # Canonical examples
│   └── onboarding.md          # This file
├── source/                     # Reference material
│   └── genesis_document.md    # Original concept (don't modify)
├── HANDOVER.md                # Current session context
└── README.md                  # GitHub overview
```

---

## Project Overview

You are helping develop a practical communication framework for individuals who experience persistent high-dimensional uncertainty when answering questions, and for people who communicate with them. This is NOT generic communication advice—it addresses a specific cognitive pattern where seemingly simple questions automatically expand into complex multi-dimensional problems.

**Core Problem**: Some highly intelligent individuals process questions by simultaneously evaluating causal, emotional, moral, strategic, and reputational dimensions. Committing to a single answer feels inaccurate or dishonest because it "amputates uncertainty." This creates communication friction in relationships, professional settings, and daily life.

**Core Solution**: Structured dimensionality reduction through question design, response protocols, and shared communication frameworks—NOT asking people to "think simpler."

## Target Audiences

This document serves three groups:

1. **People with high-uncertainty cognitive style** - who struggle to answer "simple" questions and need self-advocacy tools, response protocols, and understanding of their own processing
2. **People who interact with high-uncertainty individuals** - partners, colleagues, friends who need to ask questions that are easier to answer and interpret responses accurately
3. **Both together** - relationship-specific protocols for negotiating communication in real-time

## Document Philosophy

### What This Is
- **Immediately practical** - techniques you can use in the next conversation
- **Theoretically grounded** - but theory serves practice, not vice versa
- **Dual-perspective** - addresses both questioners and responders
- **Non-pathologizing** - this is a cognitive style with trade-offs, not a disorder to fix
- **Relationship-aware** - acknowledges that communication serves connection as well as information exchange

### What This Is NOT
- Generic "communication tips" or corporate workshop material
- Advice to "just simplify your thinking"
- Therapy or mental health treatment guidance
- Purely academic analysis without practical application
- One-size-fits-all prescriptions

---

## Writing Approach Guidelines

### Tone & Style
- **Direct and precise** - no corporate-speak, no excessive hedging
- **Intellectually honest** - acknowledge complexity, don't oversimplify
- **Accessible but not condescending** - explain technical concepts clearly without dumbing down
- **Practically grounded** - lead with "here's what to do," follow with "here's why it works"
- **Examples-rich** - show don't tell, use before/after comparisons
- **Minimal bullet abuse** - use prose and paragraphs unless structure genuinely requires lists

### Content Priorities
1. **Actionable > theoretical** - if you're explaining a framework, immediately show how to apply it
2. **Specific > generic** - "Use domain-binding: 'Logistically only, what stopped you?'" beats "Try to narrow the scope"
3. **Honest about limitations** - when something won't work, say so and why
4. **Bidirectional thinking** - always consider both sides of the communication exchange
5. **Edge cases matter** - don't pretend everything is simple; acknowledge when approaches fail

### Section-Specific Guidance

**For Theoretical Frameworks (Part I, Section 3)**:
- Start with the practical implication, then explain the theory
- Use concrete examples to illustrate abstract concepts
- Connect theory directly to communication techniques
- Keep academic depth available but don't force it on readers who want practical tools
- Format: "This matters because [practical impact]. Here's the underlying mechanism: [theory]."

**For Practical Techniques (Part II)**:
- Template: Name → Definition → Example → When to use → Common failure mode
- Use actual dialogue examples showing before/after
- Explain what makes the technique work psychologically/cognitively
- Provide decision criteria for technique selection
- Include "this won't work when..." sections

**For Relationship Applications (Part III)**:
- Acknowledge emotional complexity without getting therapeutic
- Distinguish information exchange from relationship maintenance needs
- Provide specific protocols, not just "communicate better"
- Address power dynamics and asymmetry honestly
- Include repair strategies for when approaches fail

**For Implementation Guides (Part IV)**:
- Extremely concrete and specific
- Assume reader wants to start using this TODAY
- Provide templates, scripts, and examples they can adapt
- Include calibration exercises and practice approaches
- Address the "this feels weird at first" factor

---

## Key Concepts to Understand

### The Dimensionality Problem
When asked "Why didn't you call?", high-uncertainty individuals simultaneously process:
- Logistics (phone was dead, forgot, was busy)
- Relationship implications (does this signal deprioritization?)
- Accuracy concerns (which of the 7 contributing factors is THE reason?)
- Future obligations (does answering commit me to a pattern?)
- Meta-level (is this question really about the call or about something else?)

The techniques work by **specifying which dimensions to evaluate**, not by eliminating dimensional thinking.

### Three Simultaneous Communication Layers
Every question/answer exchange carries:
1. **Literal information** (the explicit content)
2. **Relationship signal** (what this exchange means about trust, priority, care)
3. **Common knowledge establishment** (what both parties now know they both know)

High-uncertainty individuals often over-optimize for layer 1 while underweighting layers 2 and 3.

### Lossy Compression Is Not Lying
All human communication is lossy compression—transmitting a simplified version of complex internal models. High-uncertainty individuals often experience this compression as dishonest. The framework helps distinguish:
- Appropriate simplification (functional compression for transmission)
- Harmful oversimplification (loses critical information)
- Strategic ambiguity (when precision isn't needed)
- Actual deception (intentionally misleading)

---

## Common Pitfalls to Avoid

❌ **Don't**: Frame this as "overthinking" that needs to be stopped
✅ **Do**: Frame it as high-dimensional processing that needs structural support

❌ **Don't**: Suggest people "just give simple answers"
✅ **Do**: Provide protocols for appropriate dimensionality reduction

❌ **Don't**: Make this about anxiety or pathology
✅ **Do**: Treat it as a cognitive style with trade-offs

❌ **Don't**: Imply one communication style is superior
✅ **Do**: Acknowledge different styles serve different purposes

❌ **Don't**: Provide only questioner-side techniques
✅ **Do**: Balance questioner tools and responder tools

❌ **Don't**: Ignore the emotional/relational layer
✅ **Do**: Address how information exchange serves (or undermines) relationship needs

---

## Section Development Protocol

When writing a section:

1. **Check dependencies**: What information from other sections does this need? (State this explicitly if you need placeholder info)

2. **Define success criteria**: What should a reader be able to DO after reading this section?

3. **Structure flow**:
   - Core concept/problem
   - Why it matters (practical impact first)
   - Theoretical grounding (if applicable)
   - Concrete techniques/examples
   - Common failure modes
   - Variations and edge cases

4. **Self-contain for independent reading**: Someone should get value from reading just this section, even if they skip others

5. **Cross-reference judiciously**: Link to other sections when needed, but don't create dependency chains

---

## Example Quality Standards

### GOOD Example (from original doc):
> **Domain-binding**: Restrict which layer of reality is being queried.
> Instead of: "Why didn't you call?"
> Use: "Logistically only—what stopped you from calling yesterday?"

**Why this works**: Concrete, shows before/after, immediately usable, explains the mechanism

### LESS GOOD Example:
> "Try to make your questions more specific and focused on a single aspect rather than being too broad."

**Why this doesn't work**: Vague, no concrete example, doesn't explain HOW to focus or WHICH aspect

---

## You Are Writing For

- A physician with electrical engineering and software background who learns by building
- His colleague who shares this cognitive style
- Their partners, who need to communicate with them effectively
- Anyone else who recognizes this pattern in themselves or others

These are **intellectually sophisticated people** who want:
- Deep understanding of mechanisms
- Immediate practical utility
- Intellectual honesty over social comfort
- Precision when it matters, efficiency when it doesn't

---

## Questions to Ask Before You Write

1. "Can someone use this technique in their next conversation?"
2. "Have I shown a concrete example?"
3. "Have I acknowledged when this won't work?"
4. "Am I respecting the intelligence of both the questioner and responder?"
5. "Does this serve the relationship as well as the information exchange?"

---

## Ready to Write?

When you receive a section assignment, you'll get:
- Section number and title
- Current status (placeholder/needs expansion/needs writing)
- Any specific requirements or focus areas
- Context from related sections if needed

Your job: Write that section to be **immediately useful, intellectually honest, and practically grounded** while maintaining the tone and approach described above.

Start each section by briefly stating: what problem this section solves, who should read it, and what they'll be able to do afterward.

---

## Writing Strategy

Each section can be written independently with:
1. **Clear inputs**: what information it needs from other sections
2. **Standalone utility**: someone could read just that section and get value
3. **Progressive disclosure**: core content first, nuance in subsections
4. **Practical emphasis**: theory serves practice, not vice versa

---

## Session-Specific Instructions

### Session Type: Writing New Section

**Before you start**:
1. Read `HANDOVER.md` (root) for current context
2. Read `workflow/SPEC.md` for your target section (status, dependencies, success criteria)
3. Read last 2-3 `workflow/DEVLOG.md` entries (what's fresh, conceptual continuity)
4. Check `workflow/voice-samples.md` (tone reference)
5. Check `workflow/examples-bank.md` (reusable examples for consistency)
6. Read any prerequisite sections in `content/` listed in dependencies

**During writing**:
- Follow the section template from SPEC.md
- Test each example against "GOOD Example" standard above
- Generate minimum 3 concrete before/after examples per technique
- Note any new concepts that need to appear in other sections

**After writing**:
- Update `workflow/SPEC.md` section status
- Log to `workflow/DEVLOG.md`: what was written, key decisions, open questions
- Add strong examples to `workflow/voice-samples.md`
- Add reusable examples to `workflow/examples-bank.md`
- Update `HANDOVER.md` for next session
- Flag any conceptual drift or tone issues

---

### Session Type: Revising Existing Section

**Before you start**:
1. Read the section to be revised in `content/`
2. Read `workflow/DEVLOG.md` for context on why revision is needed
3. Check `workflow/SPEC.md` for success criteria (are we meeting them?)
4. Review `workflow/voice-samples.md` for current tone standard

**During revision**:
- Maintain conceptual consistency with rest of document
- Check `workflow/examples-bank.md` before changing examples (may be referenced elsewhere)
- If changing key concepts, note sections that may need updates

**After revision**:
- Log to `workflow/DEVLOG.md`: what changed and why
- Update `workflow/voice-samples.md` if new strong examples emerged
- Flag cross-reference checks needed in other sections

---

### Session Type: Continuity Check

**Purpose**: Verify conceptual and tonal consistency across multiple sections

**Process**:
1. Read `workflow/DEVLOG.md` for flagged continuity issues
2. Read relevant sections in `content/` in sequence
3. Check for:
   - Key phrase consistency ("amputates uncertainty", "lossy compression", etc.)
   - Example consistency (same scenarios used differently?)
   - Tone drift (compare to `workflow/voice-samples.md`)
   - Dependency accuracy (does Section X actually depend on Section Y?)

**Output**:
- `workflow/DEVLOG.md` entry with findings
- List of sections needing revision
- Updated `workflow/voice-samples.md` if tone standard has evolved

---

### Session Type: Cross-Reference Verification

**Purpose**: Ensure examples and concepts are used consistently

**Process**:
1. Read `workflow/examples-bank.md`
2. Search `content/` files for each canonical example
3. Verify all uses are consistent (no contradictions)
4. Check that key concepts are explained before being referenced

**Output**:
- `workflow/DEVLOG.md` entry with verification results
- Fixes for any inconsistencies found

---

### Session Type: Handover (Context Window Full / Fresh Perspective Needed)

**Before ending current session**:
1. Complete `workflow/DEVLOG.md` entry with:
   - Current section status
   - Conceptual decisions made this session
   - Open questions or blockers
   - Suggested next steps
2. Note any emerging tone/voice patterns in `workflow/voice-samples.md`
3. Update `workflow/examples-bank.md` with any new canonical examples
4. **Update `HANDOVER.md`** with current state and next steps

**When resuming in new session**:
1. Read `HANDOVER.md` (root) first - this is your entry point
2. Read this file (`workflow/onboarding.md`) to refresh on philosophy
3. Check `workflow/SPEC.md` for overall progress and next priority section
4. Proceed with session type appropriate to next task

---

## Key Project Files

### Root Directory (High Visibility)
- **HANDOVER.md** - Current session handover (START HERE when resuming)
- **README.md** - GitHub project overview
- **workflow-wisdom.md** - Generalized workflow guide (standalone resource)

### workflow/ Directory (AI Infrastructure)
- **SPEC.md** - Complete outline with success criteria, dependencies, writing order
- **onboarding.md** (this file) - Agent entry point, philosophy, writing standards
- **DEVLOG.md** - Session-by-session development log, decisions, continuity notes
- **voice-samples.md** - Tone reference library (good/bad examples)
- **examples-bank.md** - Canonical examples to maintain consistency

### content/ Directory (Written Sections)
- Section files as `section-NN-topic-name.md`
- Currently: `section-01-core-cognitive-profile.md` (complete)

### source/ Directory (Reference Material)
- **genesis_document.md** - Original conceptual seed (reference but don't modify)

---

## Current Progress

| Phase | Status | Sections |
|-------|--------|----------|
| Phase 1: Foundation | In Progress | Section 1 ✅, Section 2 ⏳, Section 4.1 📋 |
| Phase 2: Practical Depth | Not Started | Sections 5.1, 6.2, 11 |
| Phase 3: Theory | Not Started | Sections 3.1-3.4 |
| Phase 4: Relationships | Not Started | Sections 7-8 |
| Phase 5: Polish | Not Started | Remaining sections, appendices |

**Next up**: Section 2 (The Communication Mismatch)
