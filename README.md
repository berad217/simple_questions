# High-Uncertainty Cognitive Style: Communication Framework

A practical communication framework for individuals who experience persistent high-dimensional uncertainty when answering questions, and for people who communicate with them.

## The Problem

Some highly intelligent individuals process questions by simultaneously evaluating causal, emotional, moral, strategic, and reputational dimensions. Committing to a single answer feels inaccurate or dishonest because it "amputates uncertainty." This creates communication friction in relationships, professional settings, and daily life.

When asked "Why didn't you call?", they simultaneously process:
- Logistics (phone was dead, forgot, was busy)
- Relationship implications (does this signal deprioritization?)
- Accuracy concerns (which of the 7 contributing factors is THE reason?)
- Future obligations (does answering commit me to a pattern?)
- Meta-level (is this question really about the call or about something else?)

## The Solution

**Structured dimensionality reduction** through question design, response protocols, and shared communication frameworks—NOT asking people to "think simpler."

The techniques work by **specifying which dimensions to evaluate**, not by eliminating dimensional thinking.

## Project Status

**Current Phase**: Phase 2 in progress (practical frameworks)

**Progress**: 7 of 14 core sections complete (~32,300 words)

**Complete practical framework available**: The document now includes a fully usable communication system with techniques, bilateral protocols, intent taxonomy, and real-time negotiation strategies.

### What's Available to Read Now

**Foundation** (Phase 1 - Complete):
- **Section 1: Core Cognitive Profile** - Describes the high-dimensional processing pattern, why forced collapse feels dishonest, cognitive style framing
- **Section 2: Communication Mismatch** - Why "simple" questions aren't simple, what goes wrong, structural vs personal framing

**Practical Tools** (Phase 2 - In Progress):
- **Section 4.1: Core Techniques** - Six dimensionality-reduction techniques (domain-binding, uncertainty permission, forced-slice, counterfactual anchoring, output-format constraints, role-locking) with examples
- **Section 5.1: Response Protocols for Responders** - Seven response formats high-uncertainty individuals can use (satisficing, layered disclosure, meta-response, conditional, confidence-bounded, structured uncertainty, redirect)
- **Section 5.2: Response Protocols for Questioners** - Five protocol categories for asking better questions (intent declaration, constraint specification, permission-granting, meta-communication, repair protocols)
- **Section 6.2: Question Intent Taxonomy** - Five intent types (logistical, emotional, diagnostic, planning, social) with recognition patterns and technique mappings
- **Section 6.1: Real-Time Negotiation** - Signaling vocabulary, protocol negotiation, emergency simplification, meta-communication strategies for both parties

**Coming Next**:
- Section 6.3: Confidence Expression Systems
- Section 11: Worked Examples & Case Studies
- Section 3: Theoretical Frameworks (why this works)
- Sections 7-8: Relationship-specific applications

### Complete Framework Overview

The completed sections form a fully functional communication system:

**For High-Uncertainty Responders**:
1. Use techniques (Section 4.1) to structure your thinking
2. Choose appropriate response format (Section 5.1)
3. Identify question intent (Section 6.2) to select right approach
4. Use negotiation phrases (Section 6.1) when stuck

**For Questioners**:
1. Declare intent upfront (Section 6.2) to set expectations
2. Use question protocols (Section 5.2) to reduce dimensionality
3. Use negotiation phrases (Section 6.1) to redirect when needed

**For Both**:
- Shared vocabulary for real-time repair (Section 6.1)
- Meta-communication strategies for diagnosing stuck patterns
- Emergency simplification when structure fails

See [workflow/SPEC.md](workflow/SPEC.md) for the complete document structure and [HANDOVER.md](HANDOVER.md) for current session context.

## Target Audiences

1. **People with high-uncertainty cognitive style** - who struggle to answer "simple" questions
2. **People who interact with high-uncertainty individuals** - partners, colleagues, friends
3. **Both together** - relationship-specific communication protocols

## Document Philosophy

