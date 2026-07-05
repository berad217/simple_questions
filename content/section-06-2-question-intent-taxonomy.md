# Section 6.2: Question Intent Taxonomy

## What This Section Is For

"Where do you want to eat?" can be five different questions depending on what the asker actually needs. If you struggle to answer questions or receive confusing responses, you may be solving for the wrong intent. Read this to learn how to identify what a question is really asking for and calibrate your response accordingly.

After reading this, you should be able to recognize which type of intent a question serves, adjust your expectations for different intent types, and spot when miscommunication stems from intent mismatch rather than content confusion.

---

## Why Intent Recognition Matters

The same literal question serves different functions depending on what the questioner needs. "Where do you want to eat?" could mean:

- **Logistical**: "Pick a restaurant so I can make a reservation" (needs: decision, timeline)
- **Emotional**: "I want you to feel cared for" (needs: acknowledgment, connection)
- **Diagnostic**: "What's causing your food preferences lately?" (needs: accurate analysis)
- **Planning**: "What constraints should we consider for dinner?" (needs: option space, tradeoffs)
- **Social**: "I'm checking if you're still engaged in this conversation" (needs: responsiveness signal)

High-dimensional responders often receive the literal question and solve for diagnostic or planning intent—providing thorough analysis when the questioner needed a fast logistical answer. This creates friction not because the response is wrong, but because it's optimized for the wrong goal.

Intent mismatch explains many "simple question" failures. The responder isn't overthinking; they're solving a different problem than the one the questioner posed.

---

## The Five Intent Types

### Logistical Intent: Coordinate Action

**What the questioner needs**: A concrete decision or piece of information to enable the next action. Speed and closure matter more than perfect accuracy.

**What the responder hears**: An open-ended question that could go many directions, each with different implications.

**Expectation calibration**:
- **Questioner expects**: Answer in seconds to minutes, good-enough precision, willingness to revise later if needed
- **Responder naturally provides**: Comprehensive analysis of options, uncertainty about which factors matter most, reluctance to commit without more information

**Recognition signals**:
- Question includes time pressure ("We need to leave in 10 minutes—where should we go?")
- Questioner has next action blocked ("I can't book the appointment until you tell me your availability")
- Context is routine/low-stakes (choosing a restaurant, picking a meeting time)
- Questioner doesn't ask follow-up questions about your reasoning

**Examples**:

*Professional context*:
- Question: "Should we use the old API or migrate to the new one for this feature?"
- Logistical intent: "I need to assign this ticket—give me a direction so work can start"
- Responder solving diagnostic intent: Analyzes both APIs, lists 8 tradeoff dimensions, asks for more context about long-term architecture plans
- Appropriate response: "New API—it's the strategic direction and this is a good low-risk feature to migrate. We can revisit if we hit blocking issues."

*Intimate context*:
- Question: "What do you want for dinner?"
- Logistical intent: "I'm grocery shopping now—tell me what to buy"
- Responder solving diagnostic intent: Considers nutritional needs, what's in the fridge, meal prep time, recent eating patterns, decision fatigue
- Appropriate response: "Pasta—get marinara sauce and that parmesan we like."

*Casual context*:
- Question: "Are you coming to the party Saturday?"
- Logistical intent: "I need a headcount for food"
- Responder solving planning intent: Evaluates energy levels, other commitments, social capacity, transportation logistics, who else is attending
- Appropriate response: "Yes" or "No, but thanks for inviting me"

**Useful framework moves**:
- **Time-boxing**: "I'll give you my best answer in 30 seconds"
- **Satisficing criteria**: "Good enough means it won't cause problems; I'll say pasta"
- **Meta-response**: "Sounds like you need a quick decision—let me give you one and we can adjust later"

**Connection to Section 5 protocols**:
- Questioner protocol: Declare logistical intent explicitly (Section 5.2: "I need a quick answer to book this—your best guess is fine")
- Responder protocol: Use satisficing response format (Section 5.1: "My fast answer is X, but flag me if that creates problems")

---

### Emotional Intent: Reassurance and Connection

**What the questioner needs**: To feel heard, valued, or emotionally connected. The information content is secondary to the relationship signal.

**What the responder hears**: A factual question requiring an accurate answer.

