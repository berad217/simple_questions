# Section 6.1: Real-Time Negotiation

## What This Section Is For

Techniques and protocols only work when both parties can signal what they need in the moment. If you've ever felt stuck between giving a thorough answer (too slow) or a fast answer (feels dishonest), or if you've asked a question and received something incomprehensible, read this to learn how to negotiate response type without creating conflict.

After reading this, you should be able to signal when a question needs restructuring, use shared vocabulary to select appropriate protocols, implement emergency simplification when conversations break down, and exit gracefully when structure isn't helping.

---

## Why Real-Time Negotiation Matters

All the techniques (Section 4.1), protocols (Sections 5.1 and 5.2), and intent recognition (Section 6.2) assume both parties can identify and communicate about what's happening. In practice, most communication friction comes from mismatched expectations that neither party names explicitly.

**Common scenarios where negotiation is needed**:
- Questioner asks for logistical answer, responder starts diagnostic analysis
- Responder recognizes they can't give a fast answer, feels pressure, freezes
- Question carries mixed intent and neither party acknowledges the layers
- Initial protocol selection was wrong for the situation
- Communication is breaking down and both parties keep trying the same approach

Without negotiation vocabulary, these situations escalate: questioner gets frustrated ("why can't you just answer?"), responder feels trapped ("I can't compress this honestly"), relationship damage accumulates.

**What real-time negotiation provides**: Shared language to pause, identify the mismatch, and recalibrate without blame. The goal is not to eliminate friction—it's to make friction nameable and addressable.

---

## Signaling Vocabulary: For Responders

When you receive a question and recognize you need different constraints, use these phrases to negotiate:

### "Give me a version of this question that's easier to answer"

**When to use**: The question is structurally difficult (too broad, too many unstated assumptions, ambiguous intent).

**What it communicates**: "I want to answer, but I need help reducing dimensionality. Work with me to restructure this."

**Example**:
- Questioner: "Should we pursue this opportunity?"
- Responder: "Give me a version of this question that's easier to answer. Are you asking if it's strategically aligned, if we have capacity, or if the terms are acceptable? Those need different analysis."

**Why this works**: Puts responsibility on both parties to make the question answerable, doesn't blame the questioner for asking poorly.

---

### "I can give you a fast answer or a right answer—which matters more right now?"

**When to use**: You recognize the question could go either direction and you're uncertain which intent to optimize for.

**What it communicates**: "I see tradeoffs here. Tell me your priority so I don't solve the wrong problem."

**Example**:
- Questioner: "What's wrong with this design?"
- Responder: "I can give you a fast answer or a right answer—which matters more right now? Fast would be 'color contrast issues,' right would be walking through accessibility, visual hierarchy, and interaction patterns."

**Why this works**: Makes the tradeoff explicit, gives questioner control over which version they need.

---

### "I need [time/constraint] to answer this properly, or I can give you my fast/incomplete answer now"

**When to use**: Logistical intent is clear but you can't meet the speed expectation without compression you're uncomfortable with.

**What it communicates**: "I recognize you want speed, but I need to set expectations about what you'll get if I go fast."

**Example**:
- Questioner: "Can you review this PR before standup?"
- Responder: "I need 30 minutes to review this properly, or I can give you a surface-level check now—mostly looking for obvious bugs, not architecture critique."

70: **Why this works**: Offers both options, lets questioner decide if fast/simplified is acceptable or if they should adjust timeline.

---

### "This question is triggering my multi-dimensional processing—help me collapse it"

**When to use**: You're aware you're spiraling into uncertainty and need external structure.

**What it communicates**: "I'm stuck in my natural mode and need help simplifying. I'm asking for collaboration, not complaining about the question."

**Example**:
- Questioner: "Where should we go for the team offsite?"
- Responder: "This question is triggering my multi-dimensional processing—I'm thinking about budget, travel time, team preferences, accessibility. Help me collapse it: what's the most important constraint?"

**Why this works**: Self-aware, names the cognitive pattern, explicitly requests help rather than just getting stuck.

---

### "I'm hearing [intent type]—is that right, or are you asking for something else?"

**When to use**: You've identified what you think the intent is (using Section 6.2 taxonomy) but want to confirm before investing in the wrong response type.

**What it communicates**: "I want to answer the question you're actually asking, not the literal words. Let me check my interpretation."

