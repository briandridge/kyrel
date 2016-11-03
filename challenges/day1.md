## INTRODUCTION TO COMMANDS

1. turn_3rd_cell_blue - [solution](/challenges/solutions/turn_3rd_cell_blue.js)

  * start:  ['.', '.', '.', '.', '.']
  * finish: ['.', .', 'b', '.', '.']

moveRight();
moveRight();
useBlue();
draw();

2. erase_3rd_cell - [solution](/challenges/solutions/erase_3rd_cell.js)

  * start:  ['b', 'b', 'b', 'b', 'b']
  * finish: ['b', 'b', '.', 'b', 'b']

function main(b) {
moveRight();
moveRight();
useBlue();
erase();

3. every_other_erase - [solution](/challenges/solutions/every_other_erase.js)

  * start:  ['b', 'b', 'b', 'b', 'b']
  * finish: ['b', '.', 'b', '.', 'b']

function main(b) {
moveRight();
erase();
moveRight();
moveRight();
erase();

4. every_other_blue - [solution](/challenges/solutions/every_other_blue.js)

  * start:  ['g', 'g', 'g', '.', '.']
  * finish: ['g', 'b', 'g', 'b', '.']

moveRight();
useBlue();
draw();
moveRight();
moveRight();
useBlue();
draw();



5. move_start_to_finish - [solution](/challenges/solutions/move_start_to_finish.js)

  * start:  ['b', '.', '.', '.', '.']
  * finish: ['.', '.', '.', '.', 'b']

erase();
moveRight();
moveRight();
moveRight();
moveRight();
useBlue();
draw();

  * start:  ['g', '.', '.', '.', '.']
  * finish: ['.', '.', '.', '.', 'g']

erase();
moveRight();
moveRight();
moveRight();
moveRight();
useGreen();
draw();

  * start:  ['.', '.', '.', '.', '.']
  * finish: ['.', '.', '.', '.', '.']


