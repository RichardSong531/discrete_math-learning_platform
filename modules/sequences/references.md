# Sequences & Recurrences references

Primary source: the supplied **Chapter 4: Sequences**,
`Discrete_Math_Sequences (1).pdf`, 33 pages. The
[Discrete Mathematics Resources index](https://sites.google.com/view/discretemathematicsresources/home)
credits **Jose Franco and Pedro Morales-Almazan**. The PDF itself does not print
an author or publication date. Its creation metadata is August 5, 2021, which is
not a verified publication date. Reviewed 2026-11-10. The PDF is not redistributed
here. Printed page numbers match PDF page numbers.

| Source section | Pages | Main material |
| --- | --- | --- |
| 4.1.1 Preliminaries | 1-6 | Sigma notation, linearity, reindexing, finite index sets, empty sums |
| 4.1.2-4.1.4 Sequences | 6-10 | Sequences as functions, Fibonacci indexing, arithmetic and geometric sequences, exercises |
| 4.2 Sequences and induction | 10-18 | Induction, well-ordering, sum identities, counterexamples, strong induction and prime-factorization existence |
| 4.3 Recurrence relations | 18-20 | Lists, formulas, recurrence order, initial values, factorial recurrence, exercises |
| 4.4.1 First-order linear recurrences | 20-23 | Homogeneous and non-homogeneous equations, substitution, monthly growth and deposits |
| 4.4.2 Second-order recurrences | 23-26 | Characteristic roots, repeated roots, initial conditions, Fibonacci closed form |
| 4.4.3-4.4.4 Generating functions | 26-29 | Shifting, geometric-series coefficients, partial fractions, two worked examples, exercises |
| 4.5 Linear algebraic methods | 29-33 | Optional vector systems, diagonalization, companion matrices, second- and third-order examples |

## Corrections and conventions

The complete chapter was read, and 21 pages containing important formulas and
examples were inspected visually. The supplied HTML already corrects several
source errors. These notes identify relevant issues, not an exhaustive errata
sheet.

- **Page 4, Proposition 2:** the left lower summation bound is misprinted as
  `i+a`; it should be `i=a`. Reindexing changes the bounds and summand together.
- **Pages 8 and 25, Fibonacci:** with `F_0=F_1=1`, use
  `F_(n+1)=F_n+F_(n-1)` for `n>=1`, or equivalently
  `F_n=F_(n-1)+F_(n-2)` for `n>=2`. The printed `n>1` skips `F_2`.
  The corresponding Binet formula uses powers `n+1`.
- **Page 12, induction base:** the displayed denominator in `1(1+1)/1` should
  be 2. The module's base case is `1=1(1+1)/2`.
- **Pages 14-15, arithmetic/geometric indexing:** when an initial term at index
  zero is supplied, the one-step recurrence must apply starting at index 1.
  A multiplicative rule also makes sense when a term is zero, although a ratio
  involving division by that term is undefined.
- **Page 15, Euler polynomial:** `n^2+n+41` gives primes for `n=0,...,39`,
  then `p_40=41^2` is composite. The claim about the first 41 terms is false;
  `p_41=41*43` is another counterexample.
- **Pages 16-17, strong induction:** the hypothesis must cover **every** preceding
  index in the relevant range. In the factorization example that range is
  `2<=j<=k`. This argument establishes existence of a prime factorization, not
  uniqueness. Ordinary induction can prove the cumulative claim that all cases
  through `k` hold, giving the equivalent strong-induction formulation.
- **Page 19, recurrence order:** the required initial values are `k` values for
  the standard order-`k` setup, not the printed `n` values. Order measures the
  furthest effective lag; intervening lags may have zero coefficients.
- **Page 20, Problem 3(a):** `a_0=1` and `a_n=a_(n-1)+2n+1` give
  `a_n=(n+1)^2`, not `n^2`.
- **Page 23, deposits:** the printed expression for the second month omits the
  existing principal. The stated recurrence gives `a_2=2001*1.001+1000=3003.001`.
  Here `a_m` means the balance just after the deposit at month boundary `m`, with
  the initial deposit at `m=0`. For `n` years there are `12n` monthly steps.
- **Page 24, repeated-root coefficient:** for nonzero root `r=c/2`,
  `C_1=a_0` and `C_2=a_1/r-a_0=2a_1/c-a_0`. The displayed `a_1/c-a_0`
  is missing a factor of 2. When `c=d=0`, arbitrary `a_0,a_1` are followed by
  zero terms from index 2; the usual repeated-root expression is not a general
  two-parameter solution for that degenerate case.
- **Page 25, distinct-root proof:** the squared bracket in the negative-root
  branch needs denominator 4, matching the positive-root branch. The final
  characteristic-root solution is correct.
- **Pages 30-33, matrix notation:** recover the original column vector by left
  multiplication by `U`. The second decoupled update in Example 17 is
  `b_(2,n+1)=-b_(2,n)`. In Example 18 the transformed starting vector is indexed
  at zero; the displayed transformation and initial-condition subscripts are
  inconsistent. The final formula `(2^n+(-1)^(n+1))/3` agrees with seeds
  `0,1,1`. In the second-order derivation, modal coefficients must be distinguished
  from original state components; use `v_n=U Lambda^n U^-1 v_0`.

Several printed exercise claims need correction and are **not** imported as
scored questions:

- Page 17, Problem 1(c): the finite geometric sum is `(a^n-1)/(a-1)` for
  `a!=1`; it is `n` when `a=1`.
- Page 18, Problem 1(e): under the chapter's `F_0=F_1=1` convention,
  `sum_(k=1)^n F_k=F_(n+2)-2`, not `F_(n+2)-1`.
- Page 18, Problem 2(a): `n!>=2^n` does not hold at `n=2,3`; it holds for
  integers `n>=4`.
- Page 18, Problem 2(c): Bernoulli's inequality is non-strict in general;
  equality occurs, for example, when `x=0` or `n=1`.
- Page 18, Problem 3(b): 11 people cannot be partitioned into groups of 4 or 5.
  Every integer size at least 12 can be so represented, as can 8, 9, and 10.

Generating-function identities in the module are interpreted as formal power
series. If evaluated analytically, convergence restrictions must also be checked.
Negative characteristic discriminants produce complex conjugate roots; the
numerical panel still iterates the real recurrence. Matrix methods retain the
source's optional status. Interactive panels, dependency edges, bilingual
glossary, and mastery questions are learning extensions. Attribution does not
establish instructor endorsement or change the source's reuse terms.