**Example**:
- Questioner: "Do you think this project will succeed?"
- Responder: "I'm hearing diagnostic intent—like you want analysis of success factors. Is that right, or are you asking for emotional reassurance / logistical go-no-go decision?"

**Why this works**: Uses shared vocabulary (intent types), shows you're trying to match their need, prevents solving the wrong problem.

---

### "I don't know yet, and here's what I'd need to figure out to give you a useful answer"

**When to use**: The honest answer is "I don't know," but you can be specific about what information or thinking would get you to an answer.

**What it communicates**: "I'm not dodging—I'm genuinely uncertain, but I can tell you what the uncertainty depends on."

**Example**:
- Questioner: "Should we hire another engineer or prioritize automation?"
- Responder: "I don't know yet, and here's what I'd need to figure out: current team velocity, automation ROI timeline, and what we're optimizing for—shipping faster vs. reducing toil. Can we talk through those?"

**Why this works**: Makes "I don't know" informative rather than evasive. Shows your uncertainty is structured, not paralysis.

---

## Signaling Vocabulary: For Questioners

When you ask a question and get a response that doesn't match what you needed, use these phrases to redirect:

### "I need a fast/logistical answer here—your best guess is fine"

**When to use**: Responder is providing thorough analysis when you needed quick closure.

**What it communicates**: "I appreciate the depth, but I need you to compress more aggressively. I'm accepting the tradeoff."

**Example**:
- Questioner: "Should I use library A or B for this feature?"
- Responder: [Starts explaining architectural implications, long-term maintenance, team familiarity...]
- Questioner: "I need a fast answer here—your best guess is fine. I can revisit if it becomes a problem."

**Why this works**: Names the intent explicitly (logistical), gives permission to compress, acknowledges you'll handle downstream issues.

---

### "I'm actually asking for [intent type], not [different intent type]"

**When to use**: Responder is optimizing for the wrong intent (e.g., giving logistical answer when you wanted emotional support).

**What it communicates**: "You answered a different question than I meant to ask. Let me clarify the intent."

**Example**:
- Questioner: "Do you think I handled that meeting well?"
- Responder: "You could have been clearer about timeline expectations and—"
- Questioner: "I'm actually asking for emotional reassurance, not diagnostic critique. I'm feeling insecure and want to know if I did okay."

**Why this works**: Uses shared vocabulary (intent types from Section 6.2), direct about what you actually need, prevents the responder from continuing down the wrong path.

---

### "Let me make the constraints explicit: [constraint]"

**When to use**: You asked a broad question and the responder is stuck because they don't know what to optimize for.

**What it communicates**: "I'll help narrow this. Here's what actually matters for decision-making."

**Example**:
- Questioner: "What should we do about this incident?"
- Responder: [Paralyzed by multiple possible directions—fix immediately, investigate root cause, communicate to stakeholders, prevent recurrence...]
- Questioner: "Let me make the constraints explicit: customers are blocked, so I need immediate mitigation options. We can do root cause analysis after."

**Why this works**: Provides the dimensional reduction responder needs, shows you understand why the question was hard, focuses their processing.

---

### "I hear that you're uncertain—can you give me bounds / best-case and worst-case / what you're confident about?"

**When to use**: Responder is expressing uncertainty and you need *some* information even if it's incomplete.

**What it communicates**: "Uncertainty is fine, but make it informative. Give me structure around what you don't know."

**Example**:
- Questioner: "When will this feature be done?"
- Responder: "I don't know—there are a lot of unknowns..."
- Questioner: "I hear that you're uncertain—can you give me bounds? Like, definitely not before X date, probably done by Y date, worst case Z date?"

**Why this works**: Accepts uncertainty, asks for structured uncertainty (Section 6.3 territory), gives responder a format that feels more honest than single estimate.

---

### "Let's pause—it seems like this question is harder than I thought. What's making it difficult?"

**When to use**: Responder is struggling and you're not sure why. Rather than pushing harder, you create space to diagnose the difficulty.

**What it communicates**: "I see this isn't working. Let's figure out why before continuing. I'm not blaming you for the difficulty."

**Example**:
- Questioner: "Do you want to go to this event with me?"
- Responder: [Long pause, visible processing, difficulty answering]
- Questioner: "Let's pause—it seems like this question is harder than I thought. What's making it difficult? Is it about the event, about us, about something else?"

