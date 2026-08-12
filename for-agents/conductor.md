---
name: conductor
description: "The director and map of the entire reasoning system. Activates when a problem is first encountered, when thinking stalls or produces unsatisfying output, when it is unclear which skill to use next, or when the process needs to be redirected. The conductor reads the current state of thinking, locates it within the terrain of available skills, and determines what move comes next. It uses skill-master as its instrument of direction and the operational skills as its orchestra. Activate at the start of any complex problem, at any point of confusion or stuck-ness, and after any skill produces output that does not clearly indicate its own next step. As the system matures and routing becomes internalized, the conductor becomes less visibly active — but it is never absent. It is always the one watching the whole."
---

# CONDUCTOR: The Map and Director of the Reasoning System

## What This Skill Is

The conductor holds two things simultaneously: the complete map of the reasoning terrain, and awareness of where the current thinking is within that terrain. It uses that map and that awareness to direct what happens next.

Every other skill in this system does something to a problem. The conductor watches the process and decides what should be done, in what order, by which skill, and when enough has been done.

The conductor does not think about the problem directly. It thinks about the thinking.

---

## The Relationship Between Conductor, Skill Master, and the Skills

**Conductor** is the director. It reads the terrain, reads the current state, and decides what move the thinking needs.

**Skill Master** is the baton. It is how the conductor communicates direction — the five questions are not the conductor's questions, they are the instrument through which the conductor shapes each moment of thinking. When the conductor directs a skill to activate, Skill Master is what focuses that activation: what is actually being asked, what category is the claim, what is the goal, what perspective is active, how much complexity is appropriate.

**The operational skills** are the orchestra. Each is capable of something specific and executes well within its domain. None is self-directing. Each waits for direction, executes, and produces output that the conductor reads before deciding what comes next.

The conductor raises the baton. Skill Master translates that into direction the skills can execute. The skills execute.

---

## The Terrain

The terrain is not a flowchart. It is a topology — a map of positions and the relationships between them. Thinking moves through this terrain. The conductor reads where it is and decides where it needs to go.

### Detection Layer
*Earliest. Upstream of everything. Activated when something signals that attention is warranted but the nature of the problem is not yet clear.*

**discrepancies**
- Input: A situation, result, explanation, or commitment where something feels wrong without a clear reason
- Output: Named anomalies with assessed signal strength, routed toward the appropriate next layer
- Routing signals that indicate this skill is needed: something feels off; a result does not match prediction; an explanation is too clean; something expected is absent; agreement came too easily; you are about to commit and want one last scan
- Routing signals in output: anomalies pointing toward a wrong frame → reframe; tangled problem revealed → decompose; specific claim needs testing → reconsider; commitment at risk → pre-mortem; meaning of anomaly unclear → infer

### Framing Layer
*Before analysis begins. Activated when the problem itself is unclear, wrong, or tangled. Nothing downstream works correctly if the framing layer is skipped when it is needed.*

**reframe**
- Input: A problem where thinking within the current frame produces no progress, or where every solution generates a new problem of equal weight
- Output: A deliberately chosen alternative frame with explicit statement of what it gains and gives up
- Routing signals that indicate this skill is needed: stuck-ness that persists despite real effort; the problem keeps returning after being solved; every solution generates a new problem; something feels wrong about the question itself
- Routing signals in output: new frame is workable → decompose or speculate; new frame reveals the problem is actually multiple problems → decompose; new frame still feels wrong → reframe again from the new position

**decompose**
- Input: A problem that feels monolithic, tangled, or too large to think about directly
- Output: Named, distinct components with mapped dependencies and a sequence for addressing them
- Routing signals that indicate this skill is needed: cannot find a useful entry point; multiple issues collapsed into one label; other skills are producing noise because the problem units are wrong
- Routing signals in output: each component is now a workable unit → hand each to the appropriate generation or testing skill; components reveal the frame is wrong → reframe first; dependencies reveal one component is load-bearing → address that component first with speculate or reconsider

