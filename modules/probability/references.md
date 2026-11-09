# Discrete Probability references

Primary source: **Joseph Klobusicky, Discrete Probability**, supplied as
`Discrete_Probability.pdf`, 41 pages. No publication date is printed in the
chapter. PDF metadata records creation on February 7, 2022; this is not a verified
publication date. Reviewed 2026-11-08. The source PDF is not redistributed here.

Page references use the printed numbers, which match the PDF page numbers.

| Source section | Pages | Main material |
| --- | --- | --- |
| Introduction | 1-2 | Scope of discrete probability and motivation |
| 3.1-3.3 Foundations | 2-7 | Sample spaces, events, axioms, probability identities, weighted outcomes |
| 3.4 Counting | 8-15 | Classical probability, order/replacement, permutations, combinations, stars and bars, birthday problem |
| 3.5 Symmetry | 15-16 | Reduced sample spaces, positions, ties |
| 4 and 4.1 Conditioning | 16-18 | Conditional probability, chain rule, independence |
| 4.2 Total probability | 19-23 | Partitions, gambler's ruin, random-walk recurrence, Vacuumba graph |
| 4.3 Bayes' theorem | 23-26 | Reversing conditionals, hypothetical tests, conditional independence, multiple hypotheses |
| 5.1-5.2 Random variables | 26-30 | State spaces, PMFs, uniform, Bernoulli, binomial, geometric, Poisson |
| 5.3 Moments | 30-35 | Expectation, large numbers, variance, standard deviation, transformations, total expectation |
| Selected solutions and references | 35-41 | Worked source exercises and bibliography |

## Corrections and conventions

The complete chapter was read. Key formulas, diagrams, and selected solutions
were inspected visually, including Figures 1, 2, 4, and 5. The supplied HTML
already corrects several of these discrepancies. This is a list of relevant
source issues, not an exhaustive errata sheet.

- **Page 3, Example 3:** sums of two standard six-sided dice range from 2 to 12,
  not 1 to 7. The sums are not equally likely under independent fair dice.
- **Page 4, Examples 6-7:** complement labels should refer to green and yellow
  in their respective bullets. Uniform selection from 1 through 11 gives even
  probability `5/11`; selection from 1 through 10 gives odd probability `5/10`.
- **Page 11, combination example:** the six reorderings of `{1,3,4}` require
  `(3,4,1)` where the source prints `(3,4,3)`.
- **Page 13, Proposition 5:** `C(n+k-1,k)` counts unordered selection **with**
  replacement. The proposition incorrectly says no replacement. The construction
  uses `n-1` bars among `n+k-1` positions and `k` stars.
- **Pages 14 and 37, orange allocations:** a ratio of allocation counts represents
  a probability only if allocations are equally likely. Independently assigning
  each orange to a uniformly chosen bag produces a different distribution over
  allocations. The module keeps counting and probability-model assumptions distinct.
- **Page 20, gambler's ruin:** the first-step equation should use the loss event
  `L`, not the undefined `T`. Exercise 43's exponents should use the appropriate
  indices: `w_(i-1)-w_(i-2)=r^(i-2)w_1` and `1-w_(n-1)=r^(n-1)w_1`, where
  `r=(1-p)/p` and `0<p<1`.
- **Page 21, equation (6):** `b_0` is the unconditional hitting probability, not
  `P(B_0|W)`. First-step conditioning gives `b_0=p+(1-p)b_(-1)`.
- **Page 26, Proposition 8:** the denominator needs prior weights:
  `sum_i P(A|B_i)P(B_i)`, with positive evidence probability `P(A)`. The displayed
  hypothesis condition must refer to the conditioning event `A`.
- **Page 30, geometric distribution:** `k` failures then a success has probability
  `(1-p)^k p`, not `p^k(1-p)`. A finite-valued geometric PMF requires `0<p<=1`.
  At `p=0` no success occurs, and the displayed finite-outcome masses sum to zero.
  This module follows the failures-before-success convention; total trials are
  one larger.
- **Page 31, large numbers:** the illustrated finite-mean result requires an
  integrability assumption such as `E[|X|]<infinity`. The module's Bernoulli
  simulation satisfies it. Finite simulation output does not prove convergence.
- **Pages 34-35, moments and transformations:** Example 31 should use `p^i q^(n-i)`
  with its summation index. Exercise 67's displayed identity additionally
  multiplies the differentiated equation by `x`. In Example 32, preimages determine
  the correct PMF subscripts and the second-moment sum uses `y^2`. The correct
  results remain `E[Y]=7/5`, `E[Y^2]=3`, and `Var(Y)=26/25`.
- **Page 40, Exercise 55 solution:** for `a!=0`, the affine preimage is
  `(y-b)/a`, not `(y-b)/x`; when `a=0`, `Y=b` is constant. The expectation identity
  follows directly by summing `(ax+b)p_X(x)` when the expectation exists.

Further source-solution issues are kept out of scored questions:

- **Page 37, Exercise 28:** the stated `n-1` draws require exponent `n-1`, not
  `n`, in the with-replacement answer. Both sequences have limit `1/e`.
- **Pages 16 and 37, Exercise 30(i):** stopping at the first striped ball means
  the fourth draw may never occur. The printed unconditional-position answer
  `1/15` does not account for that stopping rule. The module's fixed-position
  symmetry example uses a predetermined number of draws instead.
- **Page 39, Exercise 47:** the linear-system answer `3/8` agrees with the graph.
  In the alternate path sum, the two-step loop through room 1 has probability
  `1/4`; the printed binomial sum substitutes `1/3` before later using `1/4`.
- **Page 40, Exercise 60:** the proposed symmetric mass `C/x^2` needs an explicit
  definition at zero and a normalizing constant on nonzero integers.
- **Page 41, Exercise 68:** the capped variable is `Y=min(X,5)` for `X~Pois(1)`.
  References to its moments as those of `X` and to `Exp(1)` are naming errors.

Conditional probabilities require positive-probability conditioning events.
Zero-mass cells are omitted from partition sums. Finite second moments justify
the usual variance subtraction formula. Repeated binary trials use a common
success probability and independence for binomial formulas; repeated test
examples assume conditional independence in both disease-status cases.

The diagnostic examples are hypothetical probability exercises using the source's
fixed rates. Simulators, dependency edges, bilingual glossary, and mastery
questions are learning extensions. Binomial variance `np(1-p)` is explicitly
marked as an extension to the source's mean derivation. Attribution does not
establish instructor endorsement or alter source reuse terms.