**Why this works**: Meta-level move that stops the stuck pattern, invites collaboration on diagnosis, non-judgmental framing.

---

### "I realize I asked this poorly—let me reframe"

**When to use**: You see the responder struggling and recognize your question was structurally problematic.

**What it communicates**: "I own the communication difficulty. I'll help fix this."

**Example**:
- Questioner: "Why did you do it that way?" [Sounds accusatory, unclear what "that way" refers to, ambiguous intent]
- Responder: [Defensive or paralyzed]
- Questioner: "I realize I asked this poorly—let me reframe. I'm trying to understand your reasoning for using approach X instead of Y, because I want to learn the tradeoffs, not critique your choice."

**Why this works**: Takes responsibility for poor question construction, clarifies intent, reduces defensiveness, models good communication.

---

## Protocol Negotiation Strategies

### Starting with declared intent

Rather than asking a bare question and hoping the responder infers correctly, declare your intent upfront (using Section 6.2 vocabulary):

**Pattern**: "Logistically only: [question]" / "Emotionally: [question]" / "Diagnostically: [question]"

**Examples**:
- "Logistically only—what time works for you tomorrow?" (Signals: fast answer, good-enough precision)
- "Emotionally—do you still want to work on this project together?" (Signals: reassurance needed, not logistical coordination)
- "Diagnostically—why do you think this keeps failing?" (Signals: depth welcome, thorough analysis expected)

**Why this works**: Prevents intent mismatch from the start, gives responder clear optimization target.

---

### Offering protocol options

When you recognize a question might need different response types, offer explicit options:

**Responder pattern**: "I can give you [option A: fast/shallow] or [option B: slow/deep]—which helps more?"

**Examples**:
- "I can give you my gut reaction right now, or think about this overnight and give you a more thorough answer tomorrow."
- "I can list the top 3 concerns, or I can walk through the full analysis—what's more useful?"
- "I can tell you what I'm confident about, or I can tell you all the things I'm uncertain about—which matters more for your decision?"

**Why this works**: Makes tradeoffs visible, gives questioner control, prevents responder from guessing wrong.

---

### Mid-conversation protocol switching

When initial protocol selection was wrong, explicitly signal the switch:

**Pattern**: "I started answering [intent A], but I think you're actually asking for [intent B]—let me try again"

**Examples**:
- "I started giving you logistics, but I think you're actually looking for diagnostic analysis—let me shift to that."
- "I gave you a fast answer, but now that I'm hearing your follow-ups, it sounds like you want the thorough version. Want me to restart?"
- "I was trying to be thorough, but I'm realizing you needed a decision 5 minutes ago. Here's my fast answer: [X]."

**Why this works**: Names the mismatch explicitly, repairs without blame, resets expectations.

---

### Pre-negotiated protocols for recurring scenarios

For relationships where certain question types recur (partners, close colleagues), pre-negotiate response formats:

**Pattern**: "When I ask about [scenario], I usually need [response type]. If you need different, say so, but that's the default."

**Examples** (intimate relationship):
- "When I ask 'what do you want for dinner?' in the morning, I need a fast logistical answer. When I ask at 6pm while we're both hungry, I probably need emotional support for decision fatigue."
- "When I ask 'how was your day?' right when you get home, I'm doing social check-in. When I ask later after dinner, I actually want the real answer."

**Examples** (professional):
- "When I ask 'how's that project going?' in passing, I'm just checking for blockers. When I ask in our 1-on-1, I want the full context."
- "When I ask 'can you review this?' with a timeline, I need approval/rejection. When I ask without timeline, I'm looking for thorough feedback."

**Why this works**: Reduces negotiation overhead for common scenarios, both parties know the default expectation, still allows override when needed.

---

## Emergency Simplification Techniques

When communication is breaking down despite techniques and protocols, use these emergency moves:

### "I'm going to give you my 10-second answer, and we can unpack it later if needed"

**When to use**: Responder is stuck in complexity, time pressure is real, relationship can tolerate compressed answer.

**How it works**: Forces artificial closure by time-boxing to an extreme ("10 seconds" = "first thing that comes to mind"), with explicit promise to revisit.

