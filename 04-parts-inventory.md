# 04 · The Cut

**Step 4 of 7 · Phase: Sprint, weeks 1 to 2 · Output: the delete list, the parts-deleted count by type, the stripped workflow and its stripped offer.**

This is steps one to three of the five-step rule, run on every part the map inventoried: requirements with a named owner, delete, simplify. No acceleration yet. No automation yet. No code, no AI.

The unit of the Cut is the part, whatever its type. A company is made of parts, and anything that has a cost is one. A clause nobody owns and a feature nobody owns fail the same test.

The team that runs the workflow today does not sit in this room. The immune system does not get a seat at its own diagnosis; the team joins at step 5. Their knowledge is captured then, once the parts they would defend are gone.

## The seven categories

Every node on the map from step 1 goes into one of these. The examples are the kinds of parts the method names; your inventory will have its own.

| Category | Examples of parts |
|---|---|
| Process | Workflow steps, rules, approvals, meetings |
| Information | Form fields, reports |
| Organization | Roles |
| Systems | Systems, integrations |
| Offer | Features, SKUs, offers, price tiers |
| Contract | Contract clauses, policies |
| Measurement | KPIs |

The map tells you where to look first: parts sitting at commodity but built custom, parts nobody on the map consumes, parts clustered where the antibodies are.

## The owner test

Two questions, asked of every part, identically regardless of type:

1. **Who asked for this, by name?** A person. "Compliance", "the policy", "the client contract", "the product team" are not owners. A department does not exist for the purposes of this test.
2. **What breaks if it is gone tomorrow?** Something specific, that day, that someone would notice.

When the answer to the first question is a function and the answer to the second is vague, two more questions unlock it:

- **Can we live with the risk?**
- **Imagine it is gone. Do we survive?**

An ownerless part is an antibody. It goes on the delete list. The smarter the expert defending it, the more dangerous the part: expertise is where requirements turn into dogma. This is never about guilt. The owner usually just recites the reason everyone knows, and the reason usually predates everyone in the room.

## The inventory

One row per part. Fill it from the map. Deletion is the default; a part earns its row by having a name in the owner column and a concrete answer in the next one.

| Part | Category | Owner by name | Breaks tomorrow? | Decision (delete / keep / simplify) |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

**Parts deleted, by category**

| Process | Information | Organization | Systems | Offer | Contract | Measurement | Total |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

## The stop signal

You have deleted enough when people start asking you to add things back. About 10% of what you deleted should have to return. The 10% is the signal expressed as a number; the signal is the rule.

If nothing comes back, you were timid. Go back to the inventory and run the owner test again on everything you kept.

## The blank-sheet rebuild

Simplifying what is left is not the third step. Simplifying the leftover fossilizes its shape. The third step is: reconstruct the workflow from zero, with only the requirements that survived the owner test, as if the old one had never existed. Then compare it with the old one and note what came back on its own.

```
Surviving requirements (each with its owner's name):
1. [requirement] — [name]
2. [requirement] — [name]
3. ...

The rebuilt workflow, from zero:
1. [step]
2. [step]
3. ...

The rebuilt offer (what the workflow now sells, minus the deleted
features, tiers, and clauses):
[description]
```

## Cycle time is the master metric

Steps one to three are verified by cycle time, one to two orders of magnitude, before any automation. If you hit the time target you tend to hit every other target. Measure the rebuilt workflow on paper, walking it end to end, before you build anything.

The article behind this page uses one illustration: a soap cooperative's four-day cycle was mostly waiting. Deleting the waiting, not automating the making, was where the time went. See [Delete before you automate](https://samuelpouyt.com/articles/delete-before-you-automate).

```
Cycle time before: [value, measured]
Cycle time after the Cut, on paper: [value]
Ratio: [before / after]
```

## The red-lines exception

No owner, no part, with one exception. A rule that has no person behind it may still stand if it is one of the firm's red lines: the hard rules written in the constitution, each citing the failure that earned it. The red lines are the only legitimate owner of an ownerless rule. The Cut runs against the red lines, never around them. If a part claims to be a red line and is not written there with its scar, it is not a red line, and it goes on the delete list.

Constitution skeleton: [templates/constitution.md](templates/constitution.md). Worksheet version of this page: [samuelpouyt.com/r/parts-inventory](https://samuelpouyt.com/r/parts-inventory).

## Before you move on

- Every part on the map has a row, a category, and a decision.
- Every kept part has a person's name and a concrete "breaks tomorrow" answer, or is a written red line.
- People have asked for things back. About 10% came back.
- The workflow and its offer were rebuilt from zero, not trimmed.
- The paper cycle time is one to two orders of magnitude better than the measured one.
- Nothing has been automated.

Commit the inventory. Step 5 captures what survived.

Part of The Edge Method · samuelpouyt.com/method
