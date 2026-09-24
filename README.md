# Discrete Quest

**Master Discrete Math, One Quest at a Time.**

Discrete Quest is an evolving interactive learning project for Discrete Mathematics.
It organizes concepts into visual knowledge maps so learners can understand prerequisites,
explore examples, practice, check mastery, and decide what to learn next.

## Current stage

Five standalone HTML learning maps are available. Each bundles content, CSS, and
JavaScript, with no build step, framework, or backend required. These are working
prototypes, not a completed or independently reviewed curriculum.

| Module | Entry point | Nodes | Questions |
| --- | --- | --- | --- |
| Logic | [Map](modules/logic/index.html) · [Notes](modules/logic/README.md) | 20 | 96 |
| Set Theory | [Map](modules/sets/index.html) · [Notes](modules/sets/README.md) | 23 | 105 |
| Relations | [Map](modules/relations/index.html) · [Notes](modules/relations/README.md) | 30 | 129 |
| Functions | [Map](modules/functions/index.html) · [Notes](modules/functions/README.md) | 30 | 120 |
| Permutations | [Map](modules/permutations/index.html) · [Notes](modules/permutations/README.md) | 25 | 100 |

Existing features include dependency graphs, visual explanations, worked examples,
interactive practice, common mistakes, mastery checks, mixed review, cheat sheets,
and recommended next concepts. Each module saves progress locally in the browser.
Accounts, cross-device sync, a shared cross-topic graph, and adaptive Daily Quests are planned.

## Run locally

From the repository root:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Start at the [topic guide](http://localhost:8000/) for instructions and links between maps.

Or open [Logic](http://localhost:8000/modules/logic/),
[Set Theory](http://localhost:8000/modules/sets/),
[Relations](http://localhost:8000/modules/relations/),
[Functions](http://localhost:8000/modules/functions/), or
[Permutations](http://localhost:8000/modules/permutations/).

Alternatively, open the root `index.html` for the topic guide, or any module directly. A local server gives browser
storage a consistent origin. Keep the same hostname and port to access saved progress.
Moving from a downloaded file to localhost does not migrate progress. Browser settings
may block storage; clearing site data deletes it. GitHub file links show source rather
than a running map. No hosted deployment is configured in this repository.

## Repository layout

```text
index.html     # topic guide and learning instructions
modules/
  logic/       # index.html, README.md, references.md
  sets/        # index.html, README.md, references.md
  relations/   # index.html, README.md, references.md
  functions/   # index.html, README.md, references.md, coverage.md
  permutations/ # index.html, README.md, references.md, coverage.md
docs/
  product-vision.md
  learning-model.md
  curriculum-roadmap.md
  references.md
CONTRIBUTING.md
LICENSE
```

Only existing modules receive directories. Planned topics live in the roadmap until
usable content exists. Keep modules standalone while developing the curriculum;
extract shared data and components after stable patterns emerge.

## Nine-world roadmap

| World | Status |
| --- | --- |
| Logic | Prototype available |
| Sets | Prototype available |
| Relations | Prototype available |
| Functions | Reviewed prototype |
| Permutations | Reviewed prototype |
| Proofs | Planned |
| Counting | Planned |
| Graphs | Planned |
| Recurrences | Planned |

This is a proposed sequence, not a validated global prerequisite graph.
See the [curriculum and development roadmap](docs/curriculum-roadmap.md).

## Learning philosophy

Build the knowledge before the platform. Each node aims to connect intuition,
visual exploration, a worked example, common mistakes, and a mastery check.
The maps supplement a course; a quiz score is a learning signal, not proof of lasting
understanding. See the [learning model](docs/learning-model.md).

## Where this is going

The planned unified experience includes a cross-topic knowledge graph, 15–30 minute
Daily Quests, learner accounts, synchronized progress, a mistake collection, spaced
review, weak-topic detection, adaptive practice, and progress visualization.
These features are not implemented. See the [product vision](docs/product-vision.md).

## Knowledge references

[Discrete Mathematics Resources](https://sites.google.com/view/discretemathematicsresources/home)
is a proposed curriculum reference from the planning discussion. This import does not
establish that the modules have been cross-checked against it. The Functions and Permutations modules were reviewed against their supplied PDFs; see the
[Functions](modules/functions/references.md) and [Permutations](modules/permutations/references.md)
source notes. Original source PDFs for Logic, Sets, and Relations still need verification. See the [reference register](docs/references.md).

## Contributing and license

See [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow and manual acceptance checks.
The repository retains its existing [GNU AGPL v3 license](LICENSE).
Third-party materials retain their own terms; a citation does not grant reuse rights.

## Disclaim

All source knowledge are coming from https://sites.google.com/view/discretemathematicsresources/home?pli=1&authuser=0
