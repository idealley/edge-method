# 07 · The override ladder, and letting the edge become the center

**Steps 6 and 7 · Phase: Sprint into Scale · Output: a permanent migration engine.**

The Cut does not end when the build starts. It recurs at every human override. Each time a person corrects the agent, the correction is not first of all training data. It is a pointer to a part that should not exist.

**The rule: every override is a deletion candidate first and training data second.**

## The ladder

Resolve each override in this order, highest value first. Stop at the first tier that works.

| Tier | Resolution | What it looks like |
|---|---|---|
| 1 | **Structural.** Eliminate the cause so the mistake is impossible. | Change the workflow, the data structure, or the way the domain is modeled, so that the situation that produced the override cannot occur. This is the Cut applied at runtime: the deleted part is a step, a field, a rule, or a path. |
| 2 | **Gate or eval.** Turn it into a deterministic check. | The system catches it before a human does. A validation, a reconciliation, a test that fails. Machines check everything checkable. |
| 3 | **Playbook rule or skill.** Turn it into written instruction. | A rule in the playbook, a line in the constitution, a skill the agent reads. The next run starts smarter. |
| 4 | **Human review.** Leave it to a person. | The override stays an override. A person will make this correction again next time. |

Tier 4 is the failure mode, not the safety net. An override that lands at tier 4 has not been resolved; it has been scheduled to recur.

## The two metrics

1. **The override rate falls.** Overrides per hundred runs, week over week. A falling override rate is the test of a real twin. If it does not fall, say so before Scale.
2. **The resolution distribution climbs.** Where the overrides get resolved is the test of whether anyone is tending the system. Over time the share resolved at tiers 1 and 2 should grow and the share at tier 4 should shrink. That movement, not the raw count, is what Scale is measured on.

```
Week   Runs   Overrides   Rate    Resolved at tier 1 / 2 / 3 / 4
[ ]    [ ]    [ ]         [ ]     [ ] / [ ] / [ ] / [ ]
[ ]    [ ]    [ ]         [ ]     [ ] / [ ] / [ ] / [ ]
[ ]    [ ]    [ ]         [ ]     [ ] / [ ] / [ ] / [ ]
```

Log each override with the [issue template](.github/ISSUE_TEMPLATE/override.yml). The tier field is required on purpose.

## Delete the phone number

When call centers were removed, the phone lines were cut, so the teams could not be quietly rebuilt. That is tier 1 in its purest form: make the deletion structural, so the immune system has nothing to regrow. A deleted part that is still technically reachable comes back. If a step was deleted, remove the screen, the form, the mailbox, the meeting slot. If an approval was deleted, remove the approver's access to the queue. The test of a deletion is that nobody can perform the old step even if they want to.

## Letting the edge become the center

Step 7 starts when the new way has provably won on the benchmarks fixed in step 6.

- [ ] **Deprecate the old way.** Not "keep it as a fallback". The old way is a phone number; cut it.
- [ ] **Next workflow, easiest first.** Go back to [03-the-one-thing.md](03-the-one-thing.md) with the next candidate. The edge now has people who have done this once, which makes the second run cheaper than the first.
- [ ] **Re-map quarterly.** Components move right on the evolution axis. What was custom last quarter is product now, and the map from step 1 is stale. Re-draw it, antibodies included.
- [ ] **Review the constitution for drift.** Rules that no override has needed in months are candidates for deletion; rules that overrides keep hitting belong higher on the ladder.
- [ ] **Keep the two metrics running** on every workflow the edge has absorbed. The engine is permanent or it is a project.

Part of The Edge Method · samuelpouyt.com/method
