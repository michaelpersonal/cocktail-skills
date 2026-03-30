# Preparation Modules

## Module: prepare-negotiation

**Purpose**: Build a complete negotiation prep sheet before any conversation.

**When to use**: Before any negotiation that matters — salary discussions, vendor negotiations, stakeholder alignment, scope conflicts.

**Inputs needed**:
- What is the situation?
- Who is the counterpart?
- What do I want?
- What do I think they want?
- What is my walkaway?
- What is my BATNA?

**Method**:
1. State the negotiation in one sentence: "I am negotiating [X] with [Y] because [Z]."
2. Define best outcome, acceptable outcome, and walkaway point.
3. State your BATNA explicitly.
4. List 3-5 things the counterpart likely needs or fears.
5. Identify 2-3 pressures they're under that you can verify or probe for.
6. Draft an accusation audit (3-5 statements starting with "You're probably thinking...").
7. Draft 3 calibrated questions to open or redirect the conversation.
8. Identify one potential black swan — what don't you know that could change everything?
9. Write your opening statement (2-3 sentences max).

**Example output**:
```
Negotiation: Asking VP Engineering to approve hiring a senior engineer for my team.

Best outcome: Approved headcount, backfill posted this quarter.
Acceptable outcome: Approved headcount, posting next quarter.
Walkaway: If denied, escalate with data next planning cycle.
BATNA: Redistribute work across team (unsustainable but buys 3 months).

Counterpart likely needs/fears:
- Under pressure to reduce headcount across org
- Worried about setting precedent for other teams
- Needs to show cost discipline to CFO
- Wants to avoid losing a high performer (me) over resourcing

Accusation audit:
- "You're probably thinking every manager is asking for more headcount right now."
- "You might feel like approving this opens the floodgates."
- "It probably seems like I'm not being creative enough with existing resources."

Calibrated questions:
- "What would you need to see to feel confident this hire pays for itself?"
- "How are you thinking about the tradeoff between short-term cost and attrition risk?"
- "What constraints are you working within that I should understand?"

Black swan to probe: Is there a reorg or budget cut coming that hasn't been announced?

Opening: "I know headcount decisions are tough right now, and I want to make sure I'm not adding noise. I've been looking at our delivery data, and I think there's a case worth your time. Can I walk you through it?"
```

**Failure modes to avoid**:
- Skipping the walkaway definition (you'll concede too much under pressure)
- Writing the accusation audit as a list of complaints rather than acknowledging their perspective
- Preparing a script instead of a framework (conversations never follow scripts)

---

## Module: analyze-counterpart

**Purpose**: Build a mental model of who you're negotiating with.

**When to use**: Before any negotiation where the relationship matters or the stakes are high.

**Inputs needed**:
- Who is this person?
- What is their role and what pressures come with it?
- What is your relationship history?
- What have they said or signaled about this topic?

**Method**:
1. **Role analysis**: What does their job require them to optimize for? What metrics do they answer to?
2. **Stakeholder mapping**: Who do they report to? Who influences them? Whose opinion do they care about?
3. **Communication style**: Are they analytical (wants data), assertive (wants control), accommodating (wants harmony), or creative (wants options)?
4. **Likely concerns**: List 3-5 things they're probably worried about in this specific negotiation.
5. **Likely constraints**: What can't they do even if they wanted to? (Budget caps, policy, precedent, authority limits.)
6. **Emotional drivers**: What would make them feel good about saying yes? What would make them feel nervous?
7. **Black swan candidates**: What might they know that you don't? What context are you missing?

**Example output**:
```
Counterpart: Sarah Chen, VP Product

Role optimization: Ship roadmap on time, maintain stakeholder confidence, manage team capacity.
Reports to: CTO (who is under board pressure to show velocity).
Influenced by: Engineering leads, design director, key customer accounts.

Style: Analytical with assertive tendencies. Wants data first, then wants to move fast.

Likely concerns:
- My request will delay Q3 roadmap commitments
- She'll have to renegotiate with sales on delivery dates
- Other teams will ask for similar exceptions

Likely constraints:
- Q3 commitments already shared with board
- Can't add headcount without CFO approval
- Design team is already at capacity

Emotional drivers:
- Would feel good about: finding a creative solution that doesn't require renegotiation
- Would feel nervous about: looking like she can't manage competing priorities

Black swan candidates:
- Is there a priority shift coming from the CTO that would reprioritize anyway?
- Has another team already asked for the same thing?
```

**Failure modes to avoid**:
- Projecting your own motivations onto them
- Assuming malice when the real driver is constraint
- Ignoring their stakeholder pressures (they may agree with you but can't say yes)

---

## Module: write-negotiation-brief

**Purpose**: Create a concise document that captures your complete negotiation strategy on one page.

**When to use**: Before any negotiation worth preparing for. Share with trusted advisors for feedback.

**Inputs needed**: Outputs from prepare-negotiation, analyze-counterpart, and relevant tactic modules.

**Method**: Compile into this format:

```
NEGOTIATION BRIEF

Situation: [1 sentence]
Counterpart: [Name, role, key characteristics]
My objective: [Specific, measurable]
Their likely objective: [Best guess]
My walkaway: [Specific line]
My BATNA: [Best alternative]

WHAT I KNOW
- [Key facts about their position, constraints, pressures]

WHAT I DON'T KNOW (BLACK SWAN CANDIDATES)
- [2-3 things that could change everything]

ACCUSATION AUDIT
- [3-5 preemptive acknowledgments]

MY OPENING
- [2-3 sentence opening statement]

CALIBRATED QUESTIONS
- [3-5 prepared questions]

IF THEY PUSH BACK
- [2-3 prepared responses]

SUCCESS LOOKS LIKE
- [Specific outcome + how I'll confirm it's real]
```

**Failure modes to avoid**:
- Making the brief longer than one page (if you can't fit it on one page, you haven't distilled your thinking enough)
- Not updating the brief after the conversation (capture what you learned for next time)
