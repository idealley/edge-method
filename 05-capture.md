# 05 · Capture what survives

**Step 5 of 7 · Phase: Sprint, weeks 1 to 3 · Output: playbooks, the red lines, agent-readiness scores, and the list of data the workflow touches.**

Only now. Capturing before the Cut means writing playbooks for steps that should not exist and scoring the automation potential of parts that are about to be deleted. Everything on this page is done on the stripped workflow from step 4, never on the original.

This is also where the team joins. The people who run the workflow today were kept out of step 4 so that the immune system did not diagnose itself. Now their judgment is the asset, and this page is how it is captured.

## What gets captured

1. **Senior judgment, as playbooks.** The decisions that survived the Cut because a named person could say what breaks without them. Capture video-first: record the senior person walking through a real case, then write the playbook from the recording, in their words.
2. **The firm's real trade-offs and red lines.** The hard rules that stood in step 4 without a person behind them, and the trade-offs the senior people make that nobody has written down. These go into the constitution, each with the failure that earned it. Skeleton: [templates/constitution.md](templates/constitution.md).
3. **Per-task agent-readiness scoring.** Break the stripped workflow into tasks. For each: how rule-clear it is, how measurable its output is, how reversible an error is, what it depends on. The score decides what the edge builds first in step 6 and what stays human. Score the stripped workflow, not the one you mapped in step 1; most of the low-scoring tasks were deleted.
4. **The data the workflow actually touches.** Which records it reads, which it writes, where they live, who owns them. The edge in step 6 works with this list and nothing outside it.

## Playbook template

One per judgment call that survived. Keep each one short enough to be read before every run.

```
PLAYBOOK — [name]

Trigger:
  [The situation that calls for this judgment. Precise enough that
  an agent could detect it and hand over.]

Steps:
  1. [step]
  2. [step]
  3. [step]

The judgment calls:
  [The two or three decisions in these steps that are not rules.
  What the senior person weighs, in their words, from the recording.]

Who owns it:
  [A name. The person whose judgment this is, and who updates the
  playbook when an override shows it is wrong.]

The scar it cites:
  [The real failure that made this playbook necessary. Date, what
  happened, what it cost. A playbook with no scar is speculation and
  goes back to step 4 for the owner test.]

Source recording: [link or file]
Last reviewed: [date] by [name]
```

## Readiness scoring sheet

| Task (from the stripped workflow) | Rule-clear? | Measurable output? | Reversible error? | Depends on | Stays human / gate / agent |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |
| | | | | | |

## Before you move on

- Every surviving judgment call has a playbook with a named owner and a scar.
- The red lines are in one file, each citing its failure.
- Every task in the stripped workflow has a readiness score and a decision: human, gate, or agent.
- The data list is complete and nothing on it was invented for the edge.

Commit everything. Step 6 builds.

Part of The Edge Method · samuelpouyt.com/method
