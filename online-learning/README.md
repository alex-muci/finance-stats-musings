# Regret and Rebalancing

A self-study textbook on online learning, with applications to portfolios, option pricing and trading.
It follows Jacob Abernethy's EECS 598 "Prediction, Learning, and Games" (University of Michigan, Fall 2013)
across 16 chapters in six parts, plus two appendices. Every chapter has worked proofs, finance sidebars,
and exercises with solutions.

| File | What it is |
| --- | --- |
| [`regret-and-rebalancing.pdf`](regret-and-rebalancing.pdf) | The book (A4, 91 pages) |
| [`regret-and-rebalancing.tex`](regret-and-rebalancing.tex) | LaTeX source (single file) |
| [`figures/`](figures) | Figures used by the LaTeX source |
| [`regret-and-rebalancing.html`](regret-and-rebalancing.html) | Interactive edition with live Hedge and universal-portfolio demos (download and open in a browser) |

## Building the PDF

The source compiles with pdfLaTeX and standard TeX Live packages (`tcolorbox`, `titlesec`, `mathpazo`,
`booktabs`, `tabularx`, `hyperref`). It also works on Overleaf.

```sh
pdflatex regret-and-rebalancing.tex
pdflatex regret-and-rebalancing.tex   # second pass fills in the table of contents
```

## Contents

1. **Prediction with Expert Advice**: the online learning game, Halving, Weighted Majority, Hedge, Fixed Share, lower bounds
2. **Games, Equilibria and Their Uses**: minimax via Hedge, linear programs and boosting, the Perceptron
3. **Online Convex Optimization**: online gradient descent, Follow the Regularized Leader, Bregman divergences, FTPL
4. **Finance**: Kelly betting and Cover's universal portfolios, game-theoretic probability and option-price bounds
5. **Bandits**: explore-then-commit, UCB, EXP3, combinatorial and convex bandits
6. **Approachability, Calibration and Equilibrium**: Blackwell approachability, calibration, swap regret and correlated equilibria

Appendix A is a mathematical toolkit and a table of regret bounds; Appendix B lists books, papers and project ideas.
