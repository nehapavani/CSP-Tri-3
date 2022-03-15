{% include navigation.html %)
# About
A tic tac toe game where players can play to see who wins. It is a fun and interactive game anyone can enjoy.

# [Program Code](https://github.com/christinlee367/n225_FireEradicatorsTheSequel/pull/128/commits/ff82eb26afeff32d5087e7d843efc4fc5a389a3d)

# [Runtime Video](https://user-images.githubusercontent.com/89219435/155929326-5eec9269-9bd2-44c2-9bc9-b6e41d39c7ff.mp4)

# Written Response
3.a.i. The overall purpose of the program is to stimulate a "tic tac toe" game play experience between two players and to detect a winner (three in a row).

3.a.ii. The video demonstrates simulated gameplay between two players. In the video, the user clicks on the cell of the gameboard they want to occupy with an X or an O, depending on the player. The users can keep clicking their chosen cells until a winner is decided or a tie is determined. Then the users can reset the board and play the game again. The video demonstrates the ability of the program to detect all win scenarios (horizontal, vertical, and diagonal) and a tie. 

3.a.iii. The user clicks on the cell of the gameboard and either an X or an O occupies the space. The click is the input and the displayed symbol is the output. If a player achieves three-in-a-row, the program additionally outputs a statement identifying the winner or stating a tie.

3.b.i. 

<img width="409" alt="Screen Shot 2022-02-28 at 12 31 45 AM" src="https://user-images.githubusercontent.com/89219435/155950413-980a6487-da50-46f0-8bfe-f7d4aa164216.png">

***
<img width="223" alt="Screen Shot 2022-02-28 at 12 32 56 AM" src="https://user-images.githubusercontent.com/89219435/155950529-1b867843-d905-42ff-9d54-5c5435ff8de4.png">


3.b.ii. 

<img width="408" alt="Screen Shot 2022-02-28 at 12 33 21 AM" src="https://user-images.githubusercontent.com/89219435/155950574-214bcf81-f7d5-4a08-be25-a43297a9ea79.png">


3.b.iii. The list is called ‘board’ and ‘winConditions’. In the second, the list ‘winConditions’ are stored in the list board, accessed as a function.

3.b.iv. The data contained in this list represents the "status" of each position on the tic-tac-toe game board. The array is initialized with the dimensions of 3x3, with each position representing the respective position on the game board. The "status" is denoted by an "X" (piece belongs to player X), or an "O" (piece belongs to player O). The ‘winConditions’ list stores all possible ways to win and when the conditions are met, an output statement is given. 

3.b.v. Without a list, the program would not be able to remember previous player inputs, which would make gameplay impossible. The list allows for the program to save and update the status of every position on the game board for every turn. Without the ‘winConditions’ list, the program had no way of knowing who won the game, producing no result. 

3.c.i.

<img width="649" alt="Screen Shot 2022-02-28 at 11 57 46 AM" src="https://user-images.githubusercontent.com/89219435/156050058-7f32ee48-938a-4003-abb9-2ecf88c01567.png">

3.c.ii.

<img width="615" alt="Screen Shot 2022-02-28 at 11 59 10 AM" src="https://user-images.githubusercontent.com/89219435/156050257-3f8c7beb-5161-4650-b2b3-3930d5af5880.png">

3.c.iii. After the game is finished playing, the announce function uses the determined winner with the cases and announces the winner or if it is a tie. 

3.c.iv. The function iterates through the cases and if the case is met, then the if statement will return the corresponding statement. The if statement calls the announce function in the program to work. 

3.d.i. 

First Call:
If player X or O wins, gets three in a row, then it is announced, a statement is produced that the specific player won. 

Second Call:
If the players tie, neither meets the win conditions, then the statement ‘Tie’ is announced. 

3 d.ii. 

Condition(s) tested by first call: 
The first call tests whether three positions in a row of any kind (horizontal, vertical, or diagonal) are occupied by "X" or “O” meaning they win. 

Condition(s) tested by second call: 
The second call tests whether no three positions in a row of any kind (horizontal, vertical, or diagonal) are occupied by "X" or “O” meaning they tie.

3.d.iii. 

Results of the first call: 
The statement “Player X Won” or “Player O Won” is displayed. 

Results of the second call: 
The statement “Tie” is displayed. 