**Expectation calibration**:
- **Questioner expects**: Acknowledgment of the emotional subtext, responsiveness to the relationship signal, warmth or reassurance
- **Responder naturally provides**: Literal answer to the factual question, potentially missing the emotional need entirely

**Recognition signals**:
- Question follows emotional context (after conflict, during stress, when feeling disconnected)
- Questioner already knows the factual answer or could easily find it
- Question is checking for care/attention rather than information ("Did you think about what I said?")
- Questioner's tone conveys need for reassurance more than data

**Examples**:

*Intimate context*:
- Question: "Do you still want to go on this trip together?"
- Emotional intent: "I'm feeling insecure about us—reassure me you're still invested"
- Responder solving logistical intent: "Yes, I already booked the time off work and bought tickets"
- Appropriate response: "Absolutely, I'm really looking forward to it. Are you worried about something?"
- Note: The appropriate response addresses the emotional need first, then can circle back to logistics if needed

*Professional context*:
- Question: "Do you think this presentation is good enough?"
- Emotional intent: "I'm anxious about this high-stakes meeting—tell me I'm prepared"
- Responder solving diagnostic intent: Points out 6 areas for improvement, suggests restructuring the flow
- Appropriate response: "It's solid—you've covered the key points and anticipated their questions. Want me to do a final run-through with you?"

*Casual context*:
- Question: "Did you get my message earlier?"
- Emotional intent: "I feel ignored—acknowledge that you saw it"
- Responder solving logistical intent: "Yes" [returns to other task]
- Appropriate response: "Yes, sorry I didn't reply yet—got pulled into something. I saw what you said about [topic] and want to talk about it later."

**Critical distinction**: Emotional intent doesn't mean the factual content is irrelevant. It means the relationship signal has higher priority than informational precision. A technically accurate answer that ignores the emotional subtext causes more friction than a warm but slightly imprecise response.

**Useful framework moves**:
- **Response-type declaration**: "I'm hearing this as an emotional check-in, not a logistics question—is that right?"
- **Satisficing for relationship goals**: "The relationship-serving answer is X; want the detailed version too?"

**Connection to Section 5 protocols**:
- Questioner protocol: Name the emotional need (Section 5.2: "I'm feeling anxious and need reassurance, not a critique")
- Responder protocol: Acknowledge emotional layer first (Section 5.1: "Sounds like you need to hear I'm still in—absolutely yes. Want to also talk through the logistics?")

**Common failure mode**: High-dimensional responders often optimize for accuracy and miss the emotional intent entirely. They perceive the question as informational, provide a thorough factual answer, and wonder why the questioner seems hurt or dissatisfied. Recognizing emotional intent prevents this mismatch.

---

### Diagnostic Intent: Root-Cause Analysis

**What the questioner needs**: Accurate understanding of underlying causes, mechanisms, or patterns. Speed is less important than correctness.

**What the responder hears**: Finally, a question that matches their natural processing depth.

**Expectation calibration**:
- **Questioner expects**: Thorough analysis, exploration of multiple factors, acknowledgment of uncertainty where it exists
- **Responder naturally provides**: Exactly what the questioner wants—this is the rare case where high-dimensional processing matches intent

**Recognition signals**:
- Question explicitly asks for analysis ("Why do you think X keeps happening?")
- Questioner asks follow-up questions that go deeper
- Context is troubleshooting, learning, or strategic thinking
- Questioner has time and mental space for a detailed answer
- Question starts with "why" or "what's causing"

**Examples**:

*Professional context*:
- Question: "Why does this service keep timing out under load?"
- Diagnostic intent: "Help me understand the root cause so we can fix it properly"
- Shallow response: "It's a performance problem—we should add more servers"
- Appropriate response: "I see three contributing factors: database query patterns, connection pool configuration, and caching strategy. Let me walk through each..."

*Intimate context*:
- Question: "Why have you been distant lately?"
- Diagnostic intent: "I want to understand what's happening so we can address it"
- Logistical response: "I've been busy with work"
- Appropriate response: "I think it's partly work stress, but also I've been feeling overwhelmed by social obligations and haven't created enough space to recharge. I'm not being distant *at you*, but I see how it lands that way."