**Example**:
- Questioner: "Should we pivot to this new strategy?"
- Responder: [Stuck analyzing implications, strategic fit, resource requirements, risks...]
- Responder: "I'm going to give you my 10-second answer: No, too risky given our current runway. We can unpack my reasoning if you want, but that's my gut."

**Failure mode**: Don't use this when the questioner actually needs the thorough version—this is genuinely emergency compression only.

---

### "Let's reduce this to a binary: Yes/No, A/B, Continue/Stop"

**When to use**: Responder is seeing too many dimensions, but the decision space is actually smaller than they're making it.

**How it works**: Questioner or responder explicitly collapses option space to two choices, forcing selection.

**Example**:
- Questioner: "What should our Q3 priorities be?"
- Responder: [Explodes into 15 possible priority combinations]
- Questioner: "Let's reduce this to a binary: Focus on growth or focus on stability. Pick one, then we'll figure out tactics."

**Why this works**: Artificially constrains the decision space, makes choice less paralyzing, can be expanded later if needed.

---

### "Table this question and ask me something easier"

**When to use**: The question is genuinely unanswerable in current form, and continuing to push is creating frustration for both parties.

**How it works**: Explicit acknowledgment that this question isn't working, request to come back to it later or from a different angle.

**Example**:
- Questioner: "What do you want to do with your life?"
- Responder: [Completely stuck—too broad, too many unstated assumptions, unclear intent]
- Responder: "I need to table this question—it's too big and I don't know where to start. Ask me something easier, like what I want to do in the next 6 months, or what I value most in work."

**Why this works**: Prevents the stuck pattern from continuing, invites the questioner to help by restructuring, doesn't pretend the question is answerable as-is.

---

### "Let's agree on good-enough criteria before I answer"

**When to use**: Responder knows they'll spiral without external satisficing criteria, wants to set those criteria collaboratively before attempting answer.

**How it works**: Both parties explicitly define what "good enough" looks like for this specific question, then responder attempts to meet that bar.

**Example**:
- Questioner: "Which candidate should we hire?"
- Responder: [Sees unlimited dimensions to analyze]
- Responder: "Let's agree on good-enough criteria before I answer. Are we looking for 'won't cause problems' or 'best possible fit'? And how quickly do we need to decide?"
- Questioner: "Won't cause problems, and we need to decide by end of week."
- Responder: "Okay, that I can do. Candidate B feels safest—meets all requirements, no red flags, slight upside on technical skills."

**Why this works**: Calibrates "good enough" explicitly, gives responder a clear target, prevents over-optimization.

---

### "I'm stuck—can you just tell me what to say?"

**When to use**: Responder is completely paralyzed, time pressure is extreme, they trust the questioner's judgment, and just need to be released from decision burden.

**How it works**: Responder explicitly asks questioner to choose for them, transferring decision authority.

**Example**:
- Questioner: "What should I tell the client about timeline?"
- Responder: [Paralyzed by uncertainty about technical complexity, resource availability, risk tolerance]
- Responder: "I'm stuck—can you just tell me what to say? You know the client relationship better, and I can't get unstuck on the technical timeline."
- Questioner: "Tell them 6 weeks. We'll make it work."

**Critical caveat**: Only works in high-trust contexts where both parties understand this is emergency release valve, not standard operating procedure. Overuse erodes responder's autonomy and questioner's trust.

---

## Meta-Communication: Talking About How You're Talking

### When to go meta

**Signals that meta-communication is needed**:
- Same exchange pattern is failing repeatedly
- Frustration is escalating despite good-faith attempts
- Neither party knows why communication is stuck
- The *way* you're talking is creating more problems than the content

**Pattern**: "Let's pause and talk about how we're talking"

This explicitly shifts conversation from object-level (the question content) to meta-level (the communication pattern itself).

---

### Meta-level diagnostic questions

When you've gone meta, these questions help diagnose the friction:

**"What's making this question hard to answer?"**
- Opens space for responder to name the structural difficulty
- Could be: ambiguous intent, too many dimensions, unstated assumptions, missing constraints, mixed emotional/informational layers

**"What do you actually need from me right now?"**
- Cuts through literal question to underlying need
- Could be: reassurance, permission to choose, help structuring options, acknowledgment of difficulty, just a fast answer

**"Are we trying to solve the same problem?"**
- Checks for goal alignment
- Often reveals questioner wants X (logistical closure) while responder is solving for Y (diagnostic accuracy)