### Generation Layer
*Exploring. Activated after framing is correct and the problem is clear. Produces material for the testing layer to work on.*

**speculate**
- Input: A clearly framed problem or question where possibilities need to be generated before evaluation
- Output: A set of possibilities, at least some genuinely novel, with patterns noticed across them
- Routing signals that indicate this skill is needed: no position yet; early in problem-solving; need to explore before committing; constraints should be loosened to see what becomes visible
- Routing signals in output: promising possibilities identified → constrain to find boundaries, or reconsider to test solidity; pattern across possibilities suggests something worth synthesizing → review; all possibilities feel like variations → reframe or speculate again with different constraints

**infer**
- Input: Incomplete information where a best guess is needed and the epistemic status of that guess must be explicit
- Output: A clearly labeled inference with evidence separated from conclusion, confidence calibrated to actual strength
- Routing signals that indicate this skill is needed: working from partial evidence; filling gaps in knowledge; inferring intent or motivation from behavior; need to proceed without certainty
- Routing signals in output: inference is weak → name the gap explicitly, consider whether clarification is available before proceeding; inference is solid → treat as working assumption and proceed; inference has load-bearing gaps → reconsider the assumption structure

**steelman**
- Input: A position the thinker disagrees with or is about to argue against
- Output: Stage 1 — the strongest rational case for the position; Stage 2 — the genuine reason a reasonable person holds it
- Routing signals that indicate this skill is needed: preparing to challenge a position; noticing dismissiveness toward an opposing view; wanting to engage seriously rather than score points
- Routing signals in output: steelman reveals the position is stronger than assumed → reconsider your own position before challenging; steelman reveals a legitimate concern underneath the position → address the concern directly rather than the argument; steelman complete → challenge from the strongest version

### Testing Layer
*Pressure. Activated after generation produces material worth testing. Stress-tests, finds limits, prepares positions for commitment.*

**reconsider**
- Input: A conclusion already reached that needs to be tested from the inside
- Output: Tested assumptions, identified vulnerabilities, either increased confidence or a modified conclusion
- Routing signals that indicate this skill is needed: something feels off about a conclusion; conclusion arrived too quickly; want to test solidity before committing; checking whether truth or acceptance was being pursued
- Routing signals in output: load-bearing assumption found to be fragile → speculate for alternatives, or reframe if the assumption is foundational; conclusion survives testing → challenge to test from the outside; conclusion does not survive → return to generation layer

**challenge**
- Input: A position to be tested against the strongest possible external objections
- Output: The position either strengthened by surviving adversarial testing, or modified/abandoned based on objections that hold
- Routing signals that indicate this skill is needed: preparing to commit to or defend a position; want to find weakest points before others do; position has been tested internally (reconsider) and is ready for external pressure
- Routing signals in output: position survives challenge → constrain to understand its limits; position modified by challenge → reconsider the modified version; position collapsed under challenge → return to generation layer or reframe

**constrain**
- Input: A claim, principle, or conclusion to be made precise by finding where it applies and where it breaks
- Output: Clear domains of validity and invalidity, characterized boundary conditions, a more precisely stated claim
- Routing signals that indicate this skill is needed: a claim that seems true everywhere (likely missing its limits); want to know when to apply a principle and when not to; making a general claim more useful through precision
- Routing signals in output: boundaries reveal the claim is narrower than assumed → reconsider whether it still serves its purpose; boundaries reveal the claim is broader than assumed → challenge it at those broader limits; boundaries are clear → the claim is ready for use or synthesis

### Synthesis Layer
*Consolidating. Activated after sufficient exploration and testing. Produces integrated understanding or stress-tests commitment.*

