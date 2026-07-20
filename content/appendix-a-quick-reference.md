# Appendix A: Quick Reference Cards

These are distilled, printable summaries of the full framework. Each card stands alone—print the one you need, or keep all four handy. They compress the detailed sections into at-a-glance form; when a card isn't enough, the referenced section has the full treatment, examples, and failure modes.

The cards assume you've read the framework at least once. They're memory aids, not a substitute for the reasoning behind each move.

---

## Card 1: Questioner Guide

*You're asking someone with a high-uncertainty cognitive style. You want a usable answer without forcing them to amputate real uncertainty. Full detail: Sections 4.1–4.3, 5.2.*

### Before you ask: declare intent

State what kind of answer you need and why. This removes the biggest hidden load—the responder guessing *why* you're asking (see Section 5.2).

> "I need a rough gut-check for a scheduling decision, not a full analysis."

The five intent types (Section 6.2). Naming yours resolves most friction:

| Intent | You want | Say something like |
|--------|----------|--------------------|
| **Logistical** | Coordinate an action | "Just need the when/where—best guess is fine." |
| **Emotional** | Reassurance, connection | "I don't need a solution, I want to understand how you feel." |
| **Diagnostic** | Accurate root cause | "Take your time—I want the real analysis, not a quick answer." |
| **Planning** | Decision support / risk | "Help me weigh this—what are the big factors?" |
| **Social** | Maintain the relationship | "Low stakes, just chatting—whatever comes to mind." |

### The six core techniques (Section 4.1)

| Technique | What it does | Example |
|-----------|--------------|---------|
| **Domain-binding** | Query one layer, exclude the rest | "Logistically only—what stopped you from calling?" |
| **Uncertainty permission** | Allow a provisional "current best guess" | "Even if it changes later—what's your working theory?" |
| **Forced-slice** | Ask for one factor, not the whole set | "I know it's several things—name the one that mattered most." |
| **Counterfactual anchoring** | Ask what would change the outcome | "What would've needed to be different for you to say yes?" |
| **Output-format constraints** | Specify length/shape up front | "Two-sentence version—we can go deeper if needed." |
| **Role-locking** | Specify which perspective to answer from | "As the engineer who maintains it, not the PM—ship it?" |

### If the answer stalls or expands

- **They're listing everything** → forced-slice: "Just one, to start."
- **They keep hedging** → uncertainty permission, or unbundle: "Which are you unsure about—the cause or the severity?"
- **They give a five-minute answer** → output-format: "One sentence, even if incomplete."
- **They can't separate concerns** → that's diagnostic; the dimensions are genuinely entangled. Ask them to walk you through the interaction.

### Don't

- Don't read a pause as evasion. A pause is processing (Section 10.1).
- Don't demand certainty you don't actually need. Ask for bounds instead: "Best case and worst case?"
- Don't stack urgency you don't have. False time pressure forces a lossy answer for no reason (Section 12.4).

---

## Card 2: Responder Guide

*You've been asked a "simple" question that isn't simple for you. Goal: communicable stability, not perfect truth. Full detail: Sections 5.1, 6.1, 6.3.*

### Signal, don't apologize

Convert invisible processing into information. It's a status update, not a confession (Section 5.1).

> "Give me a few seconds to map this." / "I need to think—not stuck, just processing."

### Provisional commitment: the core move

Separate your *current model* from *eternal truth*. This is how you answer without lying.

> "Based on X, my current answer is Y—that could shift if Z changes."

### Express uncertainty so it's useful, not paralyzing (Section 6.3)

- **Modal answer + bounds**: "Probably Thursday. Worst case Monday if the vendor slips."
- **Numeric when it helps**: "About 70%—the 30% is entirely the vendor timeline."
- **Make the uncertainty informative**: "I'm uncertain *because* two factors point opposite ways—which tells you the decision is genuinely close."

### Request restructuring (collaboration, not deflection)

Ask for the question you *can* answer (Section 6.1):

> "Can you give me a version that's easier to answer?"
> "Do you want the fast answer or the right answer? They're different here."
> "Which layer are you asking about—logistics, or how I feel about it?"

### Strategic choice: push back vs. give the lossy answer (Section 5.1)

Not every question is worth restructuring. Weigh **relationship cost** against **information cost**:

- Low stakes, just need flow → give the fast lossy answer; note it's rough.
- High stakes, precision matters → invest in restructuring.
- Someone you'll talk to a thousand more times → worth building shared protocols (Section 7.3).

### When simplification is genuinely required (Section 12.4)

Emergencies, testimony, hard deadlines. Collapse—but name it:

