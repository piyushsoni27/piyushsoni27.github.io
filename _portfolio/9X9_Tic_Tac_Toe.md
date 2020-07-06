---
title: "2. 9 X 9 Tic Tac Toe"
excerpt: "An interpolation of the classic 3X3 Tic Tac Toe with a larger 3X3 TicTacToe having smaller 3X3 TicTacToe in each of its 9 cells.<br/><img src='/images/9x9.png'>"
collection: portfolio
---

__Background__ - This computer vs human game is an interpolation of the classic 3X3 Tic Tac Toe with a larger 3X3 TicTacToe having smaller 3X3 TicTacToe in each of its 9 cells. An additional rule that a person can make a move only in the cell of the bigger TicTactoe which corresponds to the cell of the smaller TicTacToe where his opponent made his move (previous move).

__Solution__ - The computer uses a recursive approach to make an optimal move by predicting the next move of the user and trying out different combinations. The difficulty can be increased or decreased. In a higher difficulty the computer will predict up to 3 or larger sequence of moves of the second player. In easy mode, it would try to guess only the next move.
