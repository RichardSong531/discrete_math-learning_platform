# Integers references

Primary source: **Steven T. Dougherty, André Leroy, and Esengül Saltürk,
Properties Of Integers**, supplied as `integer.pdf` (48 PDF pages; publication
date/version not stated). Reviewed 2026-10-06. The source resource collection is
[Discrete Mathematics Resources](https://sites.google.com/view/discretemathematicsresources/home).
The supplied PDF is not redistributed here.

The module follows the chapter's main exposition on pages 1–38: integer division and
divisibility, digit rules and bases, primes, gcd/lcm, Euclid and extended Euclid,
factorials, and floor/ceiling. Later exercise and solution pages are not reproduced
as a complete assessed question set. See [coverage](coverage.md).

## Corrections and conventions

- Page 16, Example 23: `42231₅ = 2816`, not `2817`.
- Page 32, Example 47: `45 = 14·3 + 3`, and
  `1 = 45·5 + 14·(−16)`. The inverse of 45 modulo 14 is still 5.
- The imported map already corrects apparent source errors in the prime-factorization
  theorem statement and the ceiling definition. Those corrections are retained.
- For nonzero signed integers, `lcm(a,b) = |ab|/gcd(a,b)`. The calculators explicitly
  extend the definitions with `gcd(0,0)=0` and `lcm(a,0)=0`.
- Zero has no prime factorization; a negative integer's factorization includes its
  sign. Modular-inverse messages require a modulus of absolute value at least 2.

The module is a learning prototype and an adaptation, not a full transcription or
solution manual. Source attribution does not establish course endorsement or alter
the source's reuse terms.
