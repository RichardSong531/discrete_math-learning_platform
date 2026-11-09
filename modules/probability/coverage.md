# Discrete Probability coverage and review

Reviewed 2026-11-08 against Joseph Klobusicky's supplied *Discrete Probability*,
pages 1-41. This is a source-alignment review, not verification against an
instructor's current syllabus or a guarantee of examination coverage.

## Included

All 44 nodes, 176 question keys and explanations, and 56 bilingual glossary
entries were reviewed. The 75 distinct prerequisite edges refer to valid nodes,
form an acyclic graph, and allow all 44 nodes to become ready. The map uses 37
distinct laboratory/panel types; several related lessons share a panel.

| Learning area | Nodes | Material |
| --- | --- | --- |
| Fundamentals | 1-7 | Sample spaces, set events, axioms, complements, unions, weights, classical probability |
| Counting | 8-16 | Multiplication, four sampling models, stars and bars, applications, birthdays, symmetry |
| Conditioning | 17-21 | Restricted spaces, chain rule, independence, partitions and total probability |
| Random-walk applications | 22-24 | Finite gambler's ruin, hitting/recurrence, fixed Vacuumba graph |
| Bayes | 25-28 | Posterior, diagnostic rates, two-test conditional independence, multiple hypotheses |
| Random variables | 29-36 | PMFs, uniform, Bernoulli, binomial, geometric, Poisson, transformations |
| Moments | 37-43 | Mean, large numbers, variance, standard deviation, transformed moments, family summaries, total expectation |
| Synthesis | 44 | Identify a model, its assumptions, and a suitable calculation |

## Depth and remaining scope

- The introductory path centers on finite/countable events, counting, conditional
  probability, independence, random variables, and expectation. Markov-style
  hitting examples, Poisson limits, and higher moments add supplemental depth.
  Their inclusion does not establish that they are required by the current UCSC
  CSE 16 syllabus or by a particular instructor's assessments.
- The map represents the main source sections but does not reproduce all 68
  numbered exercises and subparts. It does not assess complete proofs of the
  probability axioms' consequences, the large-number theorem, Poisson convergence,
  infinite-mean constructions, or all the source's counting puzzles.
- Four-question mastery checks assess recognition and short calculations. They
  do not certify independent modeling, derivations, retention, or proof writing.
- Numerical inputs are bounded. Dice and coin labs use fixed finite spaces;
  editable PMFs use only the displayed support. The sampling formulas count
  outcomes and need a separate uniformity assumption before they yield probabilities.
- The geometric convention counts failures before success. Geometric and Poisson
  plots display a finite prefix and identify omitted tail mass; they do not
  display an entire infinite support. Binomial variance is a labeled extension.
- The transformation and moment panels use `X~Unif({1,...,n})` and `Y=|X-c|`.
  They do not accept arbitrary functions or infinite-support transformations.
- Gambler's ruin uses a bounded one-dimensional walk with fixed absorbing
  endpoints. Vacuumba uses one source graph and its exact neighbor-average
  equations; it is not a general Markov-chain or arbitrary-graph solver.
- Simulations use browser pseudorandom samples and finite runs. Observed
  frequencies may differ from exact probabilities, and sample means need not
  move monotonically toward their expectation.
- Conditional probabilities and Bayesian posteriors are undefined for impossible
  evidence. Conditional independence in repeated-test examples is a modeling
  assumption, not a property established from real observations.
- Source corrections, distribution conventions, and omitted problematic source
  exercises are recorded in [references](references.md).

## Content review

The chapter was read in full, with visual inspection of 20 pages containing key
formulas, diagrams, and selected solutions. All intended question keys match
their mathematical claims after clarifying the assumptions. The review identified
an ambiguous chain-rule distractor: an event of probability one also satisfies
the independence condition. It was replaced with an insufficient condition.
The binomial synthesis prompt now specifies a common success probability, and
coin/birth examples state the independence and uniformity assumptions they need.

The review also clarifies positive-probability conditioning, finite-moment
requirements, geometric parameter bounds, and the distinction between counting
allocations and sampling them uniformly. The finite event display represents
an empty set as `∅`, rather than the singleton set `{∅}`.

## Runtime validation

Validated in Chrome on macOS on 2026-11-08:

- 213 acceptance checks covered all 44 four-question quizzes, partial and complete
  attempts, repeat-submit protection, fresh attempts, current/best scores, mixed
  review, glossary search, recommendation, reload, scoped reset, and malformed or
  unavailable browser storage.
- 417 runtime checks covered all lesson panels, blank/out-of-range/noninteger
  numeric inputs, invalid PMFs, impossible conditioning, distribution boundaries,
  keyboard focus, event toggles, printing, and all 44 lessons at widths of 390,
  768, and 1,440 pixels.
- 651 mathematical-lab checks compared finite event counts, exact combinatorics,
  conditional and Bayesian probabilities, distributions, moments, and transforms
  with independently calculated results. Random-walk results were compared with
  independently solved linear systems, including fair-game and endpoint cases.
  Simulation checks verified operation and bounds, not a fixed random output.
- 128 shared-navigation checks covered the twelve-map guide, chapter numbering,
  totals, current-topic links, keyboard entry, and previous/next/home navigation
  at desktop, tablet, and mobile widths. The guide and module were also inspected
  visually. The local server's optional missing favicon request was excluded from
  console-error assertions; no application errors were observed.
- Static checks verified the acyclic prerequisite graph, question references,
  displayed curriculum totals, and 256 local links across the changed files.
  Existing lesson changes were limited to shared navigation.

These checks do not establish cross-browser compatibility, a full accessibility
audit, or long-term learning outcomes. Storage remains browser-local, and quiz
scores remain separate from evidence of written reasoning or retained mastery.