*Casual context*:
- Question: "What's making it hard for you to commit to this plan?"
- Diagnostic intent: "Tell me what the actual blockers are"
- Social response: "Oh, I'm just not sure yet"
- Appropriate response: "Two things: I don't know my work schedule yet, and I'm trying to figure out if I have the energy for a big social thing that weekend. Not a no, but those are the uncertainties."

**This is the intent type where high-dimensional processing is appropriate**. The questioner is explicitly asking for the kind of thorough analysis that responders naturally provide. The challenge is recognizing when *other* intent types don't want this level of depth.

**Useful framework moves**:
- Diagnostic intent often requires *fewer* dimensionality-reduction techniques
- **Confidence expression**: Show uncertainty where it exists ("I'm 70% sure it's X, 30% it could be Y")
- **Layered disclosure**: "The quick version is X; want me to explain the contributing factors?"

**Connection to Section 5 protocols**:
- Questioner protocol: Signal that depth is welcome (Section 5.2: "I have time—walk me through your thinking")
- Responder protocol: Check if they want full analysis (Section 5.1: "This connects to several things—want the deep dive or the summary?")

---

### Planning Intent: Decision Support

**What the questioner needs**: Understanding of the option space, tradeoffs, and constraints to make an informed decision. They want exploration of possibilities, not a single recommendation.

**What the responder hears**: Often confused with diagnostic intent, but the goal is forward-looking decision-making rather than backward-looking cause analysis.

**Expectation calibration**:
- **Questioner expects**: Structured presentation of options, clear tradeoffs, help thinking through scenarios
- **Responder naturally provides**: Either over-analysis that explores every possibility without structure, or diagnostic work that focuses on understanding rather than decision-making

**Recognition signals**:
- Question involves future decision ("Should we pursue strategy A or B?")
- Questioner asks about tradeoffs or scenarios ("What if we tried X?")
- Context is evaluating options before commitment
- Question includes "should we" or "what are our options for"

**Examples**:

*Professional context*:
- Question: "Should we build this feature in-house or use a third-party service?"
- Planning intent: "Help me see the decision landscape"
- Diagnostic response gone wrong: Analyzes why we don't already have this, what led to current state
- Appropriate response: "Three options: build in-house (high upfront cost, full control), use Service A (fast, limited customization), use Service B (flexible, complex integration). Main tradeoff is timeline vs. long-term flexibility."

*Intimate context*:
- Question: "Should we move to the city or stay in the suburbs?"
- Planning intent: "Help me think through this decision together"
- Logistical response: "What's your preference?" [trying to close the question quickly]
- Appropriate response: "Let's map it out—city gives us walkability and culture but costs more and feels cramped; suburbs give us space and quiet but we'd need to drive everywhere. Which tradeoffs feel more manageable to you?"

*Casual context*:
- Question: "Should I take this job offer?"
- Planning intent: "Help me evaluate this properly"
- Emotional response: "That sounds great—you should definitely do it!" [reassurance without analysis]
- Appropriate response: "What's drawing you to it, and what's giving you pause? Let's think through salary vs. growth opportunity, commute, team culture..."

**Key distinction from diagnostic intent**: Planning questions are forward-looking (what should we do?) while diagnostic questions are backward-looking (why did this happen?). Planning questions want structured options; diagnostic questions want root causes.

**Useful framework moves**:
- **Dimensional reduction via constraint declaration**: "If we rule out options that require more than 3 months, that leaves us with..."
- **Scenario-based bounds**: "In the optimistic scenario we'd get X, in the pessimistic scenario we'd get Y"
- **Satisficing for decision framing**: "Good enough means we pick something that doesn't close off future options"

**Connection to Section 5 protocols**:
- Questioner protocol: Frame as decision support (Section 5.2: "I'm trying to decide between A and B—help me see the tradeoffs")
- Responder protocol: Offer structured options (Section 5.1: "I see three main paths, each with different tradeoffs. Want me to lay them out?")

---

### Social Intent: Relationship Maintenance

**What the questioner needs**: To maintain conversational flow, show interest, or check for engagement. The specific content is nearly irrelevant—the question serves a social function.

**What the responder hears**: A literal request for information that requires a thoughtful answer.

**Expectation calibration**:
- **Questioner expects**: Brief, socially appropriate response that keeps conversation moving
- **Responder naturally provides**: Substantive answer treating it as genuine information request, or awkward silence while processing

