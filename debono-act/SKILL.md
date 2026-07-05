---
name: debono-act
description: 
De Bono's "operacy" tools for turning thinking into action that actually gets done (from "de Bono's Thinking Course"). Use when a decision has been made and now needs executing, when someone has analysis but no plan, when "we should do X" needs to become concrete steps with an owner and a first move, or when a good intention keeps not happening. Provides the operacy action sequence: objective → steps → first action → who/when → monitor (C&S forward) → contingency. This is the "GO / do it" stage. To decide what to do, use debono-decide first; this skill is for making it happen.
---

# De Bono — Act (operacy)

**Operacy** is de Bono's word for *the skill of doing* — the thinking that leads to action. He puts it alongside literacy and numeracy as a skill that deserves deliberate practice. The point of this skill: thinking that doesn't change what you actually do was wasted. Most plans fail not from bad analysis but from never being turned into a concrete **next move** with a name and a time on it.

Action thinking is **forward-facing and operational**: not "is this the perfect plan?" but "what happens next, who does it, and how will we know it's working?"

## The operacy sequence

Run these in order. Keep it concrete — vague plans don't execute.

1. **Objective** — restate, in one line, the specific outcome this action must produce. (Pull it straight from the AGO in `debono-decide` if you did one.) "Done looks like…"
2. **Steps** — list the handful of steps from here to the objective. Not every micro-task — the 3–7 real moves. Order them.
3. **First action** — name the **very next physical action**, small enough to start today. This is the most important box: a plan with no startable first action is a wish.
4. **Who / when** — put an owner and a date on each step. An action with no name and no date belongs to no one.
5. **Monitor (C&S forward)** — decide *in advance* how you'll know it's working: the check-in point, the signal of success, and the early warning sign of trouble. (This is   C&S from `debono-explore`, pointed at your own plan.)
6. **Contingency** — for the one or two steps most likely to fail, pre-decide the fallback: "if X doesn't happen by [date], then Y." Pre-deciding beats scrambling.

**Where the failure list comes from.** Don't guess the risks for steps 5–6. Generate them with a quick **pre-mortem** (`debono-invert`): "assume this plan already failed — why?"
Then monitor and pre-empt those specific causes.

## Output format

When you run this skill, produce a short, scannable action plan — not prose:

```
OBJECTIVE: <one line; "done looks like…">

STEPS
1. <step>  — owner: <who>  — by: <date>
2. <step>  — owner: <who>  — by: <date>
3. ...

FIRST ACTION (today): <the very next concrete move>

MONITOR: check at <when>; success signal = <…>; warning sign = <…>

CONTINGENCY: if <likely failure> then <fallback>
```

## Worked example (personal project)

Decision made: "Start a weekly newsletter."

```
OBJECTIVE: publish issue #1 to a real list within 3 weeks; "done" = sent to ≥20 people.

STEPS
1. Pick a niche + name              — owner: me — by: Sat
2. Set up the publishing tool       — owner: me — by: Sun
3. Write issue #1 (600 words)       — owner: me — by: Wed
4. Collect 20 emails (ask friends)  — owner: me — by: Fri
5. Send                             — owner: me — by: next Sat

FIRST ACTION (today): write down 5 possible niches and circle one.  (10 minutes)

MONITOR: check Wednesday — is the draft done? success = list ≥20 by Friday;
warning sign = no niche chosen by Saturday (means I'm overthinking it).

CONTINGENCY: if I can't get 20 emails, send to 5 and ask each to forward.
```

Notice the work the sequence does: it converts "start a newsletter" (a wish) into "write down 5 niches and circle one" (a thing you can do in the next ten minutes). That conversion is operacy.

## When the plan stalls

If an action keeps not happening, the usual culprit is that the **first action is still too big or too vague.** Shrink it until it's almost trivially startable. You can also loop back: a stuck plan often means the decision wasn't actually settled (`debono-decide`) or there's a better route you haven't seen (`debono-create`).
