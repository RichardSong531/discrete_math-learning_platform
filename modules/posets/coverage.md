# Posets coverage and review

Reviewed 2026-11-07 against the supplied *Partially Ordered Sets* chapter, pages 1–34.
This is a source-alignment review, not verification against an instructor's syllabus
or a guarantee of examination coverage.

## Included

All 41 nodes, 164 question keys and explanations, and 48 glossary entries were
reviewed against the source and independently checked mathematically. The 65 distinct
prerequisite edges match the node dependencies, form an acyclic graph, and allow
every node to become ready. All three sections are represented:

| Learning area | Nodes | Material |
| --- | --- | --- |
| Posets | 1–15 | Relation axioms, comparability, chains, divisors, finite Hasse diagrams, extrema, bounds, isomorphism, proof-method recognition |
| Lattices | 16–29 | Pairwise meet/join, set and divisor lattices, finite bounds, lattice identities, distributivity, complements, modularity |
| Boolean algebras | 30–40 | Finite power-set structure, cardinality, squarefree divisors, characteristic bits, Boolean operations, De Morgan, truth tables, minterms and sum of products |
| Synthesis | 41 | Distinguishing posets, lattices, and Boolean algebras using examples and counterexamples |

The chapter and key diagrams were visually inspected as well as text-extracted.
Source discrepancies and conventions are recorded in [references](references.md).

## Depth and lab limits

- Multiple-choice questions assess definitions, short computations, counterexamples,
  and proof-method selection. The “proof workshops” do not grade written proofs,
  and the map does not reproduce all 18 source exercises and their subparts.
- The relation editor has four fixed elements. The power-set lab uses subsets of
  `{1,2,3}`. The bounds lab uses a fixed four-element bowtie; it is not a general
  arbitrary-subset bound solver.
- Divisor diagrams support positive integers through 360. The Boolean divisor
  classifier supports integers through 50,000. These finite examples illustrate
  order structure; they are not a general large-integer factorization service.
- Isomorphism practice compares fixed pairs `D6→D55` and `D8→D6`. The lattice-law
  lab offers `M3`, a four-element Boolean diamond, a four-element chain, and `N5`.
  It does not accept arbitrary lattice definitions or construct isomorphism proofs.
- Bit operations use equal-length strings of 2–8 bits. Truth-table construction
  uses three variables and all eight assignments. Canonical sum of products is
  correct by construction but need not have the fewest terms or literals; there
  is no general expression parser or Boolean minimizer.
- Infinite orders appear as conceptual examples. Cover-path reconstruction and
  the interactive diagrams are finite; general infinite Boolean-algebra theory
  and complete-lattice theory are beyond this module.
- Each mastery check reuses a four-question pool with shuffled presentation. A
  4/4 score is a practice signal, not proof of durable retention or proof-writing
  skill. Mixed Practice does not change individual-node mastery.

## Validation

- All 41 node checks render and grade correctly, including full, partial, and zero
  scores. Incomplete attempts do not reveal explanations; repeated submissions do
  not add attempts. Current and best scores update together. New sets unlock a
  fresh attempt. Mixed Practice uses the actual available question count and
  leaves node mastery unchanged.
- Reload, confirmed/cancelled reset, malformed saved progress, and unavailable
  browser storage were checked. Invalid stored entries do not crash the map or
  grant unsupported mastery.
- Independent arithmetic checks covered every divisor lattice through 360,
  including divisor lists, prime factors, gcd, lcm, and boundary inputs. The four
  lattice models were compared with explicit order tables. All 64 power-set pairs
  and all 16 bowtie pairs were checked, along with relation presets, isomorphism
  edits, and Boolean/bitstring input validation.
- Both generated formulas were independently parsed and evaluated on all eight
  rows for each of the 256 three-input truth functions (4,096 evaluations).
- Keyboard activation preserves focus across the knowledge graph, relation
  matrix, divisor and power-set diagrams, isomorphism selectors, and truth rows.
  Glossary search and Recommended next were exercised.
- All 41 lessons fit a 390-pixel viewport, with horizontal scrolling confined to
  the intentionally wide knowledge map. Desktop and phone screenshots were
  inspected. The guide and existing topic navigation were checked at desktop,
  tablet, and phone widths; local HTML links resolve.
- The review used 156 lesson/runtime acceptance checks and 236 lab/UI checks,
  with no uncaught browser errors. These local checks do not add a package manager,
  build step, or automated test suite to the standalone curriculum repository.