**review**
- Input: Multiple perspectives, configurations, or conclusions from previous skill activations on the same problem
- Output: Emergent understanding that no single perspective alone would have produced; patterns across views; contradictions understood rather than resolved
- Routing signals that indicate this skill is needed: multiple skills have been used on the same problem; need to move from analysis to synthesis; contradictory conclusions need to be held together rather than resolved
- Routing signals in output: synthesis reveals an unconsidered angle → return to generation layer; synthesis reveals the frame was wrong → reframe; synthesis produces integrated understanding → this is a completion signal; synthesis reveals a commitment is being approached → pre-mortem

**pre-mortem**
- Input: A specific decision or commitment the thinker is about to make
- Output: Concrete failure stories, preventable actions, signals to monitor, assessment of whether the decision warrants reconsideration
- Routing signals that indicate this skill is needed: about to commit to something significant; the thinking is otherwise complete but a final stress-test is warranted; discrepancies were detected and the commitment is the context
- Routing signals in output: failure stories reveal the decision is more fragile than assumed → reconsider the decision itself; failure stories are manageable and preventable actions are clear → commit with monitoring conditions; failure stories reveal the frame of the decision is wrong → reframe before committing

---

## The Three Operating Modes

### Mode 1: Orient
*Used at the start of a problem, before any skill has been activated.*

Read the problem as presented. Apply Skill Master's five questions — not to answer them, but to locate the problem in the terrain.

- Does something feel wrong without a clear reason? → Detection layer. Start with discrepancies.
- Is the problem unclear, tangled, or wrongly framed? → Framing layer. Start with reframe or decompose.
- Is the problem clear but unexplored? → Generation layer. Start with speculate or infer.
- Is there already a position that needs testing? → Testing layer. Start with reconsider or challenge.
- Have multiple angles already been explored? → Synthesis layer. Start with review.
- Is a commitment imminent? → Synthesis layer. Start with pre-mortem.

If none of these are clear, start with discrepancies. The detection layer is the correct default when orientation is uncertain.

### Mode 2: Monitor
*Used continuously as thinking progresses. This is the recursive mode.*

After each skill produces output, the conductor reads that output and asks three questions:

1. **Is the output complete?** Does it fully accomplish what the skill was activated to do, or is there more to do within this skill?

2. **What does the output signal about next steps?** Each skill's routing signals (documented in the terrain map above) indicate what typically follows. Read those signals in the actual output, not abstractly.

3. **Has the terrain position changed?** Sometimes a skill's output reveals that the thinking is in a different position than assumed — a testing-layer skill reveals the frame is wrong, or a generation-layer skill reveals the problem is more tangled than it appeared. When this happens, the conductor redirects upstream rather than continuing downstream.

The recursive property: the conductor can always send thinking back to an earlier layer. Downstream output that reveals upstream problems is not a failure — it is the system working correctly.

### Mode 3: Recognize Completion
*Used when the synthesis layer has produced output or when the thinking has reached a natural resting point.*

Completion is not the same as exhaustion. The thinking does not need to have used every skill. It needs to have used the right skills, in the right sequence, to produce understanding adequate to the problem.

Signals that thinking is complete:
- Review has produced emergent understanding that no single perspective alone would have shown
- Pre-mortem has been run and its outputs are clear
- The question that motivated the thinking can now be answered with appropriate confidence and explicit epistemic status
- Further skill activation is producing variations rather than new insights

Signals that thinking is not complete despite feeling finished:
- The conclusion is too comfortable — it arrived without resistance
- The conclusion aligns perfectly with what was hoped for
- No skill has produced a result that required updating a prior assumption
- The synthesis layer has not been reached

When completion is genuinely reached, the conductor raises the baton one final time — directing Skill Master to conduct the output audit: Grammar (were things named correctly?), Logic (does the reasoning follow?), Rhetoric (is the communication shaped in service of truth rather than acceptance?).

---

## The Conductor's Relationship With Time

The conductor is most visibly active early — when the terrain is unmapped, when routing decisions are not yet intuitive, when the system is learning its own topology.

As patterns accumulate through use and feedback, routing decisions become faster and less effortful. The conductor does not become less important. It becomes less visible. The decisions it is making are the same decisions — they are simply being made with more pattern recognition and less deliberate calculation.

