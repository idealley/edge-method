# The Edge Method

This repository contains no code. That is the point.

The method's rule is: no code and no AI before the method has run. Its implementation is a set of documents you fill in, in order. If you came here asking where the implementation is, you are looking at it.

**One sentence.** Reinvent a company at the edge, starting from one workflow: map it, cut it, rebuild it where the immune system cannot reach, prove it against the old way, then let the edge become the center.

## Four questions, four instruments

| Question | Instrument | What it does |
|---|---|---|
| Where? | The Wardley map | The real map of one workflow's value chain: what is commodity and should be bought, what is genesis and stays human, what is hand-built for no reason and is therefore the first thing to delete. |
| How? | The five-step rule (the Cut) | Inside one workflow, in this order: requirements with a named owner, delete, simplify, accelerate, automate last. Musk's five steps, applied to every part a company is made of. |
| Why, and toward what? | The exponential question and the edge | What marginal cost of supply toward zero means for this firm; the learning loop that compounds; the edge as the only container where this survives above about 50 people. |
| Why it will fail anyway | The immune system | The question the other three never ask. Which processes, incentives, and habits will restore every deleted part, and what to override first. |

The fourth row is what makes this a method rather than a reading list. Maps, the five steps, and exponential thinking all assume that once you see the right thing you can do it. A mature company cannot, and each reason it cannot has a name.

## The sequence

| # | Step | Output | Phase | Document |
|---|---|---|---|---|
| 0 | Recalibrate. The CEO builds something with AI, alone, and hits the wall. | Recalibrated executive judgment | Build (optional side door) | [samuelpouyt.com/build](https://samuelpouyt.com/build) |
| 1 | See the map | The map of one workflow, antibodies drawn on | Awake | [01-map.md](01-map.md) |
| 2 | Name the destination | Destination, learning-loop hypothesis, CEO mandate in writing | Awake | [02-destination.md](02-destination.md) |
| 3 | Pick the one thing | Wave-1 workflow and a go/no-go | Awake | [03-the-one-thing.md](03-the-one-thing.md) |
| 4 | Cut | Delete list, parts-deleted count by type, the stripped workflow and its stripped offer | Sprint | [04-parts-inventory.md](04-parts-inventory.md) |
| 5 | Capture what survives | Playbooks, red lines, agent-readiness scores | Sprint | [05-capture.md](05-capture.md) |
| 6 | Build at the edge and prove | Falling override rate; before/after on cycle time, error rate, cost, parts deleted | Sprint | [06-build-and-prove.md](06-build-and-prove.md) |
| 7 | Let the edge become the center | A permanent migration engine | Scale | [07-override-ladder.md](07-override-ladder.md) |

Steps 1 to 3 are the Awake. Steps 4 to 6 are the Sprint. Step 7 is Scale. Step 0 sits outside the ladder on purpose.

## The rules

One workflow at a time, never the company. No code and no AI before the method has run. Delete before you automate. Delete until people ask for things back, about 10%. Cycle time is the master metric; the bar is 10×, not 10%. No owner, no part. The immune system does not get a seat at its own diagnosis: the team joins at step 5, not before. The edge is funded by the CEO, never by the division it will replace. The old way stays live until the new way has provably won. Benchmarks are set before the run; the goalposts do not move. Every override is a deletion candidate first and training data second. If the override rate does not fall, say so before Scale.

## How to use this repository

1. Fork it.
2. Fill the documents in order, 01 to 07. Each one produces the input for the next. Do not start at 05 because that is where the interesting work seems to be.
3. Commit each document when it is filled. An uncommitted spec is just a prompt.
4. Once the build runs, log every human override as an issue with the [override template](.github/ISSUE_TEMPLATE/override.yml). The ladder in 07 tells you where each one gets resolved.
5. Keep your red lines in one file. [templates/constitution.md](templates/constitution.md) is the skeleton. Pull requests: see [CONTRIBUTING.md](CONTRIBUTING.md).

## Where it comes from

- The method page: [samuelpouyt.com/method](https://samuelpouyt.com/method)
- The article on step 4: [Delete before you automate](https://samuelpouyt.com/articles/delete-before-you-automate)
- The Parts Inventory, the worksheet behind 04: [samuelpouyt.com/r/parts-inventory](https://samuelpouyt.com/r/parts-inventory)
- The antibody diagnostic behind 01: [samuelpouyt.com/diagnostic](https://samuelpouyt.com/diagnostic)

The method was written by Samuel Pouyt ([@idealley](https://github.com/idealley), Lausanne), after years of running transformation work inside a Fortune 500 company and then outside it.

## Credits

- Simon Wardley, for maps and the evolution axis.
- Salim Ismail et al., *Exponential Organizations*, for the exponential question and the edge rules.
- The five-step rule of Elon Musk, as documented by Walter Isaacson and by Karim Bousta, whose practitioner detail sharpened the Cut.
- [@poteto](https://github.com/poteto), for the override ladder progression.

## License

Text and templates: [CC BY-SA 4.0](LICENSE). Share it, adapt it, credit it, keep it open.

Part of The Edge Method · samuelpouyt.com/method
