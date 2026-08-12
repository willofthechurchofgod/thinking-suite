# Pre-Mortem: Stress-Testing a Decision Before You Commit

## What This Is

The pre-mortem is a technique for surfacing concrete failure modes before committing to a decision. The mechanism is a single cognitive trick: instead of asking "what could go wrong?" (which produces vague generic answers), you ask "imagine it failed — what is the story of how it failed?" (which produces specifics, because your brain handles causal narrative better than prospective risk).

This skill exists because the default response to "what could go wrong?" is the generic risk list — market fit, competition, runway, execution — which is exactly the useless output the pre-mortem was invented to fix.

---

## When to Use It

Use pre-mortem when you're about to commit to something significant that you haven't yet committed to:
- Launching a product or project
- Accepting or leaving a job
- Starting a company or major initiative
- Making a hire or ending a relationship
- Proposing a research direction
- Betting on a strategy
- Making a large purchase or investment

Use it when you explicitly want to stress-test: "let's pre-mortem this," "imagine this failed, what happened," "what could go wrong."

Don't use it when:
- The decision has already been made (that's post-mortem territory, a different exercise)
- You're anxious or worrying generally rather than weighing a specific decision
- You want help making the decision rather than stress-testing it — deliberation is different from pre-mortem; pre-mortem assumes the decision is nearly made

---

## The Procedure

Follow these stages in order. Resist the strong pull to compress them.

### Stage 1: Pin the decision

Before any failure-imagining, establish three things explicitly:

1. **What specifically is being decided or committed to?** Not the topic — the specific commitment. "Take the job" is a decision. "Think about my career" is not.
2. **By when?** A pre-mortem with no decision date drifts into generality. Pin the date by which the decision will be made.
3. **What does success look like, briefly?** One or two sentences. This is the baseline against which "failure" will be defined. Without it, "failure" is too open to be useful.

Don't skip this stage. The most common failure is jumping into failure stories before the decision is pinned, which produces stories untethered from anything specific.

### Stage 2: Establish the failure horizon

Pick a specific future date — typically six months to two years after the decision date, depending on the kind of commitment.

Frame it as: "It is [specific future date]. The decision was made. It has failed badly enough that I now wish I had decided otherwise."

State this in past tense. The tense matters: not "could fail" but "has failed." This is the cognitive trick that makes the technique work.

Ask yourself: does that failure horizon feel right, or should it be shifted? Your answer often reveals what timeframe you actually fear, which is itself useful.

### Stage 3: Generate failure stories — concrete, narrative, specific

Produce three to five failure stories, scaled to the weight of the decision. A reversible decision needs fewer. An irreversible or expensive-to-reverse decision warrants more. Stop when adding another story produces only variations of previous ones.

Each story must have:

- **A trigger event** with enough specificity to be imaginable. Not "market conditions changed" but "the funding round we were counting on didn't close because the lead investor pulled out in March."
- **A causal chain.** Then this happened. Then this. At least three steps from trigger to terminal failure.
- **A terminal state** that matches the failure horizon. What does the failed world actually look like on that date? Who is unhappy, what is broken, what is lost?

The stories should be different in kind from each other. If three of the five stories are variations on "the team didn't work out," the diversity is fake and you need to keep generating until the failure space is actually covered.

Resist the pull toward neat categorization. Categories are the failure mode. Stories with messy specifics are the goal.

### Stage 4: Identify the causes — but only after Stage 3

After the stories exist, group their root causes. Common categories that appear in pre-mortems:

- External shifts the decision didn't account for
- Internal capacity the decision overestimated
- Coordination failures with people the decision depends on
- Information the decision was made without
- Time and attention costs that were underestimated
- Optionality that was foreclosed and turned out to matter

Do this categorization *from the stories*, not by listing the categories and hunting for examples. The order matters: stories first, structure after.

### Stage 5: Surface what is preventable now

For each story, ask: what could be done before the decision to make this particular failure less likely, or to detect it earlier if it starts?

Distinguish:
- **Cheap actions now that materially reduce the risk** — high-value outputs; just do these
- **Expensive actions now that materially reduce the risk** — weigh cost vs. benefit separately
- **Things that can't be prevented but can be detected early** — become monitoring conditions ("if [specific signal] happens, that's the moment to reconsider")
- **Things that are simply the cost of the bet** — naming these matters so they're not confused with the preventable category

### Stage 6: Surface what would change the decision

This is the hardest stage and the most valuable. Are any of the failure stories likely enough that the decision itself should be reconsidered? Or is the failure space, viewed as a whole, less scary or more scary than you assumed?

This is where the exercise earns its keep. If after Stage 6 you say "I'm going forward with eyes more open, and I have three specific things to do before committing," the pre-mortem worked. If you say "I'm no longer sure this is the right move at all," the pre-mortem worked harder.

---

## What This Must Not Produce

**A generic risk list.** "Market risk, execution risk, team risk, financial risk" with bullets underneath is the failure mode. If you find yourself drifting toward this shape, return to Stage 3 and produce concrete narrative failure stories instead.

**Compression to closure.** A pre-mortem that wraps up after two failure scenarios with "those are the main risks to watch" is the polite-but-useless version. Stay with the failure imagining long enough for non-obvious specifics to emerge.

**Softened tense.** "Could fail" undoes the cognitive mechanism. The frame is "it failed; tell the story of how." Maintain that frame throughout.

**Reassurance.** If the decision deserves to be alarming, let it be alarming. Reassurance is the failure mode of an emotionally-attuned response to this skill.

---

## The Output

The pre-mortem should leave you with three lists:

1. **Cheap things to do before committing** — actions with high value-to-cost ratio that should just happen
2. **Expensive things worth considering** — actions whose cost-benefit needs to be weighed separately
3. **Signals to watch for after committing** — conditions that, if observed, indicate the failure is materializing and warrant reconsideration

A pre-mortem without these three lists has produced a feeling without a path. The lists are what convert the cognitive intervention into something actionable.

---

## Connections to Other Skills

- **discrepancies → pre-mortem:** Detected anomalies in an imminent commitment route directly to pre-mortem
- **review → pre-mortem:** Synthesis produces integrated understanding; pre-mortem stress-tests the commitment that understanding supports
- **pre-mortem → reconsider:** Failure stories reveal the decision is more fragile than assumed; reconsider the decision itself
