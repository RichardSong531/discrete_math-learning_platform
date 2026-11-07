# Curriculum and development roadmap

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
| 11 | Proofs | Planned | Build a standalone map |
| 12 | Recurrences | Planned | Build a standalone map |

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
The browsing route is a suggestion, not a requirement to finish every earlier map.
Use these when designing the future cross-topic graph. The sequence is provisional;
topics overlap and proof techniques may be introduced earlier.

## Development stages

1. **Independent interactive maps — current.** Import existing modules, document
   operation and provenance, then review content and interactions.
2. **Complete the curriculum.** Build missing maps and review prerequisites, examples,
   answer keys, keyboard access, and small-screen use.
3. **Standardize content and graph.** Extract stable IDs and shared schemas from
   working modules; validate prerequisites and question references.
4. **Unified website.** Build navigation and reusable components after content contracts stabilize.
5. **Accounts and persistent mastery.** Add synchronized progress and local-progress migration.
6. **Mistake collection and review queue.** Store useful feedback and schedule review.
7. **Adaptive Daily Quest.** Assemble focused sessions from prerequisites and learning evidence.

Prototype availability does not mean topic completion. Record real milestones in Git;
do not fabricate historical commits or mark planned features complete.
