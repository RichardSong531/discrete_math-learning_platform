# Sequences & Recurrences coverage and review

Reviewed 2026-11-10 against the supplied *Chapter 4: Sequences*, pages 1-33,
credited by the source collection to Jose Franco and Pedro Morales-Almazan.
This is a source-alignment review, not verification against an instructor's
current syllabus or a guarantee of examination coverage.

## Included

All 38 nodes, 152 question keys and explanations, and 48 bilingual glossary
entries were reviewed. The 56 distinct prerequisite edges refer to valid nodes,
form an acyclic graph, and allow all 38 nodes to become ready.

| Learning area | Nodes | Material |
| --- | --- | --- |
| Summation | 1-5 | Sigma notation, triangular sums, linearity, reindexing, index sets and empty sums |
| Sequence basics | 6-9 | Functions on discrete indices, arithmetic/geometric sequences, Fibonacci seeds |
| Induction | 10-15 | Ordinary induction, well-ordering, sum and sequence proofs, counterexamples, strong induction |
| Recurrence definitions | 16-19 | Representations, order, initial values, factorials, recurrence iteration |
| Linear recurrence solving | 20-28 | Homogeneity, first-order equations, monthly examples, characteristic roots, Fibonacci closed form |
| Generating functions | 29-32 | Coefficients, shifted sums, partial fractions, first- and second-order examples |
| Optional matrix methods | 33-37 | State vectors, matrix powers, diagonalization, companion matrices, second- and third-order examples |
| Synthesis | 38 | Connect lists, formulas, recurrences, generating functions, and proof |

## Depth and remaining scope

- The main learning path covers summation, sequence representations, induction,
  and elementary recurrence solving. Generating functions add depth, while
  Section 4.5 explicitly marks matrix methods as optional. Inclusion does not
  establish a requirement in the current UCSC CSE 16 syllabus.
- The map represents the source's major sections but does not reproduce every
  exercise or subpart. Source exercise errors and indexing conventions are
  recorded in [references](references.md).
- Strong induction is present here with a prime-factorization existence outline.
  The separate Proofs map still needs its strong-induction coverage consolidated
  during the whole-curriculum repair. This import does not close that task.
- Four-question checks assess recognition and short calculations. Proof-outline
  ordering does not grade independently written arguments, factorization
  uniqueness, or the full equivalence proof for induction and well-ordering.
- Numeric panels have bounded inputs and display finite prefixes. Agreement
  between iteration and a formula is evidence for those inputs, not a proof for
  all indices. Decimal output may be rounded.
- The recurrence builders use the displayed presets and parameterized first- and
  second-order forms; they are not symbolic solvers for arbitrary recurrence
  expressions, nonlinear equations, or divide-and-conquer recurrences.
- The characteristic-root panel distinguishes distinct, repeated, zero, and
  complex-root cases. It uses real recurrence iteration for complex roots; it
  does not provide a general complex-number algebra interface.
- Generating-function panels show selected source examples and coefficients.
  They do not accept arbitrary rational functions or automatically perform
  symbolic partial fractions. Formal identities do not by themselves justify
  evaluating an infinite series at an arbitrary real number.
- The matrix panel illustrates bounded 2-by-2 iteration. The third-order lesson
  explains the source's 3-by-3 construction; the shared panel is not a general
  third-order solver or diagonalization engine.
- The fixed growth and contribution examples are recurrence exercises with a
  stated monthly clock and contribution timing.

## Content review

The chapter was read in full, with visual inspection of 21 pages containing key
formulas and examples. The supplied map already corrects Fibonacci indexing,
Euler's first composite output, the initial-value count, and the square-sequence
exercise. All intended question keys match their mathematical claims after
clarifying zero-term ratios and the nonzero repeated-root condition.

The repository review also clarifies recurrence order, monthly units, the base
case required by the well-ordering example, and the scope of the shared matrix
panel. Source errors in the repeated-root coefficient and selected exercises
are documented rather than copied into scored questions.

## Runtime validation

Validated in Chrome on macOS on 2026-11-10:

- 189 acceptance checks covered all 38 four-question quizzes, incomplete and
  repeated submissions, current/best scores, retries preserving lab settings,
  mixed practice, glossary search, recommendations, reload, scoped reset, and
  malformed or unavailable browser storage. All 38 lessons fit a 390-pixel
  viewport; desktop and mobile lesson views were also inspected visually.
- 446 calculation and interaction checks covered invalid numeric inputs, empty
  sums, undefined powers, arithmetic/geometric/Fibonacci terms, recurrence
  iteration, closed forms, characteristic-root cases, generating-function
  coefficients, and matrix updates. Expected values were checked against
  independently calculated examples and formulas. Keyboard graph activation,
  proof-outline ordering and reset, synthesis controls, and lesson printing
  were checked as well.
- 223 navigation checks covered all thirteen topic links, chapter ordering,
  current-topic markers, previous/next/home navigation, keyboard entry, and the
  guide totals at widths of 390, 768, and 1,440 pixels. No uncaught browser errors
  occurred in these runs.
- Static checks verified question references, the 56-edge prerequisite DAG,
  curriculum totals, local links, unchanged original downloads, and navigation-only
  changes to the twelve existing lesson files.

These checks do not establish cross-browser compatibility, full accessibility
conformance, correctness for every floating-point input, or retained mastery.
The mathematical and interaction limitations above remain part of the repair
handoff for the thirteen-map curriculum.
