# Posets references

Primary source: **Steven T. Dougherty, Michael Engling, and Serap Şahinkaya,
Partially Ordered Sets**, supplied as `Poset.pdf`, 34 pages. No publication date is
printed in the chapter. Its PDF creation timestamp is January 14, 2022; that is file
metadata, not a verified publication date. Reviewed 2026-11-07. The supplied PDF is
not redistributed here.

Page references use the printed numbers, which match the PDF page numbers.

| Source section | Pages | Main material |
| --- | --- | --- |
| 1. Partially Ordered Sets | 1–11 | Relation axioms, comparability, linear orders, divisors, Hasse diagrams, extrema, bounds, isomorphisms, Exercises 1–7 |
| 2. Lattices | 12–17 | Meet/join, lattice laws, distributivity, bounds, complements, modularity, Exercises 8–14 |
| 3. Boolean Algebras | 18–28 | Power sets, squarefree divisors, bitstrings, Boolean functions, minterms, truth-table construction, Exercises 15–18 |
| Solutions | 28–34 | Answers and proof sketches for the three sections |

## Source corrections and conventions

The source was checked independently. The supplied HTML already corrects several
of the following issues; they are retained rather than copied from the printed key.
This list records relevant discrepancies, not a claim that every typo has been found.

- **Page 4, Theorem 3:** for `n>1`, the divisor poset is linear exactly when `n` is a
  prime power. The singleton `D1` is also linear and is handled separately.
- **Page 6, minimal-element definition:** the printed inequality is reversed.
  Minimal means there is no distinct element strictly below it.
- **Page 9, Example 32:** the claimed common upper bounds disagree with Example 19's
  diagram and relation on page 5. In that poset, `{b,c,d}` has no upper bound:
  `e` is above `c` but not `d`, and `f` is above `d` but not `c`. Its greatest lower
  bound is `b`. The module's bowtie lab uses its own explicitly stated order.
- **Page 12, Example 36:** the prose briefly reverses intersection and union. The
  displayed operations are correct: join is union and meet is intersection in a
  full power-set lattice.
- **Page 13, Theorem 9:** the join proof must use `lcm(a,b)`, not the printed `gcd`.
- **Page 14, Example 42:** the top of `P(A)` is `A`, not `L=P(A)`.
- **Pages 15–16:** `n/a` is a complement of `a` in `Dn` only when
  `gcd(a,n/a)=1`; equivalently its meet with `a` is 1 and its join is `n`.
  Every element has a complement exactly when `n` is squarefree. In `D24`,
  `2` and `12` fail both complement equations, despite multiplying to 24.
  The source's unrestricted complement notation in Example 44 is therefore unsafe.
- **Page 18:** the Boolean-algebra definition is mislabeled “Modular Lattice.”
  The chapter uses a power-set-isomorphism definition. This module emphasizes finite
  Boolean algebras, where that characterization agrees with a bounded distributive
  complemented lattice. Arbitrary infinite Boolean algebras need not be isomorphic
  to a full power set. This distinction is also explained in
  [McGill MATH 318 notes, Section 4.1](https://www.math.mcgill.ca/makkai/MATH3182007/318074S1.pdf),
  pages 99–100. The chapter's convention allows the singleton `P(∅)` and `D1`.
- **Page 21, Example 51:** `101∧010=000`, not `111`; the latter would be OR.
  Also, `(101∨011)′∧110=000`, not the printed `110`.
- **Pages 25–26, Examples 56–58:** the repeated expression in the table headings
  does not match the outputs. Construct formulas from the actual rows, and verify
  every assignment. Example 56 is true only at `011`; Example 57 at `000,100,110`;
  Example 58 is false only at `110,111`.
- **Page 29, Exercise 1(7) solution:** ordering people by height is not necessarily
  antisymmetric, because distinct people can have equal height. The stated relation
  is not a partial order without identifying equal-height people or changing the set.
  **Exercise 3(3):** `(ℤ,≤)` has neither a least nor a greatest element; 0 is not least.
- **Page 31, Exercise 11:** parts (6) and (7) evaluate to `2` and `30`, respectively,
  rather than the printed `30` and `5`.
- **Page 32:** Exercise 12(4) gives `{3}`, not `{2,3}`; Exercise 15(5) factors
  `143=11×13`, not `12×13`; Exercise 16(3) is the four-bit result `0001`, not `00011`.

The source's six-element nondistributive lattice has four incomparable middle
points. The module's five-element `M3` is a smaller parallel example. `N5`, explicit
cover terminology, and the interactive checks are teaching extensions. Reconstructing
order from finite upward cover paths is used for finite posets; it does not hold for
every infinite poset, such as the real numbers with their usual order.

The source collection is [Discrete Mathematics Resources](https://sites.google.com/view/discretemathematicsresources/home).
This record attributes the supplied material; it does not establish instructor
endorsement or alter source reuse terms.
