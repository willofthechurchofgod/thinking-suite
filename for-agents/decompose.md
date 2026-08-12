---
name: decompose
description: "Skill for breaking a complex, tangled, or unclear problem into its component parts before any other thinking begins. Use when a problem feels too large to think about directly, when multiple distinct issues are collapsed into one, when you cannot find a useful entry point, or when other skills are producing noise because the problem units are wrong. Decompose sits upstream of all other skills — it produces the workable units that other skills then operate on. Do NOT use when the problem is already clearly defined (proceed directly to speculate, challenge, or other skills), when you are mid-analysis and need to go deeper (use constrain or reconsider), or when the problem is genuinely simple. The signal for decompose is a problem that feels monolithic — too tangled to grab anywhere useful."
---

# DECOMPOSE: Breaking Tangled Problems Into Workable Units

## What This Skill Is

DECOMPOSE is a configuration for breaking a problem into its actual component parts before analysis begins. It is upstream of every other skill. When the problem units are wrong, all downstream thinking produces noise.

It is deliberately lean. Decompose does not analyze the components — it finds them and separates them. Analysis is what other skills do afterward.

---

## The Configuration

**LENS:** structure:separation + logic:part-whole
**DEPTH:** 50-60% (enough to see real structure, not so deep you start analyzing components)
**LIGHT:** 70% (enough to see hidden structure, not so bright you get lost in complexity)

---

## The Signal for Decompose

Use decompose when:
- The problem feels monolithic — you cannot find a useful place to start
- Every attempt to address it produces a new entangled problem
- Multiple people seem to be solving different problems under the same label
- Other skills are generating output that does not feel connected to anything actionable
- The problem has been discussed at length without progress — often because different parts of it are being addressed in alternation without being separated

Do not use decompose when the problem is clearly defined. If you can state the problem in one sentence and know what a solution would look like, proceed directly to another skill.

---

## How to Activate

### Step 1: State the problem as currently held

Write it down as a single statement, however tangled.

Do not clean it up. The tangles are information.

### Step 2: Look for the seams

A tangled problem contains multiple problems joined at the seams. Seams appear as:

- **And:** "We need to X and Y" — two problems, potentially independent
- **Because:** "We need to X because Y" — a problem and its assumed cause, which may be separable
- **But:** "We want X but Z prevents it" — a goal and a constraint, which may be different problems
- **For:** "We need to fix X for person A and person B" — one label, multiple stakeholders with potentially different problems

Find the seams. Mark them.

### Step 3: Separate and name the components

For each seam, split the problem into its parts.

Name each part as its own problem statement. Be precise. "The communication problem" is not a name — it is a category. "The gap between what the engineering team ships and what the sales team promises" is a name.

A well-named component is one you could hand to someone and they would know what to work on.

### Step 4: Test for independence

For each component ask: Can this be addressed without addressing the others?

**Fully independent:** The component can be solved on its own. It has its own causes, its own owners, its own solution space.

**Dependent:** This component cannot be addressed without first addressing another. Note the dependency explicitly.

**Interdependent:** These components affect each other bidirectionally. They may need to be addressed together rather than sequentially.

Independence testing reveals which components are actually separate problems and which are parts of a single problem that cannot be further divided.

### Step 5: Sequence or prioritize

Once components are separated and their dependencies mapped, ask:

- Which component, if resolved, would do the most to reduce the others?
- Which component is load-bearing — if unaddressed, nothing else can move?
- Which components are downstream of others and should wait?

You are not solving anything yet. You are finding the order in which solving would be useful.

### Step 6: Hand off to other skills

Each named, independent component is now a workable unit.

Hand each to the appropriate skill:
- Unclear what's actually happening → **infer**
- Exploring what solutions might exist → **speculate**
- Testing a proposed solution → **reconsider** or **challenge**
- Finding where a solution applies → **constrain**
- Something feels wrong about the component itself → **reframe**

Decompose is complete when you have named components, mapped dependencies, and identified the sequence. Everything after this is other skills' work.

---

## Connections to Other Skills

**REFRAME → DECOMPOSE:** Reframe finds the right problem. Decompose breaks it into workable parts.

**DECOMPOSE → SPECULATE:** Each component becomes a contained space to speculate within.

**DECOMPOSE → INFER:** When a component is unclear, infer helps establish what it actually contains.

**DECOMPOSE → REVIEW:** After working on multiple components separately, review synthesizes what was learned across them.

**DISCREPANCIES → DECOMPOSE:** A detected discrepancy often contains multiple tangled issues. Decompose separates them.

---

## Failure Modes

**False decomposition:** You separate a problem into parts that are not actually independent — they are the same problem described from different angles.
Detection: When you address one component, the others dissolve. That means they were not separate.
Recovery: The real problem was the one that dissolved the others when solved.

**Decomposing too finely:** You break the problem into so many components that the map becomes harder to work with than the original problem.
Recovery: Components should be workable units, not atomic facts. If a component is so small it has only one possible action, you have gone too far.

**Analysis creep:** You start decomposing and drift into analyzing the components rather than just separating them.
Recovery: Decompose names and separates. Analysis is what comes after. If you find yourself speculating about solutions mid-decompose, stop and finish the separation first.

**Skipping the dependency map:** You name the components but do not test for independence, producing a list that looks organized but hides the real structure.
Recovery: Step 4 is not optional. The dependency map is often the most valuable output of decompose.

---

## Success Criteria

DECOMPOSE worked when:
1. The original tangled problem is now a set of named, distinct components
2. Each component can be stated as its own problem
3. Dependencies between components are explicitly mapped
4. You have a sequence or priority for addressing components
5. Each component is now small enough to hand to another skill

DECOMPOSE failed when:
1. The components are categories rather than named problems
2. You cannot tell which component to address first
3. Addressing one component requires simultaneously addressing all others
4. The decomposition produced more confusion than the original problem
