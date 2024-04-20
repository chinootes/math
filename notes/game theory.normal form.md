---
id: b8a3hqqg6t515k7sfddbdn6
title: Normal Form
desc: ''
updated: 1713213642810
created: 1713212811724
---

Matrix representing [[game theory.games]].

1. The [[game theory.games.players]] are represented as the two axes.
2. The [[game theory.games.strategy]]s for each player are represented as the rows and columns.
3. The [[game theory.games.payoffs]] are mentioned inside the cells of the matrix.

    Payoffs are listed in order X, Y. That is, payoffs for player whose strategies are listed in rows or x-axis (in this case, player A) are written first, followed by payoff for the player whose strategies are written in columns or y-axis (in this case, player B).

|          |       |      Player B       |
-----------|-------|----------|----------|
|          |       | SB1      | SB2      |
| Player A |   SA1 | A11, B11 | A12, B12 |
|          |   SA2 | A21, B21 | A22, B22 |
