# The Fibonacci Principle

**Damped Harmonic Convergence in the k-nacci Families**  
*Series: Harmonic Structures in Natural Systems*

**Author:** Carolina Johnson (CJ)  
**Date:** November 2026  
**DOI:** [10.5281/zenodo.18227844](https://doi.org/10.5281/zenodo.18227844)  
**ORCID:** [0009-0002-8819-3347](https://orcid.org/0009-0002-8819-3347)

---

## Overview

The ratio of successive Fibonacci numbers converges to the golden ratio φ by alternating around it. Every step multiplies the error by an exact factor that tends to `-1/φ²`, so the approach to φ is a damped alternation rather than a one-sided approach.

The same construction extends to the k-nacci families, from Tribonacci to Octanacci. From Tribonacci on, the slowest subdominant roots form a complex-conjugate pair, and the ratio converges through damped harmonic modes whose decay and frequency are given exactly by the roots. The Fibonacci Principle states this convergence for the whole family.

---

## Key Contributions

- **Exact Ratio Error:** The Fibonacci ratio error is given in closed form in terms of φ alone, with a one-step map that shows both the sign change and the contraction at every step.
- **Origin of the Alternation:** The alternating sign is traced to the product of the characteristic roots, `φψ = -1`, the same property behind Cassini's identity, the Lucas identity and the norm in ℤ[φ].
- **Hurwitz Connection:** The constant `√5` in the error is Hurwitz's constant, and the Fibonacci ratios approach Hurwitz's bound.
- **k-nacci Modes:** The modulus and argument of the subdominant roots give the decay rate and frequency of each family's convergence, tabulated from Fibonacci to Octanacci, with an exact amplitude and phase for Tribonacci.
- **Physical Reading:** Each mode is a sampled damped oscillator, and the convergence rate equals the dominant-eigenvalue rate of power iteration on the companion matrix.

---

## The Exact Error

With `r(n) = F(n+1)/F(n)` and `e(n) = r(n) - φ`:

`e(n) = (-1)ⁿ √5 / (φ²ⁿ - (-1)ⁿ)`

`e(n+1) = -e(n) / (φ r(n))`

The factor `-1/(φ r(n))` is negative at every step, so the error changes sign, and its magnitude is below 1, so the error shrinks. It tends to `-1/φ² = -0.381966`.

---

## The k-nacci Families

| k | Family | Decay factor \|s\|/α | Angle θ | Period (steps) |
|---|---|---|---|---|
| 2 | Fibonacci | 0.3819660 | 180° | 2 |
| 3 | Tribonacci | 0.4008906 | 124.689° | 2.8872 |
| 4 | Tetranacci | 0.4245135 | 95.356° | 3.7753 |
| 5 | Pentanacci | 0.4430676 | 77.038° | 4.6730 |
| 6 | Hexanacci | 0.4568576 | 64.489° | 5.5823 |
| 7 | Heptanacci | 0.4670223 | 55.355° | 6.5035 |
| 8 | Octanacci | 0.4745352 | 48.415° | 7.4357 |

Fibonacci is the only family whose slowest mode is a strict alternation at 180°. From Tribonacci on, the error rotates, with a phase that advances by θ each step.

---

## Repository Contents

| File | Description |
|---|---|
| `README.md` | This file |
| `The Fibonacci Principle.pdf` | Full paper |

---

## Citation

Johnson, C. (2026). The Fibonacci Principle: Damped Harmonic Convergence in the k-nacci Families. Series: Harmonic Structures in Natural Systems. SemanticDrift. DOI: https://doi.org/10.5281/zenodo.18227844

---

## License

026 Carolina Johnson (CJ). All Rights Reserved.
