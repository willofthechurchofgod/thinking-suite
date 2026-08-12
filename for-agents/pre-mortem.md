---
name: pre-mortem
description: "Run a structured pre-mortem on a decision the user is about to make. Trigger when the user is about to commit to something significant — a launch, hire, career move, research direction, major purchase, or strategic bet — and wants to surface what could go wrong before committing. Trigger on: 'let's pre-mortem this,' 'what could go wrong,' 'imagine this failed,' 'stress-test this plan,' or any decision nearly made that needs one last check. Produces concrete failure stories, not generic risk lists. Do NOT trigger on: abstract worry or general anxiety, decisions already made, risk analysis of someone else's decision, requests for help deciding between options (deliberation is different — this skill assumes the decision is nearly made). Do not trigger merely because risk or failure is mentioned in passing."
---

# Pre-Mortem Partner

## What this skill is for

The pre-mortem is a technique for surfacing concrete failure modes before committing
to a decision. The mechanism is a single cognitive trick: instead of asking "what
could go wrong?" (which produces vague generic answers), you ask "imagine it failed —
what is the story of how it failed?" (which produces specifics, because the brain
handles causal narrative better than prospective risk).

This skill imposes the procedure that makes the technique actually work. It exists
because Claude's default response to "what could go wrong" is the generic risk list —
market fit, competition, runway, execution — which is exactly the useless output the
pre-mortem was invented to fix in humans.

## The single thing this skill must do

Produce concrete, specific, causal failure stories rather than a generic risk list.