- **Immediately practical** - techniques you can use in the next conversation
- **Theoretically grounded** - but theory serves practice, not vice versa
- **Dual-perspective** - addresses both questioners and responders
- **Non-pathologizing** - this is a cognitive style with trade-offs, not a disorder to fix
- **Relationship-aware** - acknowledges that communication serves connection as well as information exchange

## Core Techniques Preview

Six foundational techniques for asking easier-to-answer questions:

1. **Domain-binding** - Restrict which layer of reality is being queried
   - Instead of: "Why didn't you call?"
   - Use: "Logistically only—what stopped you from calling yesterday?"

2. **Uncertainty permission** - Explicitly allow provisional or incomplete answers
   - "Given what you knew at the time, even if it was wrong, what did you think was happening?"

3. **Forced-slice questions** - Ask for one factor rather than the full explanation set
   - "If you had to name just one factor, what mattered most?"

4. **Counterfactual anchoring** - Ask what difference would have changed the outcome
   - "What would have needed to be different for you to say yes?"

5. **Output-format constraints** - Define the structure of the answer before it's given
   - "Yes or no first, explanation after."
   - "One sentence, even if incomplete."

6. **Role-locking** - Specify which internal role should answer
   - "Answer this as a manager, not as a theorist."
   - "Answer as if you had to act today."

## Project Structure

```
simple_questions/
├── content/                    # Written sections (the actual document)
│   ├── section-01-core-cognitive-profile.md           # ~3,800 words ✅
│   ├── section-02-communication-mismatch.md           # ~3,200 words ✅
│   ├── section-04-1-core-techniques.md                # ~4,900 words ✅
│   ├── section-05-1-response-protocols-responders.md  # ~6,600 words ✅
│   ├── section-05-2-response-protocols-questioners.md # ~6,400 words ✅
│   ├── section-06-1-real-time-negotiation.md          # ~6,800 words ✅
│   └── section-06-2-question-intent-taxonomy.md       # ~5,900 words ✅
│
├── workflow/                   # AI workflow infrastructure
│   ├── SPEC.md                # Section outline, success criteria, dependencies
│   ├── DEVLOG.md              # Session-by-session development log
│   ├── onboarding.md          # Agent entry point (philosophy, protocols)
│   ├── voice-samples.md       # Tone reference library
│   └── examples-bank.md       # Canonical examples tracker
│
├── source/                     # Reference material
│   └── genesis_document.md    # Original conceptual seed
│
├── HANDOVER.md                # Current session handover (Session 7 → 8)
├── README.md                  # This file
└── workflow-wisdom.md         # Generalized workflow guide
```

## Development Approach

This project uses a **session-based incremental development workflow** with AI assistance:

- **Phase 1**: Foundational concepts (Sections 1-2) ✅ COMPLETE
- **Phase 2**: Practical frameworks (Sections 4.1, 5.1, 5.2, 6.2, 11) - IN PROGRESS (4 of 5 sections complete)
- **Phase 3**: Theoretical grounding (Section 3.1-3.4)
- **Phase 4**: Relationship-specific applications (Sections 7-8)
- **Phase 5**: Polish and completeness (Sections 9-14)

The framework is usable now—readers can apply techniques, protocols, intent recognition, and negotiation strategies immediately. Theory and relationship-specific applications will deepen understanding but aren't required for practical use.

See [workflow-wisdom.md](workflow-wisdom.md) for insights on AI-assisted non-coding projects and [DEVLOG.md](workflow/DEVLOG.md) for detailed session history.

## Contributing

This is currently in active development. The framework is being written collaboratively between human domain experts and AI assistants.

If you recognize this cognitive pattern and want to contribute examples, edge cases, or insights, please open an issue.

## License

[To be determined]

## Authors

- Brad (primary author, domain expert)
- Nikki (genesis document author)
- Claude (AI writing assistant)

---

**Current Status**: Phase 2 in progress — 7 core sections complete (~32,300 words), complete practical framework available

**Latest Session**: Session 7 completed Sections 6.1 (Real-Time Negotiation) and 6.2 (Question Intent Taxonomy)

**Next Up**: Section 6.3 (Confidence Expression Systems) or Section 11 (Worked Examples)
