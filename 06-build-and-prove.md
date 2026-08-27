# 06 · Build at the edge and prove

**Step 6 of 7 · Phase: Sprint, weeks 3 to 10 · Output: a falling override rate, and before/after on cycle time, error rate, cost, and parts deleted.**

Only now does anything get built. The order inside this step is the last two of the five: accelerate cycle time first, automate last. Automation freezes a process, and it quietly licenses useless steps because a machine now does them. That is why it comes after everything else, and why this page is a checklist rather than an architecture.

## The container

Above about 50 people, the company's immune system will restore what the Cut removed. The edge is the only container where the new way survives long enough to be proven.

- [ ] **50 people or fewer:** build in place. The company is the edge. No twin is needed.
- [ ] **More than 50 people:** build an edge twin. A small unit that runs the stripped workflow alongside the company, not inside it.
  - [ ] 3 to 5 of the firm's own people, plus agents. Volunteers, not assignees: the method fails on people who had another life before.
  - [ ] Funded by the CEO, from the line named in the mandate. Never by the division it will replace.
  - [ ] Insulated: its own reporting line to the CEO, its own tooling decisions, its own metrics. The division's approvals do not apply to it.
  - [ ] Working only with the data listed in step 5.

## Before the run

- [ ] Benchmarks are written down and committed **before** the shadow run starts. The goalposts do not move.
  - [ ] Cycle time, measured on the current workflow the same way it will be measured on the new one.
  - [ ] Error rate, with "error" defined in writing.
  - [ ] Cost per run.
  - [ ] Parts deleted, by category, carried over from step 4.
- [ ] The comparison baseline is the **cut** workflow from step 4, not the original. Proving the new way beats a workflow full of parts nobody owns proves nothing.
- [ ] Every agent has a written spec: what it does, what it reads and writes (from the data list), which playbook it follows, and where it hands over to a human.
- [ ] The human gates from step 5 are in place and closed by named people.
- [ ] The red lines from the constitution are enforced as gates, not left as guidance.
- [ ] The override log is open. The [issue template](.github/ISSUE_TEMPLATE/override.yml) in this repository is one way to run it.

## The shadow run

- [ ] The new way runs on real cases alongside the old way. The old way remains the system of record.
- [ ] Every divergence between the two is recorded. Every human correction of the agent is logged as an override.
- [ ] Each override is treated by the ladder in [07-override-ladder.md](07-override-ladder.md): a deletion candidate first, training data second.
- [ ] The override rate is tracked weekly. A falling override rate is the test of a real twin.
- [ ] If the override rate does not fall, say so, in writing, before any decision to scale. This is a rule, not a preference.

## Handover in waves

- [ ] The workflow is handed over in waves, not at once. Each wave moves a bounded set of cases or a bounded set of tasks to the new way as system of record.
- [ ] Each wave has its own before/after on the four benchmarks.
- [ ] The next wave starts only when the previous one has held its numbers.
- [ ] The old way stays live until the new way has provably won on all four benchmarks. "Provably" means the numbers, not a demo.

## The result

```
Workflow: [name]
Shadow run: [start date] to [end date]

                     Before (cut workflow)   After   Ratio
Cycle time           [ ]                     [ ]     [ ]
Error rate           [ ]                     [ ]     [ ]
Cost per run         [ ]                     [ ]     [ ]
Parts deleted        [ ] (from step 4)       [ ] (further, from overrides)

Override rate, week 1: [ ]   week n: [ ]
Overrides resolved at tier 1 / 2 / 3 / 4: [ ] / [ ] / [ ] / [ ]

Decision: [scale / another wave / stop]
Decided by: [name]     Date: [date]
```

Commit the result. Step 7 lets the edge become the center.

Part of The Edge Method · samuelpouyt.com/method
