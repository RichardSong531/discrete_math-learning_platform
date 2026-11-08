# Methods of Proof references

Primary source: **Michael P. Allocca, Methods of Proof**, supplied as
`MethodsOfProof.pdf`, 23 pages. No publication date is printed in the chapter.
The PDF creation timestamp is June 29, 2021; that is file metadata, not a verified
publication date. Reviewed 2026-11-08. The supplied PDF is not redistributed here.

Page references use the printed numbers, which match the PDF page numbers.

| Source section | Pages | Main material |
| --- | --- | --- |
| Introduction and 1.1 Groundwork | 1–5 | Proof versus examples, prime-polynomial counterexample, axioms, modus ponens, given/replacement/tautology rules |
| 1.2 Direct Proofs | 5–9 | Conditional proof, parity, readable proof prose, multiple hypotheses, cases, divisibility |
| 1.3 A Note on Quantifiers | 10–13 | Hidden universals, arbitrary elements, witnesses, existence and uniqueness, quantifier order |
| 1.4 Proofs by Contrapositive | 13–16 | Logical equivalence, even-square converse, negated divisibility, quadratic parity |
| 1.5 Biconditional Proofs | 16–17 | Both directions, reuse of earlier results, reversible equivalence chains |
| 1.6 Proofs by Contradiction | 18–20 | Negating a claim, no greatest even integer, irrationality of √2, negation of a conditional |
| 1.7 Inductive Proofs | 20–23 | Base case, inductive hypothesis, successor step, arithmetic and geometric sums, starting-index generalization |

## Source corrections and conventions

The source was checked independently, including visual inspection of the title,
key proof formulas, exercises, and induction templates. The supplied HTML already
corrects several of the following errors. This list records relevant discrepancies,
not a claim that every source typo has been found.

- **Pages 7 and 10–11, Example 7 and Theorem 2:** the unintroduced variable `y`
  should be `b`: `a+c=2(k+ℓ−b)`.
- **Page 8, Example 9:** the even product has form `2s`, not the printed `2s+1`.
  The preceding algebra correctly gives `ab=2(2k₁k₂+k₁)`.
- **Pages 14 and 16, Examples 14 and 17:** the square expands as
  `(2k+1)²=4k²+4k+1`; `4k⁴` is a typo.
- **Page 14, failed square-root argument:** taking a square root does not establish
  the required integer-parity conclusion, and in general `√(a²)=|a|`, not `a`.
  The source's broader suggestion that a proof about integers may never use real
  intermediates is too restrictive. The map focuses on the unsupported conclusion
  and gives the valid contrapositive proof.
- **Page 17, Example 18:** the abbreviated displays must end with `a+1 is odd`,
  not `a is odd`. The backward chain must also begin with `a+1`. Integer witnesses
  in a full equivalence chain need existential scope.
- **Page 20, Example 22:** the three-element set should be `{a₁,a₂,a₃}`, not the
  printed `{a₁,a₂,a₂}`. This power-set argument is not a dedicated module exercise.
- **Pages 20–23, induction terminology:** mathematical induction is a rigorous
  deductive proof method, distinct from generalizing from observed examples.
  The source's “generalized induction” changes the initial index; it does not
  introduce strong induction, whose hypothesis includes all earlier eligible cases.

The following source exercises are not copied into the scored question bank:

- **Page 9, Exercise 2:** the target residue `x` is unspecified, so the printed
  problem is incomplete as a fixed congruence claim.
- **Page 9, Exercise 3:** the claim about `aⁿ−1` needs domain restrictions such as
  integers `a≥2`, `n≥2`; allowing `a=4,n=1` gives the prime 3 and defeats the stated
  conclusion. The module does not silently supply omitted assumptions.
- **Page 16, Exercise 10(4):** as printed, the claim is false. For `a=1`,
  `a³+3a²−9=−5` is odd, but `a` is not even.

The chapter takes natural numbers to start at 1 and defines `a | b` only for
nonzero divisor `a`. That divisibility convention is used consistently in this
module, including when the middle term of a transitivity example is a divisor.
For the irrationality proof, `a/b` means integers `a,b`, `b≠0`, in lowest terms.

The finite quantifier evaluator, numerical explorers, step-order exercises,
bilingual glossary, and multiple-choice questions are teaching extensions. A
preferred strategy is not necessarily the only valid proof method, and a different
sound proof presentation need not match the step-order model.

The source collection is [Discrete Mathematics Resources](https://sites.google.com/view/discretemathematicsresources/home).
This attribution does not establish instructor endorsement or alter source reuse terms.