**Recognition signals**:
- Question is formulaic small talk ("How was your weekend?", "What did you think of that movie?")
- Questioner is clearly not invested in detailed answer (asks while doing something else, scrolling phone)
- Context is social lubrication (running into colleague, party small talk, waiting for meeting to start)
- Question is checking for conversational engagement ("You still with me?")

**Examples**:

*Professional context*:
- Question: "How's that project going?"
- Social intent: "I'm showing friendly interest as I walk past your desk"
- Diagnostic response: Stops questioner, explains current technical challenges, uncertainty about timeline
- Appropriate response: "Making progress—hit a tricky part but working through it" [said while continuing to walk, matching their energy]

*Casual context*:
- Question: "What did you think of the party?"
- Social intent: "I'm making conversation while we wait for the elevator"
- Planning response: Analyzes what worked and didn't work, suggests improvements for next time
- Appropriate response: "It was fun—good to see everyone" [sufficient for context]

*Intimate context*:
- Question: "Did you see that article I sent you?"
- Social intent: "I'm checking if you're paying attention to things I share"
- Logistical response: "Not yet" [returns to other task]
- Appropriate response: "Saw the headline, haven't read it yet—want to talk about it over dinner?"
- Note: Even in intimate contexts, some questions are primarily social-maintenance rather than information-seeking

**Critical recognition**: Social intent questions are not trivial or unimportant—they serve real relationship and conversational functions. The error is treating them as information requests and providing answers calibrated for diagnostic or planning intent.

**Useful framework moves**:
- **Social calibration**: Match the energy and depth of the questioner
- **Satisficing for social context**: "Good enough means I acknowledge the question and keep the conversation moving"
- **Response-type declaration**: (Rarely needed—usually just match their level)

**Connection to Section 5 protocols**:
- Questioner protocol: Usually doesn't need special protocol (these are smooth for most people)
- Responder protocol: Recognize when to give "social answer" vs "real answer" (Section 5.1: Notice the context and energy level)

**Common failure mode**: High-dimensional responders often fail to recognize social intent entirely, treat casual small talk as genuine information requests, and provide thorough answers that create social awkwardness. Learning to identify social intent prevents over-investment in questions that serve conversational lubrication.

---

## Mixed-Intent Questions

Most questions in intimate relationships and many in professional contexts carry multiple intents simultaneously. "Where do you want to eat?" from your partner might be 60% logistical (we need to pick a place), 30% emotional (I want to make you happy), 10% social (maintaining conversational engagement). Recognizing mixed intent prevents optimizing for the wrong dimension.

**Signs of mixed intent**:
- Questioner seems dissatisfied with a factually correct answer
- Same question generates different reactions in different contexts
- Emotional undertone doesn't match the literal content
- Questioner asks follow-up questions that shift intent type

**Handling mixed intent**:

**Strategy 1: Address the highest-priority intent first**

Questioner asks: "Do you actually want to go to this wedding with me?"

This carries:
- Emotional intent (primary): "Are you still invested in this relationship / in being my partner for important events?"
- Logistical intent (secondary): "Should I RSVP for two people?"

Responding to logistical only: "Yes, I already put it on my calendar" ← Misses emotional layer, creates hurt

Responding to emotional first: "Of course I want to be there with you for this. Are you worried I don't?" Then, if needed: "And yes, definitely RSVP for both of us."

**Strategy 2: Name the multiple intents you're perceiving**

Questioner asks: "Should we really commit to this big project right now?"

You perceive:
- Planning intent: "Help me think through if timing is right"
- Emotional intent: "I'm feeling overwhelmed and need to know you see that"
- Diagnostic intent: "What's making this feel like too much?"

Response: "I'm hearing a few things here—are you asking whether the project is strategically sound, or whether we have the capacity for it right now, or something else? Want to unpack which part you're most uncertain about?"

**Strategy 3: Ask which intent to optimize for**

Questioner asks: "Why didn't you tell me about this earlier?"

Could be:
- Diagnostic: "What caused this communication breakdown?"
- Emotional: "I feel hurt that you didn't include me"
- Social: "Just checking that we're on the same page"

Response: "I want to answer this well—are you asking me to diagnose what happened, or is this more about feeling left out? Those need different responses."

