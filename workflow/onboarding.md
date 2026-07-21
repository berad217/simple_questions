# Start Here: Simple Questions Project Onboarding

**You are joining a multi-session writing project.** This is your single entry point.

**IMPORTANT**: Reading this document means FOLLOWING the instructions in it. As you read each step, execute it before moving to the next step. When you finish reading this file, you should have already read HANDOVER.md and any other files specified for your session type, and be ready to begin work.

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

**Current status**: Content-complete as of Session 26 (2026-07-20). All SPEC sections (1–14) and Appendices A/B/C are written, editorially verified, and cross-vendor reviewed (~57,500 words, 22 build units). See `DEVLOG.md` (latest entries) and root `HANDOVER.md` for current state. Remaining work is optional polish only.

---

## Step 2: Read the Handover (What's In Flight)

**ACTION**: Read `HANDOVER.md` (root directory) RIGHT NOW before continuing.

This tells you:
- What the last session accomplished
- What's ready to work on next
- Any in-flight decisions or temporal context

Stop reading this file and go read HANDOVER.md. Come back after you've read it.

---

## Step 3: Determine Your Session Type and Complete Required Reading

After reading HANDOVER.md, you'll know what needs to be done. Most common session types:

### A. Writing New Section (most common)
**ACTION**: Read these files NOW (in order) before you report ready to the user:
1. ✅ This file (you're here)
2. ✅ HANDOVER.md (you just did this)
3. **SPEC.md - YOUR SECTION ONLY** - Use Grep to find your section (e.g., "Section 6.2"), read ~30 lines
4. **voice-samples.md - EXAMPLES 1-5 ONLY** - Read first ~150 lines for tone calibration
5. **Skip DEVLOG.md** - HANDOVER already summarizes recent sessions
6. **Skip examples-bank.md** - Reference during writing only if needed
7. **Skip previous sections** - Reference during writing only if needed for cross-reference

**Critical**: Read ~300 lines total, not thousands. HANDOVER contains all temporal context you need.

After reading required files, tell the user you're ready and what you plan to work on.

### B. Revising Existing Section
**ACTION**: Read these files NOW before you report ready:
1. ✅ This file + HANDOVER.md
2. The section being revised
3. **voice-samples.md - EXAMPLES 1-5 ONLY** - First ~150 lines for tone calibration
4. **Skip DEVLOG.md** - HANDOVER explains why revision is needed

### C. Infrastructure/Meta Work
**ACTION**: Read these files NOW before you report ready:
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

If you've followed the steps above, you've now:
- ✅ Read this file (onboarding.md)
- ✅ Read HANDOVER.md
- ✅ Read all required files for your session type (SPEC.md section, DEVLOG.md, voice-samples.md, examples-bank.md, previous sections as needed)

You should be fully oriented and ready to begin work.

**Tell the user you're ready and what you plan to work on.**
