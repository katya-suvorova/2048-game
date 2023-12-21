# 2048 game
- [DEMO LINK](https://katya-suvorova.github.io/2048-game/)
- Technologies: HTML, SCSS, JS;
- Description:
1) The game field is 4 x 4
2) Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
3) The player can move cells with keyboard arrows
4) All the numbers move in the selected direction until all empty cells are filled in
   - 2 equal cells merge into a doubled number
   - The merged cell can’t be merged twice during one move
5) The move is possible if at least one cell is changed after the move
6) After each move, 2 or 4 appears in a random empty cell. The probability of 4 is 10%.
7) When the value 2048 is displayed in any cell, a win message is shown.
8) The `game over` message is shown if there are no more available moves.
9) When the game starts, the start message is hidden.
10) The `Start` button changes to `Restart` after the first move.
11) The score increases with each move by the sum of all merged cells.


