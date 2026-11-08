# Curriculum and development roadmap

## Current progress

Eleven of thirteen standalone maps are available, with 350 knowledge nodes and
1,438 practice questions. Eight maps, from Functions through Proof Methods &
Induction, have been reviewed against supplied PDFs. Logic, Sets, and Relations
still require source verification and content review.

The latest addition is [Proof Methods & Induction](../modules/proofs/README.md):
40 nodes, 160 questions, and a separate notebook for ungraded written drafts.
Its [coverage report](../modules/proofs/coverage.md) records the source and browser
checks, including the remaining strong-induction scope. Prototype availability
does not mean that every planned learning outcome has been completed.

## Topic worlds

| Proposed order | World | Status | Next milestone |
| --- | --- | --- | --- |
| 1 | Logic | Imported prototype | Review sources and correctness |
| 2 | Sets | Imported prototype | Review sources and correctness |
| 3 | Relations | Imported prototype | Review sources and correctness |
| 4 | Functions | Reviewed prototype | Expand written-proof practice |
| 5 | Permutations | Reviewed prototype | Expand computation and written-proof practice |
| 6 | Integers | Reviewed prototype | Expand written proofs and algorithm-tracing practice |
| 7 | Matrices | Reviewed prototype | Expand multi-step computation and written-proof practice |
| 8 | Counting | Reviewed prototype | Expand multi-step counting and written-proof practice |
| 9 | Graphs | Reviewed prototype | Expand graph construction, algorithm traces, and written proofs |
| 10 | Posets | Reviewed prototype | Expand order construction, lattice reasoning, and written proofs |
| 11 | Proof Methods & Induction | Reviewed prototype | Add strong induction and expand written-proof practice |
| 12 | Sequences & Recurrences | Remaining | Build and review a standalone map |
| 13 | Discrete Probability | Remaining | Build and review a standalone map |

Sets includes a Logic-to-Sets bridge; Relations includes a Set/Logic prerequisite bridge;
Functions builds on Relations; Permutations begins with a Functions/bijections bridge;
Integers connects divisibility, base representation, primes, and Euclidean algorithms;
Matrices connects array operations to transformations and Boolean reachability;
and Counting builds on finite sets, factorials, and ordered versus unordered choices.
The suggested browsing order does not require finishing Permutations before studying Integers
or finishing Integers before studying Matrices. Matrix operations also build on ideas from
Functions, Relations, and Permutations. Counting can follow Sets and Permutations directly;
Matrices is not a prerequisite. Graphs builds on Sets and Relations; Matrices helps
with adjacency representations, and Counting supports graph and coloring counts.
Posets builds on Relations and Sets, connecting partial orders and Hasse diagrams to lattices
and Boolean algebra. Graphs helps with diagrams but is not a required preceding map.
Proof Methods & Induction consolidates direct proof, contraposition, contradiction,
counterexamples, and ordinary induction, including different starting indices.
It can follow Logic and basic integer reasoning directly; Posets is not a prerequisite.
Strong induction remains a planned extension. Sequences & Recurrences
connects recursive definitions, summations, induction, and elementary recurrence
solving. Discrete Probability builds on Sets and Counting through sample spaces,
events, conditional probability, and independence.
The browsing route is a suggestion, not a requirement to finish every earlier map.
Use these when designing the future cross-topic graph. The sequence is provisional;
topics overlap and proof techniques may be introduced earlier.

## Remaining-task handoff

Complete the two remaining standalone maps in this order:

1. **Sequences & Recurrences** — sequences, summations, recursive definitions,
   initial conditions, and elementary recurrence solving.
2. **Discrete Probability** — sample spaces, events, counting-based probability,
   conditional probability, and independence.

Chapter 11 is available as a reviewed prototype. Its remaining scope includes strong
induction and more written-proof practice. Carry these items into the full-curriculum
repair pass; ordinary induction with a different starting index is not strong induction.

Finishing chapter 13 ends the independent-map production milestone. It does not
mean the curriculum is finished. Before unified-platform work begins, perform one
full repair and standardization pass across all thirteen chapters:

- verify every module against its recorded sources and resolve open content notes;
- align vocabulary, notation, chapter names, prerequisites, and cross-topic links;
- review every question, answer key, explanation, worked example, and lab result;
- standardize mastery thresholds, retries, mixed practice, saved progress, and reset behavior;
- distinguish scored practice from ungraded written drafts, preserving both during migration;
- preserve stable node and question identifiers for future progress migration;
- test navigation, keyboard access, focus behavior, narrow screens, and browser storage;
- update the root guide, totals, module records, source register, and coverage reports; and
- define the validated cross-topic prerequisite graph used by the future platform.

The completion handoff should report which checks passed, which limitations remain,
and which content or interaction decisions must carry into platform integration.

## Development stages

1. **Independent interactive maps — current.** Complete the two remaining modules
   so the repository contains all thirteen planned chapters.
2. **Full-curriculum repair.** Apply the completion handoff above to every chapter,
   including earlier prototypes and the final three chapters.
3. **Standardize content and graph.** Extract stable IDs and shared schemas from
   the repaired modules; validate prerequisites and question references.
4. **Unified website.** Build navigation and reusable components after content contracts stabilize.
5. **Accounts and persistent mastery.** Add synchronized progress and local-progress migration.
6. **Mistake collection and review queue.** Store useful feedback and schedule review.
7. **Adaptive Daily Quest.** Assemble focused sessions from prerequisites and learning evidence.

Prototype availability does not mean topic completion. Record real milestones in Git;
do not fabricate historical commits or mark planned features complete.
