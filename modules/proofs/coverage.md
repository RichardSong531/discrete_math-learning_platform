# Methods of Proof coverage and review

Reviewed 2026-11-08 against Michael P. Allocca's supplied *Methods of Proof*, pages
1–23. This is a source-alignment review, not verification against an instructor's
current syllabus or a guarantee of examination coverage.

## Included

All 40 nodes, 160 question keys and explanations, 51 glossary entries, and the
proof-scaffold strings were reviewed. All scored answer keys are mathematically
consistent with their prompts; the original map already shuffles answer choices.
The 65 distinct prerequisite edges refer to valid nodes, form an acyclic graph,
and allow all 40 nodes to become ready.

| Learning area | Nodes | Material |
| --- | --- | --- |
| Foundations and groundwork | 1–8 | Universal evidence, counterexamples, axioms, logical rules, exhaustive cases |
| Direct proof | 9–17 | Implications, parity definitions, proof prose, multiple premises, WLOG, divisibility and transitivity |
| Quantifiers | 18–22 | Universes, arbitrary elements, existential witnesses, uniqueness, mixed quantifier order |
| Contrapositive | 23–26 | Converse/inverse distinction, even-square reverse implication, negated divisibility, quadratic parity |
| Biconditionals | 27–29 | Both directions, reuse of lemmas, scoped equivalence chains |
| Contradiction | 30–33 | Negation of a target, no greatest even integer, irrationality of √2, mutually exclusive parity |
| Induction | 34–39 | Base, hypothesis, step, arithmetic/geometric sums, arbitrary starting index |
| Synthesis | 40 | Method selection and recognition of proof obligations |

The chapter was read in full, and relevant original formulas and proof templates
were visually inspected. Source discrepancies are recorded in [references](references.md).

## Depth and remaining scope

- **Strong induction is not included.** Starting at `n₀` is a variation of ordinary
  induction. A strong-induction lesson, worked proof, and practice remain necessary
  to meet the broader chapter-11 curriculum target.
- Written proof drafts are practice notes; they are not automatically verified.
  Four-question mastery scores primarily assess recognition and short reasoning,
  not independent proof-writing skill or long-term retention.
- The module represents all seven named source sections but does not reproduce
  all 21 numbered source exercises and their subparts. Power-set induction,
  well-ordering arguments for prime divisors, infinitely many primes, the
  Archimedean principle, calculus witness exercises, and the absolute-value example
  do not have dedicated lessons or assessed proofs here.
- Counterexample exploration evaluates `n²−3n+43` on a bounded range. Parity and
  divisibility labs illustrate symbolic arguments with bounded numeric inputs.
  Such examples support exploration; they do not prove an infinite universal claim.
- The quantifier evaluator uses three fixed finite, nonempty universes and four
  predicates. It does not evaluate arbitrary formulas, real domains, empty-domain
  conventions, or nested-quantifier expressions.
- The implication transformer uses four fixed claims. The rules and biconditional
  panels are references. The step-order lab checks four predetermined scaffolds,
  not arbitrary proofs or every valid ordering of equivalent steps.
- The induction explorer presents three claims and their symbolic successor
  arguments alongside numerical illustrations. It is not a proof assistant or a
  general recurrence solver.
- The strategy exercise identifies the source's natural method. Other valid
  approaches are possible and require evaluation of the actual argument.

## Content review

- Checked the prime-polynomial counterexample, parity expansions, divisibility
  witness substitutions, conditional negations, quantifier scope, square-root
  contradiction, and the three induction identities against their definitions.
- Corrected broken divisibility key-point formatting and clarified glossary scope,
  finite-example limits, and integer witnesses. The divisibility transformer's
  inverse requires an OR, not an AND, after negating its conjunctive consequent.
- Source errors are documented without treating incomplete or false exercise
  statements as valid scored claims.

## Runtime validation

Browser validation on 2026-11-08 passed 160 acceptance checks with no uncaught
browser errors, 303 independent mathematical-lab checks, and targeted interaction
and shared-navigation checks:

- Rendered every lesson and graded all 40 question sets. Incomplete attempts reveal
  no answer explanations; completed attempts lock against duplicate submission.
  Current and best scores, progress, and recommendations stay consistent.
- Checked shuffled retries and mixed sets of 4 and 12 questions. Refreshing a quiz
  preserves its lab state and proof draft; mixed results preserve per-node mastery.
- Verified literal draft text, per-node persistence, reload, replacement/cancellation,
  and separate mastery/draft resets. Malformed and unavailable browser storage
  recover without crashing; unavailable storage is reported visibly.
- Exercised numeric validation, keyboard step ordering and focus, glossary search,
  and printable written drafts. All 40 lessons fit a 390-pixel viewport; targeted
  checks also passed at 768 and 1440 pixels. Desktop and mobile screenshots were
  inspected visually.
- Checked navigation across all eleven maps, including Posets → Proofs → topic
  guide, keyboard access, and 219 local links in the changed HTML and documentation.
- Compared the prime-polynomial explorer for all inputs 1–100 with an independent
  sieve, all 36 finite-quantifier combinations with their definitions, and parity,
  divisibility, and inverse examples with independent calculations. Checked all four
  conditional transformations, three induction arguments and stage controls, four
  model proof orders, eight strategy recommendations, and five source-error repairs.

These checks cover the supplied interactions and reviewed content. They do not
certify arbitrary written proofs, constitute a comprehensive accessibility audit,
or establish alignment with an instructor's current assessment requirements.
