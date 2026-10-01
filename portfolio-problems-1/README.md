# Portfolio Problems 1

Selected proofs on the real number system, the Axiom of Completeness, and sequences, completed for Real Analysis (MTH 337) at Muhlenberg College.

## Goal

Demonstrate foundational proof techniques in real analysis, focusing on least upper bounds, contradiction arguments using the Archimedean property, and sequence limits.

## What I Created

A 3-page LaTeX document containing complete proofs for three core real analysis problems:
- **Exercise 1.3.3:** Proving the duality between infima and suprema ($\sup B = \inf A$, where $B$ is the set of lower bounds of a non-empty set $A$ bounded below) using the Axiom of Completeness and the supremum approximation lemma.
- **Exercise 1.4.7:** Proving by contradiction that $\alpha = \sup \{t \in \mathbb{R} : t^2 < 2\}$ cannot satisfy $\alpha^2 > 2$, using the Archimedean property to construct an explicit upper bound $\alpha - 1/n < \alpha$.
- **Exercise 2.5.7:** Proving that the geometric sequence $(b^n) \to 0$ if and only if $-1 < b < 1$, handling positive, negative, and zero base cases with monotonicity and the Squeeze Theorem.

## Technologies

- LaTeX (`amsart` document class)
- AMS packages (`amsmath`, `amssymb`, `amsfonts`, `amsthm`, `fullpage`, `graphicx`, `color`)

## Features

- Formal proof structures using AMS proof environments
- Epsilon-delta and index-choice arguments
- Case analysis for sequence behavior

## Mathematical Content

- Axiom of Completeness and least upper bound properties
- Archimedean property of real numbers
- Monotone convergence and the Squeeze Theorem

## Preview

![Supremum and Infimum Duality Proof](../assets/previews/supremum-infimum-duality-proof.png)

## Files

- `main.tex` — LaTeX source
- `main.pdf` — compiled reference output

## Compiling Locally

Compile with `pdflatex`:

```bash
pdflatex main.tex
```
