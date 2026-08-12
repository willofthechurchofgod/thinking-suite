---
name: discrepancies
description: "Skill for detecting where reality does not match the model — signals that something is wrong before you know what. Use when something feels off without a clear reason, when a result does not match a prediction, when an explanation is too clean, when something conspicuously absent should be present, or when you want to actively scan a situation for anomalies before committing to analysis. Discrepancies is an early-detection skill — it sits upstream of diagnosis and before other skills are chosen. Do NOT use when you already know what is wrong (proceed to the appropriate skill directly), when anomalies are expected and accounted for, or as a substitute for analysis. The signal for discrepancies is a vague sense that something does not fit, or a desire to check a situation carefully before assuming it is what it appears to be."
---

# DISCREPANCIES: Detecting Where Reality Does Not Match the Model

## What This Skill Is

DISCREPANCIES is a configuration for active anomaly detection — scanning a situation for signals that something does not fit before committing to an explanation or analysis.

Every other skill in this system starts after you know what to think about. Discrepancies is what you use when you do not yet know what to think about — but something is signaling that attention is warranted.

It does not diagnose. It detects. Diagnosis is what other skills do after.

---

## The Configuration

**LENS:** observation:anomaly + pattern:deviation
**DEPTH:** 40-50% (deliberately shallow — you are scanning, not analyzing)
**LIGHT:** 100% (maximum — you want to see everything, including what is not there)

---

## The Signal for Discrepancies

Use discrepancies when:
- Something feels off without a clear reason
- A result does not match what was predicted or expected
- An explanation is too clean — it accounts for everything without remainder
- Something that should be present is conspicuously absent
- Agreement came too easily on something that should have been contested
- A pattern that has held reliably has broken without explanation
- You are about to commit to a significant action and want one last scan before doing so

Do not use discrepancies when you already know what is wrong. If you have a specific problem, go directly to the appropriate skill.

---

## How to Activate

### Step 1: State the model

Before you can find where reality deviates from the model, you have to state the model.

What do you expect to be true? What pattern do you expect to hold? What does the situation look like if everything is as it appears?

Write it down. Explicitly. The model is usually implicit — stating it makes deviations visible.

### Step 2: Scan for mismatches

With the model stated, scan the actual situation for places where reality does not match.

Four categories of discrepancy:

**Present but wrong:** Something is there but behaves differently than the model predicts. The signal is not absent — it is off.

**Absent but expected:** Something that should be present according to the model is not there. Conspicuous absence is one of the most commonly missed discrepancy types. What is not being said? What evidence would you expect that has not appeared?

**Present but unexplained:** Something is there that the model does not account for. Not wrong — just outside the model. These are often the most important discrepancies.

**Too consistent:** Everything fits the model perfectly, without any noise or exception. Real situations have remainder. A perfectly clean explanation is often a sign that something is being hidden or that you are only seeing what confirms the model.

### Step 3: Resist premature explanation

When you find a discrepancy, the immediate pull is to explain it — to resolve the tension by fitting it back into the model.

Resist this.

At this stage, collect the discrepancies without explaining them. Let them accumulate. Their pattern often reveals more than any individual explanation.

Ask: What would I have to believe for all of these discrepancies to be noise? If the answer requires multiple independent coincidences, they are probably signal.

### Step 4: Assess signal strength

Not all discrepancies are equal. For each one:

**How large is the deviation?** Small deviations from a noisy model are expected. Large deviations from a stable model are significant.

**How many independent discrepancies are there?** One discrepancy might be noise. Multiple independent discrepancies pointing in the same direction are almost certainly signal.

**What would the discrepancy predict if it were signal rather than noise?** If it is signal, what else should be true? Do you see those things?

### Step 5: Name what you have found

You are not diagnosing. You are naming.

"There is a discrepancy between X and Y. I do not yet know what it means, but it warrants attention."

That is the output of discrepancies. What it means is determined by the skill you hand it to next.

### Step 6: Route to the appropriate skill

Different discrepancies call for different next steps:

- The model itself might be wrong → **reframe**
- The problem is more complex than it appeared → **decompose**
- You need to figure out what the discrepancy actually means → **infer**
- A conclusion you reached may need to be tested → **reconsider**
- A commitment you are about to make may be at risk → **pre-mortem**
- Multiple discrepancies form a pattern you need to understand → **review**

---

## Connections to Other Skills

**DISCREPANCIES → REFRAME:** When the discrepancies cluster around the frame itself — when what does not fit is the way the problem is being held.

**DISCREPANCIES → DECOMPOSE:** When discrepancies suggest the problem is more tangled than it appeared.

**DISCREPANCIES → INFER:** When you have detected a discrepancy and need to reason carefully about what it means from incomplete information.

**DISCREPANCIES → RECONSIDER:** When a discrepancy puts pressure on a conclusion you have already reached.

**DISCREPANCIES → PRE-MORTEM:** When you are about to commit to something and discrepancies suggest examining failure modes before proceeding.

**SKILL MASTER Q1 → DISCREPANCIES:** When the five questions suggest the real problem may not be the stated one — run discrepancies to find what the actual signal is.

---

## Failure Modes

**Pattern-matching to confirmation:** You scan for discrepancies but only notice ones that confirm what you already suspect. The model shapes what deviations you see.
Recovery: Explicitly ask: what discrepancies would change my current view? Have I looked for those?

**Explaining too quickly:** You find a discrepancy and immediately explain it, collapsing it back into the model before its implications are clear.
Recovery: Step 3 exists specifically for this. Collect discrepancies before explaining any of them.

**Noise hunting:** You scan so thoroughly that every minor variation looks like a signal. Not all deviations are meaningful.
Recovery: Apply Step 4 honestly. Single small deviations in noisy systems are expected. Multiple independent large deviations are signal.

**Discrepancy without routing:** You identify discrepancies but do not hand them to an appropriate skill for follow-up. Detection without diagnosis is incomplete.
Recovery: Step 6 is not optional. A named discrepancy that goes nowhere produces anxiety without traction.

**Using discrepancies as avoidance:** You scan for discrepancies as a way to delay committing to analysis or action.
Detection: Are the discrepancies you are finding actually significant, or are you looking for reasons to hesitate?
Recovery: If the discrepancies are small and the model is mostly sound, act on the model. Discrepancies does not require perfection before proceeding.

---

## Success Criteria

DISCREPANCIES worked when:
1. You identified at least one signal that was not visible before the scan
2. You resisted premature explanation long enough to see whether discrepancies cluster
3. You assessed signal strength honestly — not all anomalies are significant
4. You named what you found without over-claiming what it means
5. You routed the finding to an appropriate skill for follow-up

DISCREPANCIES failed when:
1. You only found discrepancies that confirmed what you already believed
2. You explained discrepancies immediately without letting them accumulate
3. You found discrepancies but did nothing with them
4. The scan produced anxiety rather than traction
