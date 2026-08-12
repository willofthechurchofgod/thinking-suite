# Thinking Suite — for-agents

This directory contains the full reasoning skill system, written for AI agents. Technical notation is preserved: lens, depth, light intensity, routing signals, conductor integration.

---

## How to use this system

**Start with `skill-master.md`.** It is the master lens — five questions applied before any substantive response. Every other skill builds on the discipline it establishes.

**Then read `conductor.md`.** It routes between skills, watches for drift, and knows when to stop.

**Then read `topology.md`.** It maps how all skills relate to each other in three dimensions (time, abstraction, certainty). Use it when you are not sure which skill fits.

**Then read `kaleidoscope-guide.md`.** It is the operating manual — how the whole system works in practice.

---

## The skills

| File | What it does |
|------|-------------|
| `skill-master.md` | Master lens — five questions before any substantive response |
| `conductor.md` | Director — routes between skills, watches the whole |
| `topology.md` | Three-dimensional map of how all skills relate |
| `kaleidoscope-guide.md` | Operating manual — how the system works in practice |
| `discrepancies.md` | Detect where reality doesn't match the model, before you know why |
| `reframe.md` | Step outside the current problem frame when the frame is the obstacle |
| `decompose.md` | Break a tangled problem into named, workable parts |
| `speculate.md` | Generate possibilities without committing to any |
| `infer.md` | Reason carefully from incomplete information |
| `steelman.md` | Construct the strongest version of a position you disagree with |
| `reconsider.md` | Re-examine a conclusion you've already reached |
| `challenge.md` | Test a position against the strongest possible objections |
| `constrain.md` | Find exactly where a principle applies and where it breaks |
| `review-synthesis.md` | Synthesize multiple perspectives into emergent understanding |
| `pre-mortem.md` | Surface concrete failure modes before committing to a decision |

---

## Architecture notes

The system has three layers:

**Foundation:** `skill-master` → applied first, always. Five questions that orient the entire reasoning process.

**Direction:** `conductor` → routes to the right skill, monitors for performance drift, signals completion.

**Application:** the remaining 12 skills → specific cognitive operations, each with defined activation conditions, mechanics, and failure modes.

`topology` and `kaleidoscope-guide` are meta-skills — they describe the system's structure rather than performing specific operations.

---

## The kaleidoscope model

The system is organized around a central metaphor: a kaleidoscope.

- **The lens** — your operative perspective (epistemological category + constitutional principle)
- **The fragments** — everything you know about the subject
- **The dial** — controls which lens is active and the light intensity (depth and detail)
- **The bubble** — the bounded thought-space where reasoning happens

Rotation is deliberate. The same fragments, viewed through different lenses, produce different patterns. The discipline is noticing when you are locked into one configuration and choosing to shift.

Each skill is a specific lens configuration. The conductor manages rotation between them.

---

## License

MIT. Use freely, adapt freely, attribute if it's useful to you.
