# About This Project

## What This Project Is

This repository is a practical framework for designing a 4-week enterprise AI fast-start onboarding program. It is built to show an end-to-end workflow that starts with discovery, translates findings into program decisions, and outputs a structured plan that can be evaluated and improved.

The design goal is simple: make AI adoption planning concrete, measurable, and repeatable for real teams with real constraints.

## Why This Project Exists

Many AI onboarding efforts fail because they are either too generic or too ambitious for the first 30 days. This project addresses that by:

- centering discovery before recommendations,
- mapping blockers to specific weekly interventions,
- forcing measurable checkpoints and ownership,
- using a lightweight rubric to evaluate quality before sharing.

## What Is Included

- Discovery assets:
  - `framework/discovery-question-framework.md`
  - `prompts/discovery-interview-prompt.md`
- Program design assets:
  - `framework/mapping-rules.md`
  - `framework/four-week-program-template.md`
- Example run:
  - `examples/mock-discovery-session.md`
  - `examples/mock-four-week-output.md`
- Evaluation assets:
  - `evals/output-quality-rubric.md`
  - `evals/mock-output-evaluation-v1.md`
  - `evals/mock-output-evaluation-v2.md`

## How to Use This

Use this workflow as a repeatable exercise to produce a mock or real 4-week fast-start program from discovery inputs.

### Step 1: Capture discovery input

Run the interview using `prompts/discovery-interview-prompt.md` and guide questions in `framework/discovery-question-framework.md`.

Your output should include, at minimum:
- organization profile and team scope,
- current AI usage and top blockers (ranked),
- risk/governance constraints,
- candidate pilot workflow(s),
- success criteria for 30 days,
- baseline metric definitions and current values with owner,
- open questions.

Tip: if you only want a practice run, use `examples/mock-discovery-session.md` as your input.

### Step 2: Map findings to program choices

Use `framework/mapping-rules.md` to translate discovery signals into design decisions:
- low confidence -> more guided reps and scaffolding,
- high governance risk -> stronger boundaries and manager checkpoints,
- time constraints -> reduced scope and tighter relevance,
- quality concerns -> explicit verification and owner-assigned metrics.

At this step, choose one primary pilot workflow and preserve scope discipline.

### Step 3: Generate the 4-week program

Fill `framework/four-week-program-template.md` using your mapped decisions.

Every weekly checkpoint should include:
- metric,
- target by end of week,
- owner,
- evidence artifact.

Your measurement plan should include baseline values, week-4 targets, cadence, and data sources.

### Step 4: Validate output quality

Score the generated plan with `evals/output-quality-rubric.md` across six categories:
- relevance,
- feasibility,
- actionability,
- confidence building,
- workflow realism,
- measurement clarity.

Record:
- total score out of 30,
- top 2 strengths,
- top 2 gaps,
- one revision to apply before next run.

### Step 5: Revise and re-score

Apply one focused revision set, regenerate or edit the program output, and run the rubric again. Keep both evaluations to show quality improvement over time.

## Expected exercise output

At the end of one full run, you should have:
- a structured discovery summary,
- a customized 4-week fast-start program,
- a rubric-scored evaluation,
- at least one revision cycle with a measurable delta.

This is enough for a mock demonstration and strong enough to use as a starting point for a real pilot.

## Suggested operating cadence

- Day 1-2: discovery and baseline capture
- Day 3: mapping and first program draft
- Day 4: rubric evaluation and revision
- Day 5: final output and stakeholder-ready summary

## Boundaries

This project does not replace legal/compliance policy creation or full transformation planning. It is a focused onboarding accelerator for an initial team pilot.

## Final Reflection

### What worked best

- The discovery-first sequence prevented generic recommendations and kept outputs tied to real constraints.
- Mapping rules made it easier to convert stakeholder input into concrete week-by-week actions.
- The checkpoint schema (metric, target, owner, evidence) improved execution clarity and accountability.
- The rubric and revision loop showed measurable quality improvement between versions.

### Limitations and trade-offs

- This framework prioritizes speed and clarity over deep organizational change design.
- A single pilot workflow improves focus, but may underrepresent cross-functional dependencies.
- Quality still depends on manager reinforcement consistency and baseline data reliability.
- The mock scenario validates method quality, but not real-world adoption behavior over longer horizons.

### What to improve in a real deployment

- Add a fallback protocol when weekly targets are missed (owner action, recovery window, escalation trigger).
- Add role-specific variants for managers, ICs, and governance stakeholders.
- Extend measurement beyond week 4 with a 30/60/90-day adoption follow-through layer.
- Add a lightweight implementation kit (review checklist, tracker template, retrospective template) for easier operational rollout.