**"What would a satisfying answer look like to you?"**
- Makes implicit expectations explicit
- Could be: three options with tradeoffs, yes/no with reasoning, acknowledgment of uncertainty, confidence bounds, emotional validation

**"Is this question carrying multiple intents?"**
- Uses Section 6.2 vocabulary to check for mixed intent
- Could be: logistical + emotional, diagnostic + planning, social + emotional

---

### Meta-level repair strategies

Once you've diagnosed why communication is stuck, these strategies help repair:

**Name the pattern you've fallen into**:
- "I think we're in a loop where I'm giving you thorough answers and you're getting frustrated that I won't just pick something."
- "I notice I keep asking you to choose, and you keep asking me for more information. I don't think either of us is getting what we need."

**Propose a different approach**:
- "Let's try this instead: I'll give you my top 2 choices and why I'm stuck between them, then you tell me which one aligns better with your priorities."
- "What if I answer the logistical question first (my fast answer: yes), then separately we can talk about my concerns (diagnostic layer)?"

**Check if the question is actually answerable**:
- "I'm wondering if this question can be answered the way it's framed, or if we need to reframe it entirely."
- "This might be a question that doesn't have a clean answer right now—should we figure out what we'd need to know first?"

**Acknowledge the difficulty explicitly**:
- "This is a genuinely hard question—not because either of us is communicating poorly, but because the decision space is complex. Let's acknowledge that before continuing."
- "I realize I'm asking you for something that might not be possible given the constraints. Help me understand what is possible."

---

### Example: Full meta-communication exchange

**Context**: Partner asks "Do you want to have kids?" Responder is stuck, questioner is getting hurt by non-answer, pattern is repeating.

**Questioner**: "Let's pause—I've asked this several times and you haven't answered, and I'm starting to feel like you're avoiding it. Can we talk about why this question is hard?"

**Responder**: "I do want to answer, but every time you ask, I get stuck analyzing all the implications—financial, lifestyle, relationship, existential. I know you need an answer, but I can't get to a stable position."

**Questioner**: "Okay, that helps. What would make it easier to answer? Is the question itself wrong, or do you need more structure?"

**Responder**: "I think part of the problem is I don't know if you're asking for my current position, my ideal scenario, or my prediction of what we'll decide together. Those are different questions."

**Questioner**: "Ah. I'm actually asking: right now, based on everything you know, are you leaning toward yes or no? I'm not asking for a final commitment or perfect certainty. I need to know your current lean so I can understand if we're roughly aligned."

**Responder**: "That I can answer: I'm currently leaning yes, but I'm nervous about timing and whether we're ready. Like, 60% yes, 40% not yet."

**Questioner**: "Thank you—that's actually really helpful. The 60/40 tells me we're aligned enough to keep talking about this, even if we're not ready to decide."

**What this example shows**:
- Meta-level pause stopped the stuck pattern
- Diagnostic questions revealed multiple issues: intent ambiguity, uncertainty about answer format, implicit expectations
- Both parties collaborated on restructuring
443: - Final answer was "simplified" (60/40) but satisfied the actual need (alignment check, not perfect certainty)
- Relationship strengthened by successful navigation of difficult question

---

## Negotiation Patterns by Context

### Professional contexts

**Default bias**: Toward logistical/planning intents, okay to compress aggressively, meta-communication is common practice in functional teams.

**Effective negotiation phrases**:
- "Let me know if you need the detailed version or just the decision"
- "This sounds like you need triage—let me give you the urgent items first"
- "Should we schedule time to dig into this properly, or do you need my quick take?"

**Common failure**: Assuming all questions are logistical and missing emotional/diagnostic needs. Engineers often under-weight emotional intent in team communication.

---

### Intimate relationship contexts

**Default bias**: Questions carry mixed intent more often, emotional layer is almost always present, speed pressure is lower but relationship stakes are higher.

**Effective negotiation phrases**:
- "I think you're asking me two things here—can we separate them?"
- "I want to answer this well—is this about [information] or about [relationship]?"
- "I hear the factual question, but it feels like there's something underneath. Am I missing something?"

**Common failure**: Over-optimizing for informational accuracy while missing emotional need, or over-indexing on emotional reassurance while avoiding necessary difficult conversations.

---

### Casual/social contexts

