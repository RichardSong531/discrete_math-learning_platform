# Counting references

Primary source: **Steven T. Dougherty, Gary Greaves, and Frédérique Oggier,
Combinatorics**, dated January 10, 2026, supplied as `counting.pdf` (21 PDF pages).
Reviewed 2026-11-02. The source resource collection is
[Discrete Mathematics Resources](https://sites.google.com/view/discretemathematicsresources/home).
The supplied PDF is not redistributed here.

| PDF pages | Module coverage |
| --- | --- |
| 1–4 | Slots and choices, product rule, Cartesian products, powersets, ordered choices |
| 4–8 | Permutations, factorials, partial permutations, repeated objects |
| 8–14 | Combinations, Pascal identities, symmetry, binomial theorem, formula selection, Chess-960, card exercises |
| 14–15 | Pigeonhole and generalized pigeonhole principles, socks and suits |
| 16–17 | Passwords, complements, inclusion–exclusion, exact digit positions, ranked-award exercises |
| 18–21 | Selected exercise solutions used for verification |

## Source corrections and conventions

- Page 11: the binomial expansion sum starts at `k=0`, retaining the `xⁿ` term.
  The map already corrects the source's lower bound of 1.
- Page 12: Pascal row sums run from `k=0` through `n` and equal `2ⁿ`; the map
  clarifies the source's indexing/formatting.
- Page 20, solution 31: a specified runner among the top three of eight ranked
  awards has `3P(29,7) = 23,598,993,600` outcomes. The source's expression and printed
  total `25,284,636,000` do not correctly enforce the specified runner's top-three
  placement. The map retains the corrected count.
- The source's five-card flush exercise counts all same-suit hands, including
  straight flushes, giving `4C(13,5)=5,148`.
- The MISSISSIPPI frequency question explicitly orders letters as M, I, S, P,
  making its answer `1,4,4,2` unambiguous.
- Empty selections have one outcome. Nonnegative integer selections larger than
  the available distinct set have zero outcomes; factorial-ratio formulas require
  their usual domain restrictions. Password labs use positive lengths, and the
  combinations-with-repetition chooser uses at least one object type.

The map is an adaptation and learning prototype, not a full transcription or solution
manual. Attribution does not establish course endorsement or alter source reuse terms.
