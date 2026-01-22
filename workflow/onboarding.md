# Start Here: Simple Questions Project Onboarding

**You are joining a multi-session writing project.** This is your single entry point.

---

## Step 1: Read This Section (Project Context)

**What we're building**: A practical communication framework for individuals with high-uncertainty cognitive style and the people who communicate with them. This addresses a specific pattern where "simple" questions automatically expand into multi-dimensional problems.

**Target audience**:
- People who struggle to answer "simple" questions (responders)
- People who interact with them (questioners)
- Both together (relationship protocols)

**Philosophy**:
- Immediately practical (techniques you can use today)
- Non-pathologizing (cognitive style with trade-offs, not disorder)
- Dual-perspective (serves both questioners and responders)
- Example-rich (show, don't tell)

**Current status**: ~8,000 words written, Phase 1 complete, voice established

---

## Step 2: Read the Handover (What's In Flight)

**Read**: `HANDOVER.md` (root directory)

This tells you:
- What the last session accomplished
- What's ready to work on next
- Any in-flight decisions or temporal context

**Do this now before continuing.**

---

## Step 3: Determine Your Session Type

After reading HANDOVER.md, you'll know what needs to be done. Most common session types:

### A. Writing New Section (most common)
**You need to read**:
1. ✅ This file (you're here)
2. ✅ HANDOVER.md (you just did this)
3. **SPEC.md** - Find your section, read its requirements/success criteria
4. **DEVLOG.md** - Skim last 2-3 session entries for context
5. **voice-samples.md** - Read ~5 examples to calibrate tone
6. **examples-bank.md** - Reference if you're reusing established examples
7. **Previous sections** - Skim if voice continuity check needed

**Then**: Write the section, update workflow files (SPEC.md status, DEVLOG.md entry, voice-samples/examples-bank if applicable), update HANDOVER.md

### B. Revising Existing Section
**You need to read**:
1. ✅ This file + HANDOVER.md
2. The section being revised
3. DEVLOG.md - Why revision is needed
4. voice-samples.md - Current tone standard

### C. Infrastructure/Meta Work
**You need to read**:
1. ✅ This file + HANDOVER.md
2. Whatever HANDOVER.md says to read

---

## Core Concepts (Keep These Consistent)

**Key phrases - use exactly**:
- **"Amputates uncertainty"** - why forced collapse feels dishonest
- **"Structured collapse"** - solution approach (NOT "simpler thinking")
- **"Reduce dimensionality"** - what techniques do
- **"Lossy compression is not lying"** - when both parties agree on compression level
- **"Communicable stability, not perfect truth"** - the goal

**Cognitive style framing**:
- NOT: "overthinking" that needs fixing
- YES: High-dimensional processing that needs structural support

**Communication model** (mentioned but not fully explained until Section 3.3):
1. Literal information (explicit content)
2. Relationship signal (trust, priority, care)
3. Common knowledge (what both parties know they both know)

---

## Voice & Tone Standards

**The 5 rules**:
1. **Direct and precise** - no corporate-speak, no excessive hedging
2. **Non-pathologizing** - structural mismatch, not personal failure
3. **Practically grounded** - show what to do, then why it works
4. **Example-rich** - minimum 3 before/after examples per technique
5. **Minimal bullet abuse** - use prose for conceptual content; bullets only for actual lists

**Good example pattern** (from genesis_document.md):
> **Domain-binding**: Restrict which layer of reality is being queried.
>
> Instead of: "Why didn't you call?"
> Use: "Logistically only—what stopped you from calling yesterday?"

Concrete, shows before/after, immediately usable, explains mechanism.

**See voice-samples.md for 18+ examples of strong passages.**

---

## Writing Templates

### Section Opening (use for all sections):
```
## What This Section Is For

[What problem this solves]. If you [experience X] or [interact with people who Y],
read this to learn [concrete outcome].

After reading this, you should be able to [specific capabilities].
```

### Technique Template (for Section 4.x):
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

**Failure Modes**: What goes wrong and how to correct (2-3 common modes with fixes)
```

---

## File Structure

```
simple_questions/
├── HANDOVER.md           ← Read this second (in-flight context)
├── workflow/
│   ├── onboarding.md     ← You are here (start point)
│   ├── SPEC.md           ← Section requirements, dependencies, status
│   ├── DEVLOG.md         ← Session-by-session development log
│   ├── voice-samples.md  ← Tone reference library
│   └── examples-bank.md  ← Canonical examples tracker
├── content/              ← Written sections
│   ├── section-01-core-cognitive-profile.md
│   ├── section-02-communication-mismatch.md
│   └── section-04-1-core-techniques.md
└── source/
    └── genesis_document.md  ← Original concept (reference, don't modify)
```

---

## After You Write

**Always update**:
1. **SPEC.md** - Change your section status to "Complete"
2. **DEVLOG.md** - Add session entry (what done, key decisions, recommendations)
3. **HANDOVER.md** - Update for next session (what's now in-flight)

**Update if applicable**:
4. **voice-samples.md** - Add strong passages
5. **examples-bank.md** - Add new canonical examples

**Git commit**:
- Commit when section complete or at natural checkpoint
- Use format: "Session N: [Brief description]"
- Include "Co-Authored-By: Claude [model] <noreply@anthropic.com>"

---

## Common Pitfalls to Avoid

❌ **Don't**: Frame this as "overthinking" that needs to be stopped
✅ **Do**: Frame as high-dimensional processing that needs structural support

❌ **Don't**: Suggest people "just give simple answers"
✅ **Do**: Provide protocols for appropriate dimensionality reduction

❌ **Don't**: Make this about anxiety or pathology
✅ **Do**: Treat as cognitive style with trade-offs

❌ **Don't**: Ignore the emotional/relational layer
✅ **Do**: Address how information exchange serves (or undermines) relationship needs

❌ **Don't**: Create new files unless necessary
✅ **Do**: Prefer editing existing files

---

## Quick Checks Before You Start Writing

1. "Can someone use this technique in their next conversation?"
2. "Have I shown a concrete example?"
3. "Have I acknowledged when this won't work?"
4. "Am I respecting the intelligence of both questioner and responder?"
5. "Does this serve the relationship as well as the information exchange?"

---

## You're Ready

You've now read:
- ✅ This file (onboarding.md)
- ✅ HANDOVER.md

Next: Based on HANDOVER.md, read the specific files you need (SPEC.md section, voice-samples.md, etc.) and begin work.

**Tell the user you're ready and what you plan to work on.**
