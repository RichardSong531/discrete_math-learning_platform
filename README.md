# Discrete Quest

**Master Discrete Math, One Quest at a Time.**

Discrete Quest is an evolving interactive learning project for Discrete Mathematics.
It organizes concepts into visual knowledge maps so learners can understand prerequisites,
explore examples, practice, check mastery, and decide what to learn next.

## Current stage

Three standalone HTML learning maps are available. Each bundles content, CSS, and
JavaScript, with no build step, framework, or backend required. These are working
prototypes, not a completed or independently reviewed curriculum.

| Module | Entry point | Nodes | Questions |
| --- | --- | --- | --- |
| Logic | [Map](modules/logic/index.html) · [Notes](modules/logic/README.md) | 20 | 96 |
| Set Theory | [Map](modules/sets/index.html) · [Notes](modules/sets/README.md) | 23 | 105 |
| Relations | [Map](modules/relations/index.html) · [Notes](modules/relations/README.md) | 30 | 129 |

Existing features include dependency graphs, visual explanations, worked examples,
interactive practice, common mistakes, mastery checks, mixed review, cheat sheets,
and recommended next concepts. Each module saves progress locally in the browser.
Accounts, cross-device sync, a shared cross-topic graph, and adaptive Daily Quests are planned.

## Run locally

From the repository root:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open [Logic](http://localhost:8000/modules/logic/),
[Set Theory](http://localhost:8000/modules/sets/), or
[Relations](http://localhost:8000/modules/relations/).

Alternatively, open a module's `index.html` directly. A local server gives browser
storage a consistent origin. Keep the same hostname and port to access saved progress.
Moving from a downloaded file to localhost does not migrate progress. Browser settings
may block storage; clearing site data deletes it. GitHub file links show source rather
than a running map. No hosted deployment is configured in this repository.

## Repository layout

```text
modules/
  logic/       # index.html, README.md, references.md
  sets/        # index.html, README.md, references.md
  relations/   # index.html, README.md, references.md
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

## Eight-world roadmap

| World | Status |
| --- | --- |
| Logic | Prototype available |
| Sets | Prototype available |
| Functions | Planned |
| Relations | Prototype available |
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
establish that the modules have been cross-checked against it. The HTML pages also refer
to PDFs that were not provided. Mathematical review and source verification remain
outstanding; see the [reference register](docs/references.md).

## Contributing and license

See [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow and manual acceptance checks.
The repository retains its existing [GNU AGPL v3 license](LICENSE).
Third-party materials retain their own terms; a citation does not grant reuse rights.
