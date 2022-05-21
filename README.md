# lights-out

Game board of Lights out.
 Properties:
 
  - nrows: number of rows of board
  - ncols: number of cols of board
  - chanceLightStartsOn: float, chance any cell is lit at start of game
 
 State:
  - hasWon: boolean, true when board is all off
  - board: array-of-arrays of true/false
 
For this board:

        .  .  .
        O  O  .     (where . is off, and O is on)
        .  .  .

This would be: [[f, f, f], [t, t, f], [f, f, f]]

Deployment server: https://yagneswar17.github.io/lights-out/