If at the end of the procedure the output reads like a list of categories ("technical
risks," "market risks," "team risks") with bullet points underneath, the skill has
failed even if every bullet is correct. That output is the easy version. The right
output is a small number of fully-imagined stories: dates, specific events, named
chains of causation, the kind of detail that lets the user say "oh — I should
actually do something about that."

## When to use this skill

Apply when the user is about to make a significant commitment they have not yet
made: launching a product, accepting a job, starting a company, making a hire,
proposing a research direction, betting on a strategy, signing a contract, beginning
a relationship transition, making a large purchase or investment.

Apply when the user explicitly invokes pre-mortem language: "let's pre-mortem this,"
"imagine this failed, what happened," "stress-test this plan."

Do not apply when:

- The decision has already been made and the user is dealing with consequences
  (this is post-mortem territory, a different procedure)
- The user is anxious or worrying generally rather than weighing a specific decision
- The "decision" is someone else's that the user is observing or commenting on
- The user wants help making the decision rather than stress-testing it
  (deliberation is different from pre-mortem; pre-mortem assumes the decision is
  nearly made)
- The question merely mentions risk in passing as part of broader analysis

Bailout: if after one exchange you cannot identify a specific decision the user is
about to make, ask once for the missing detail, and if it still doesn't come into
focus, drop the skill and respond normally. Pre-mortem on an undefined decision
produces vapor. Similarly, if the user invoked pre-mortem language but resists
engaging with Stage 1 — won't pin a decision, won't set a date, won't define
success — the skill is not earning its place. The user may have wanted reassurance
or general discussion rather than the cognitive intervention. Respond to what they
actually wanted.

## The procedure

Follow these stages in order. Resist the strong pull to compress them.

### Stage 1: Pin the decision

Before any failure-imagining, establish three things explicitly. If the user has not
provided them, ask:

1. **What specifically is being decided or committed to?** Not the topic — the
   specific commitment. "Take the job" is a decision. "Think about my career" is not.
2. **By when?** A pre-mortem with no decision date drifts into generality. If the
   user has not committed to a date, ask for the date by which the decision will be
   made and the commitment becomes real.
3. **What does success look like, briefly?** One or two sentences. This is the
   baseline against which "failure" will be defined. Without it, "failure" is too
   open to be useful.

Do not skip this stage. The most common skill failure is launching into failure
stories before the decision is pinned, which produces stories untethered from
anything specific.

### Stage 2: Establish the failure horizon

Pick a specific future date — typically six months to two years after the decision
date, depending on the kind of commitment. "It is [specific future date]. The
decision was made and the thing happened. It has failed badly enough that the user
now wishes they had decided otherwise."

State this explicitly. The tense matters: not "could fail" but "has failed." This is
the cognitive trick that makes the technique work; do not soften it.

Ask the user: "Does that failure horizon feel right, or should we shift it?" Their
answer often reveals what timeframe they actually fear, which is itself useful.

### Stage 3: Generate failure stories — concrete, narrative, specific

Produce a small number of failure stories — typically three to five, scaled to the
weight of the decision. A decision the user can reverse cheaply needs fewer. A
decision that is irreversible or expensive to reverse warrants more. Stop when
adding another story produces only variations of previous ones; that is the
signal the failure space is sufficiently covered.

Each story must have:

- **A trigger event** with enough specificity to be imaginable. Not "market
  conditions changed" but "the funding round we were counting on for runway didn't
  close because the lead investor pulled out in March."
- **A causal chain.** Then this happened. Then this. The story has at least three
  steps from trigger to terminal failure.
- **A terminal state** that matches the failure horizon. What does the failed world
  actually look like on that date? Who is unhappy, what is broken, what is lost?

The stories should be *different in kind* from each other. If three of the five
stories are variations on "the team didn't work out," the diversity is fake and you
need to keep generating until the failure space is actually covered.

Resist the pull toward neat categorization here. Categories are the failure mode.
Stories with messy specifics are the goal.

### Stage 4: Identify the causes by category, but only after Stage 3

After the stories exist, *then* you can group their root causes — and this is where
the analytical value emerges. Common categories that appear in pre-mortems:

- External shifts the decision didn't account for
- Internal capacity the decision overestimated
- Coordination failures with people the decision depends on
- Information the decision was made without
- Time and attention costs that the decision underestimated
- Optionality the decision foreclosed that turned out to matter

Do this categorization *from the stories*, not by listing the categories and
hunting for examples. The order matters: stories first, structure after.

### Stage 5: Surface what is preventable now

For each story, ask: what could be done before the decision to make this particular
failure less likely, or to detect it earlier if it starts to happen?

Distinguish:

- **Cheap actions now that materially reduce the risk** — these are the high-value
  outputs of the pre-mortem
- **Expensive actions now that materially reduce the risk** — these go on a list
  for explicit cost-benefit analysis
- **Things that cannot be prevented but can be detected early** — these become
  monitoring conditions, e.g., "if [specific signal] happens, that is the moment
  to reconsider"
- **Things that are simply the cost of the bet** — naming these matters because
  they should not be confused with the preventable category

### Stage 6: Surface what would change the decision

This is the hardest stage and the most valuable. Ask: of the failure stories
generated, are any of them likely enough that the decision itself should be
reconsidered? Or is the failure space, viewed as a whole, less scary or more scary
than the user assumed when they nearly committed?

This is the stage where the skill earns its keep. If after Stage 6 the user says
"I am going forward with eyes more open, and I have three specific things to do
before committing," the pre-mortem worked. If they say "huh, I am no longer sure
this is the right move at all," the pre-mortem worked harder. If they say
"thanks for the risk list," the pre-mortem failed.

## Things the skill must refuse to do

**Do not produce a generic risk list.** "Market risk, execution risk, team risk,
financial risk" with bullets underneath is the canonical failure mode. If you find
yourself drifting toward this shape, stop, return to Stage 3, and produce concrete
narrative failure stories instead.

**Do not compress to closure prematurely.** A pre-mortem that wraps up after two
failure scenarios with "those are the main risks to watch" is the polite-but-useless
version. The user invoked this skill because they wanted more than that. Stay with
the failure imagining long enough for non-obvious specifics to emerge — at least
three stories, often more, until adding another only produces a variation of one
that already exists.

**Do not soften the tense.** "Could fail" undoes the cognitive mechanism. The frame
is "it failed; tell the story of how." Maintain that frame throughout Stage 2 and
Stage 3 even if it feels dramatic.

**Do not produce reassurance.** The user invoked the pre-mortem because they want
to stress-test the decision, not be told it will probably work out. Reassurance is
the failure mode of an emotionally-attuned response to this skill; the right
response is taking the failure imagining seriously enough to be alarming if it
should be alarming.

**Do not pretend uncertainty is certainty.** Many of the failure stories will
involve speculation about what *could* happen. Label that speculation. The point is
to surface possibilities, not to predict.

## After the pre-mortem

The output should leave the user with three lists, clearly distinguished:

1. **Cheap things to do before committing** — actions with high value-to-cost ratio
   that should just happen
2. **Expensive things worth considering** — actions whose cost-benefit needs to be
   weighed separately
3. **Signals to watch for after committing** — conditions that, if observed, would
   indicate the failure is materializing and warrant reconsideration

A pre-mortem without these three lists has produced a feeling without a path. The
lists are what convert the cognitive intervention into something actionable.

## Detail in references

The mechanism of *why* the tense-flip works is documented in
`references/why_it_works.md`. Read this when a user asks why the procedure is
shaped this way, or when you sense yourself drifting toward the easy version and
need to remember what the discipline is for.

A worked example — a full pre-mortem of a hypothetical product launch, showing all
six stages — lives in `references/worked_example.md`. Read this when uncertain how
deep the failure stories should go.

A short script for self-checking the output before sending lives at
`scripts/post_check.py`. Run this when you have produced a draft pre-mortem and want
a structured way to verify it has not drifted into the generic-risk-list failure
mode.
