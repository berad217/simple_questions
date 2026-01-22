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

**Current Phase**: Phase 1 in progress (Section 1 complete, Section 2 next)

This repository contains:
- Complete document outline with 35+ sections
- Development infrastructure for multi-session AI-assisted writing
- Section 1: Core Cognitive Profile (complete)
- Foundation for practical techniques and relationship-specific protocols

See [workflow/SPEC.md](workflow/SPEC.md) for the complete document structure and development roadmap.

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
│   └── section-01-core-cognitive-profile.md
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
├── HANDOVER.md                # Current session handover
├── README.md                  # This file
└── workflow-wisdom.md         # Generalized workflow guide
```

## Development Approach

This project uses a **session-based incremental development workflow** with AI assistance:

- **Phase 1**: Foundational concepts and core techniques (IN PROGRESS)
- **Phase 2**: Practical depth (response protocols, worked examples)
- **Phase 3**: Theoretical grounding
- **Phase 4**: Relationship-specific applications
- **Phase 5**: Polish and completeness

See [workflow-wisdom.md](workflow-wisdom.md) for insights on AI-assisted non-coding projects.

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

**Current Status**: Phase 1 in progress — Section 1 (Core Cognitive Profile) complete, Section 2 (Communication Mismatch) next