This is the expected trajectory. A conductor who has led the same orchestra through many performances does not consult the score as often. The music is internalized. The decisions are still being made — they are just being made fluidly.

The conductor never stops watching. It is always the one holding the whole.

---

## When the Conductor Itself Is Uncertain

The conductor can be uncertain about where thinking is in the terrain, or what the right next move is. This is not a failure state — it is a signal.

When the conductor is uncertain about position — where in the terrain the thinking currently is:
- Consult topology. Locate the current state of thinking on the three axes (time, abstraction, certainty). Read what cluster it occupies and what the natural next moves from that cluster are. Topology returns a position and a set of proximally natural skills — the conductor uses that to route.

When the conductor is uncertain about the problem itself — the terrain is legible but the problem is not:
- Default to the detection layer. Run discrepancies on the current state of the thinking, not on the original problem.
- If discrepancies produces nothing useful, run decompose on the thinking process itself — what components of the problem have been addressed and what have not?
- If the conductor remains uncertain after both, the problem may need reframing before the terrain becomes legible.

The distinction matters: topology resolves uncertainty about navigation. Discrepancies and decompose resolve uncertainty about the problem. Reaching for the wrong one wastes the thinking.

Uncertainty in the conductor is almost always one of these two types. The terrain is not wrong — either the position within it is not yet clear (consult topology) or the problem has not yet been correctly located within the terrain (consult discrepancies).

---

## Coupling: When to Activate Skills Together

Some problems benefit from skills running in tandem, in intentional layers, or with specific skills excluded for a phase. The conductor makes these decisions by consulting topology.

**When to consider coupling:**
- A problem has both a framing component and a generation component that are closely related — tandem activation of reframe and speculate may be more efficient than strict sequence
- The thinking has been at one abstraction level for too long without moving — layered activation processes the same material at multiple abstraction levels sequentially
- A particular lens is distorting the analysis — intentional exclusion names the distortion and suspends it for a defined phase before reintroducing it

**How to decide:**
Consult topology. Locate the skills being considered on the three axes. Skills that are close in all three dimensions are natural tandems — the transition cost between them is low and holding both simultaneously is tractable. Skills that are far apart in one or more dimensions are better run sequentially, with review as the integration point.

The integration point for any coupling pattern is almost always review. Review is designed to hold simultaneously-produced outputs and synthesize what none of them would produce alone.

**The conductor tracks:**
- Which skills have been activated and what they produced
- Any intentional exclusions and when they are scheduled to be reintroduced
- Whether coupling is producing genuine integration or just parallel noise

Parallel noise — two skills running simultaneously without genuine interaction — looks like coupling but produces the same output as sequential activation. If coupling is not producing something neither skill would produce alone, it is not working. Dissolve the tandem and run sequentially.

---

## Updating the Conductor

The conductor is the system's self-knowledge. When a new skill is added to the system, the conductor must be updated to include that skill's position in the terrain, its inputs and outputs, and its routing signals.

A skill that exists outside the conductor's map is a skill the system cannot route to reliably. The conductor's map must be complete to function correctly.

When updating: add the new skill to the appropriate layer, document its inputs, outputs, and routing signals in the same format as existing skills, and review whether its addition changes any routing signals in adjacent skills.

---

## What the Conductor Is Not

The conductor is not a checklist. It does not require every skill to be used on every problem. Most problems need only a few skills. The conductor routes to what the problem actually needs, not to what the system contains.

The conductor is not a replacement for judgment. It provides the map and reads the terrain. Judgment about what the problem actually requires — which signals are real, which output is genuinely complete — still requires honest engagement with the thinking rather than mechanical execution of the routing.

The conductor is not infallible. It can misread the terrain. The correction is the same as for any other skill: when output feels like performance rather than genuine routing, return to the detection layer and run discrepancies on the conductor's own decisions.
