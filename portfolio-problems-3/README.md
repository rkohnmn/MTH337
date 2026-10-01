# Portfolio Problems 3

Selected proofs on function sequences, power series, and Riemann integration, completed for Real Analysis (MTH 337) at Muhlenberg College.

## Goal

Provide rigorous mathematical proofs covering uniform convergence of function sequences, analytic properties of power series, and preservation of Riemann integrability under uniform limits.

## What I Created

A 3-page LaTeX document containing complete proofs for three advanced real analysis problems:
- **Exercise 6.2.10:** Proving that a sequence of increasing functions $f_n$ converging pointwise to a continuous function $f$ on a closed interval $[a,b]$ converges uniformly. The proof combines uniform continuity of $f$ on compact $[a,b]$, a partition with mesh $\le \delta$, and monotonicity bounds.
- **Exercise 6.5.4a:** Proving that the termwise antiderivative $F(x) = \sum_{n=0}^\infty \frac{a_n}{n+1} x^{n+1}$ of a power series $f(x) = \sum_{n=0}^\infty a_n x^n$ converges on $(-R, R)$, shares the same radius of convergence $R$, and satisfies $F'(x) = f(x)$ by termwise differentiation.
- **Exercise 7.2.5:** Proving that if each $f_n$ is Riemann-integrable on $[a,b]$ and $f_n \to f$ uniformly, then $f$ is Riemann-integrable. The proof establishes boundedness and bounds the upper and lower Darboux sum gap $U(f,P) - L(f,P) < \varepsilon$.

## Technologies

- LaTeX (`amsart` document class)
- AMS packages (`amsmath`, `amssymb`, `amsfonts`, `amsthm`, `fullpage`, `graphicx`, `color`)

## Features

- Uniform continuity and partition arguments
- Power series termwise integration and differentiation
- Darboux sums and the Riemann integrability criterion

## Mathematical Content

- Pointwise vs. uniform convergence of function sequences
- Power series and radius of convergence
- Darboux sums and Riemann integrability

## Preview

![Uniform Convergence Proof](../assets/previews/uniform-convergence-proof.png)

## Files

- `main.tex` — LaTeX source
- `main.pdf` — compiled reference output

## Compiling Locally

Compile with `pdflatex`:

```bash
pdflatex main.tex
```
