* version 1.0 PR: 

# Chess Board
In this project, we created a Chess board, which is an 8 by 8 grid of alternating black and white squares. 
The queens are red and blue squares.

Each board will have one red and one blue queen at different coordinates.
In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.


We defined a **ChessBoard**, which included the following:
1. Contains an 8x8 grid - Each cell in grid should have a color represented in RGB format. 
    - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)
2. `add_red`: that accepts a row and column as input which colors corresponding cell.
3. `add_blue`: accepts a row and column as input which colors corresponding cell.
4. `render`: displays the chess board on screen with red and blue shown in correct locations.
5. `is_under_attack`: return boolean if red is under attack by a blue piece horizontally, vertically or diagonally.


Also, the code included _user acceptance tests_, with the following test cases:

1. queens on same row should be “under attack”
2. queens on same column should be “under attack”
3. queens on same diagonal should be “under attack”
4. queens with any other coordinates should NOT be “under attack”