**Common mixed-intent patterns**:

**Pattern 1: Logistical + Emotional**
"What time will you be home?" often means both "I need to plan dinner" (logistical) and "I miss you and want to know you're thinking of me" (emotional).

**Pattern 2: Diagnostic + Planning**
"Why did this approach fail?" often means both "What went wrong?" (diagnostic) and "What should we do differently next time?" (planning).

**Pattern 3: Social + Emotional**
"You still with me?" in a long conversation means both "Checking conversational engagement" (social) and "I need to know you care about what I'm saying" (emotional).

**Failure mode to avoid**: Don't use intent-ambiguity as an excuse to avoid answering. "I'm not sure what you're asking" used repeatedly signals evasion. If truly uncertain about intent, name the 2-3 interpretations you see and ask which matters most.

---

## Practical Application: Using This Taxonomy

**For responders**:

When you receive a question that triggers your high-dimensional processing, pause and ask:

1. **What intent is this question serving?**
   - Logistical: They need a decision to unblock action
   - Emotional: They need reassurance or connection
   - Diagnostic: They want accurate root-cause understanding
   - Planning: They want decision support and tradeoff analysis
   - Social: They're maintaining conversational flow

2. **What technique does this intent require?**
   - Logistical → Satisficing, time-boxing, fast closure
   - Emotional → Acknowledge relationship layer first, then optionally provide information
   - Diagnostic → Your natural mode; show your full thinking
   - Planning → Structure options, make tradeoffs explicit
   - Social → Match their energy, brief response, keep it moving

3. **If uncertain about intent, ask:**
   - "Are you looking for a quick decision or should we think through this properly?"
   - "Is this a 'just pick something' question or a 'help me understand' question?"
   - "Want my fast answer or my thorough answer?"

**For questioners**:

When you ask a question and get a response that doesn't match what you needed:

1. **Check if you signaled your intent clearly**
   - Logistical intent: Add time pressure, say "just need a direction"
   - Emotional intent: Name the feeling ("I'm anxious and need reassurance")
   - Diagnostic intent: Say "I want to understand why"
   - Planning intent: Say "help me think through options"
   - Social intent: Usually clear from context, but if not, keep your energy light

2. **If the response doesn't match, redirect explicitly**
   - "I should have been clearer—I need a fast answer to book this, not a full analysis"
   - "I think what I actually need is reassurance, not a solution"
   - "Let me reframe: I want to understand what caused this, not just fix it quickly"

3. **Notice patterns in which intent types create friction**
   - If logistical questions consistently get thorough analysis, start using time-boxing language
   - If emotional questions get factual answers, practice naming the emotional need directly

**For both**:

The goal is not to eliminate intent ambiguity—real communication is often layered. The goal is to recognize when intent mismatch is creating friction and have vocabulary to repair it. "I think I answered the logistics, but you were asking about the relationship piece—let me try again" is a repair move that prevents escalation.

Intent recognition doesn't mean every conversation requires meta-discussion. It means building pattern-recognition so you can match response to intent automatically for common scenarios, and explicitly check intent for high-stakes or ambiguous situations.

---

## Connection to Larger Framework

**Framework techniques** (dimensionality reduction, response protocols, and confidence formats) work differently depending on intent:
- Logistical intent: Use aggressively to get to closure
- Emotional intent: Secondary to relationship acknowledgment
- Diagnostic intent: Use sparingly, depth is appropriate
- Planning intent: Use to structure option space
- Social intent: Brief responses that match questioner's energy

**Section 5 protocols** (response formats for responders, question formats for questioners) become more powerful when both parties understand intent taxonomy. A questioner who declares "I need a quick logistical answer" is using intent taxonomy. A responder who says "This sounds like you want diagnostic depth—is that right?" is checking intent alignment.

**Upcoming sections** build on this:
- Section 6.1 (Real-Time Negotiation) shows how to negotiate intent mismatches in the moment
- Section 6.3 (Confidence Expression) shows how to calibrate certainty claims per intent type
- Section 7 (Intimate Relationships) explores how intent complexity increases in high-trust contexts

Intent taxonomy is the conceptual layer that makes techniques and protocols selectable. Without understanding *what the question is for*, you can't choose the right approach.
