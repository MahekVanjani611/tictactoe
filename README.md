# TicTacToe: An interactive gaming interface developed on PYNQ-Z2 Board

## Introduction
  This project is essesntially the classic game of Tic-Tac-Toe realised on the PYNQ-Z2 FPGA board. As an outcome,2 players can play this game as is the case classically,but here the noughts and crosses are replaced by two players- RED and GREEN respectively. 

## Implementation
   Since a classic game of Tic Tac Toe involves player's input on a 3x3 grid in the form of Noughts or Crosses, we established a similar grid using RGB LEDs which were connected to the PModA and PModB of the board. Due to peripheral connectivity constraints,the first cell was accomodated on one of the RGB LED of the board itself,rest 8 on physical LEDs on a breadboard. An additional RPI addon module was used to take inputs of the positions of a player in form of Binary numbers. Player1 and Player2 can input their desired position to place their mark onto the grid via this. One of the available buttons on the board was assigned RESET which can be used to reset the game either mid-way or when a game is completed. The other RGB LED on the board is used to declare the winner-which glows RED if Player1 wins,and glows green if Player2 is the winner. In case of a tie,this LED doesn't glow. 

## How to play
### Apparatus required: 
1. PYNQ-Z2 Board
2. Breadboard
3. RGB LEDs
4. Male-male jumper wires
5. RPI Addon module
6. Vivado Design suite