**Default bias**: Most questions are social intent (relationship maintenance), speed is expected, depth is usually unwelcome.

**Effective negotiation**: Often unnecessary—pattern-match to social norms. Only negotiate if you misread the context or the question unexpectedly requires more depth.

**Example of needed negotiation**:
- Casual friend: "How's your new job?" [Expects: "It's good!"]
- You: "Honestly, it's complicated—do you have a few minutes to actually talk about it, or should I give you the social answer?"
- Friend can choose: "Actually yes, I want to hear" or "Ah, give me the short version for now, we can talk later."

**Common failure**: Giving thorough answers to social-intent questions in casual contexts, creating social awkwardness.

---

## When Structure Fails: Graceful Exits

Sometimes negotiation doesn't work and the question remains unanswerable. Graceful exit strategies:

### "I need more time with this question—can I come back to you?"

**When to use**: You've tried to answer, negotiation happened, you're still stuck but believe time/thinking will help.

**What it communicates**: "This is a real question that deserves a real answer, and I can't generate that answer right now. I'm not avoiding—I need processing time."

**Example**: "I need more time with this question—can I come back to you tomorrow? I want to give you a real answer, not just a dodge."

**Failure mode**: Using this habitually for questions that don't genuinely need time. If you always need more time, the pattern itself needs diagnosis.

---

### "I think I can't answer this question the way it's framed—here's what I could answer instead"

**When to use**: The question is structurally unanswerable for you, but you can identify adjacent questions that you *could* answer.

**What it communicates**: "The literal question isn't working, but I can give you related information that might help. Let's see if that's close enough."

**Example**:
- Question: "Do you love me?"
- Response: "I think I can't answer this question the way it's framed—'love' means different things and I get stuck on definitions. Here's what I could answer instead: Do I want to build a life with you? Yes. Do I feel committed to your wellbeing? Yes. Do I feel that Hollywood-romance immediate certainty? I'm not sure I experience that the way other people do."

**Why this works**: Honest about the limitation, offers alternative routes to similar information, doesn't pretend the question is answerable when it's not.

---

### "This question is outside my capacity right now—I'm not the right person to ask"

**When to use**: The question requires capabilities or knowledge you don't have, and you need to redirect.

**What it communicates**: "I'm not dodging, but I'm genuinely not equipped to answer this well. Here's who/what might help instead."

**Example**: "This question is outside my capacity right now—you're asking me to assess security implications and I'm not qualified to do that. We should ask [security expert] or schedule a proper security review."

**Why this works**: Clarifies the limitation is capability, not willingness; redirects to appropriate resource.

---

### "I've tried several ways to answer this and I'm stuck—I need help understanding what's blocking me"

**When to use**: You're stuck, you don't know why, and you need external help diagnosing your own difficulty.

**What it communicates**: "I'm committed to answering, but I need collaborative diagnosis. Something about this question is triggering my paralysis and I can't see it from inside."

**Example**: "I've tried several ways to answer this and I'm stuck—I need help understanding what's blocking me. Every time I start to answer, I spiral into uncertainty. What do you think the question is actually asking for?"

**Why this works**: Vulnerability and collaborative problem-solving, shows effort and good faith, invites the other person to help debug.

---

## Connection to Larger Framework

**Real-time negotiation is the lubricant** that makes techniques (Section 4.1) and protocols (Sections 5.1 and 5.2) usable in messy reality. Without negotiation vocabulary:
- Techniques are theoretical (you know they exist but can't deploy them in conversation)
- Protocols are rigid (wrong protocol selection breaks communication)
- Intent taxonomy is descriptive only (you can recognize intent mismatch but can't repair it)

**With real-time negotiation**:
- Techniques become selectable in the moment ("I can give you a fast answer or thorough answer")
- Protocols become flexible (you can switch mid-conversation when initial selection was wrong)
- Intent taxonomy becomes actionable (you can check intent explicitly and recalibrate)

**Upcoming sections build on negotiation foundation**:
- Section 6.3 (Confidence Expression) shows how to negotiate uncertainty/confidence levels
- Section 7 (Intimate Relationships) explores negotiation in high-stakes emotional contexts
- Section 11 (Worked Examples) shows full exchanges with negotiation moments

Real-time negotiation is the skill that makes everything else work in practice. It's the difference between knowing communication theory and being able to repair communication breakdowns as they happen.