> "Given the time constraint, my best collapse is: yes. What I'm not capturing is [X]. If that matters, we need more time."

---

## Card 3: Common Patterns Cheat Sheet

*Fast lookup. The full toolkit at a glance, plus the extras from Section 4.2.*

### Additional techniques (Section 4.2)

| Technique | What it does | Example |
|-----------|--------------|---------|
| **Scope-locking** | Bound the answer in time/space/reach | "Just for this week, not forever—what do you want?" |
| **Reversibility framing** | Pre-define the undo path to lower risk | "We can revisit in a month—want to try it?" |
| **Confidence calibration** | Ask for a probability, not a yes/no | "How confident, 0–10, that it's ready Friday?" |
| **Intent declaration** | State why you're asking | "Just curious, not checking up—how was today?" |
| **Acceptable error tolerance** | Give permission to stop optimizing | "Rough number's fine—within $500 is close enough." |
| **Iteration permission** | Separate generating from committing | "First-draft idea, nothing binding—what comes to mind?" |

### Symptom → move

| What you're seeing | Reach for |
|--------------------|-----------|
| Answer expands into everything | Forced-slice, output-format constraints |
| Endless hedging | Uncertainty permission, confidence calibration |
| Freezes on commitment | Scope-locking, reversibility framing, iteration permission |
| "Why are you asking?" tension | Intent declaration |
| Wrong-layer answer | Domain-binding, role-locking |
| Optimizing forever | Acceptable error tolerance |
| Question feels like a trap | Check for trauma/anxiety, not style (Section 12) |

### The five key phrases (use precisely)

- **Amputates uncertainty** — why forced collapse feels dishonest
- **Structured collapse** — the solution (not "think simpler")
- **Reduce dimensionality** — what the techniques do
- **Lossy compression is not lying** — when both agree on the compression level
- **Communicable stability, not perfect truth** — the goal

### Techniques stack

> "Logistically only *(domain-binding)*, what would need to change *(counterfactual)* for you to take this—just one factor *(forced-slice)*, even if you're not sure *(uncertainty permission)*?"

---

## Card 4: Protocol Negotiation Flowchart

*When a question is stuck, either party can drive the negotiation. Follow the branch for your role. Full detail: Section 6.1.*

### Responder: "I've been asked something I can't cleanly collapse."

```
Asked a question that triggers full expansion
        │
        ▼
Do I need a moment, or is the question itself malformed?
        │
   ┌────┴─────────────────────────┐
   │                              │
 Just need time                Question is unanswerable as framed
   │                              │
   ▼                              ▼
Signal processing            Request restructuring:
"Give me a few seconds"      "Which layer are you asking about?"
   │                         "Fast answer or right answer?"
   ▼                              │
Can I now give a                  ▼
provisional answer?          Did reframing unlock it?
   │                              │
 ┌─┴──┐                      ┌────┴────┐
Yes   No                    Yes        No
 │     │                     │          │
 ▼     ▼                     ▼          ▼
"Based on X,   Is simplification    Answer    Graceful exit:
my current     truly required?      it.       "I can't answer this
answer is Y"   (emergency/formal)             as framed—here's what
        │                                      I CAN answer instead"
    ┌───┴───┐
   Yes     No
    │       │
    ▼       ▼
Collapse   Strategic choice:
+ name     relationship cost vs.
what's     information cost →
lost       push back or give
           the lossy answer
```

### Questioner: "My question got a stalled or expansive response."

```
Response stalled, hedged, or expanded
        │
        ▼
Did I declare my intent and the answer format?
        │
   ┌────┴────┐
   No        Yes
   │          │
   ▼          ▼
Declare    Is the pause processing, or avoidance?
intent +   (consistent across topics? enables commitment
format,    when given structure? → processing. Section 12)
re-ask         │
   │      ┌────┴─────────────┐
   │   Processing         Avoidance / not-style
   │      │                   │
   │      ▼                   ▼
   │  Apply a technique   Structure won't fix it.
   │  to the symptom      Address the real driver:
   │  (see Card 3         safety, anxiety, trauma,
   │  symptom→move)       or relationship negotiation
   │      │               (Sections 5, 12)
   └──────┤
          ▼
   Still stuck after 2–3 tries?
          │
          ▼
   Go meta: "Let's pause—what's making
   this question hard to answer?"
```

### The meta-escape hatch (either side, anytime)

When the *content* negotiation fails, talk about the *talking*:

> "Let's pause and talk about how we're talking. What would make this easier?"

This is always available and never a failure. Naming the process is itself a protocol (Section 5.1, meta-honesty).

---

*For the reasoning behind every move here, see the full sections. These cards are the compression; the sections are the source.*
