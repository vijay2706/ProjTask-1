# ProjTask-1
## Problem Statement
To implement a automated chess board, which moves peices physically even if the opponents are seperated by a distance and allows player to train against computers to monitor and improve their chess skills.
## To be implemented:
- Detection of movement of chess pieces
- Movement of chess peices
- Communication between chess boards
## Ideation:
**Pipeline**
Movement of piece on one board => Detection of Piece using Magnetic Reed switches => Wifi module => 2D CNC machine, which moves pieces.
### Detection of Movement of Chess Pieces
The movement is detected by using reed sensors that are triggered by the magnetic field from permanent magnets placed on the bottom of each piece.When square containing a piece will have its reed switch activated because of magnetic field due to magnet present on piece and the reed sensor at the square where the piece is taken is inactive. So by this way we can detect that which piece is moved.
### Movement of Pieces
An X-Y plotter or 2D CNC machine can be modified to our need in this project. Instead of marker or driller, we can use a Magnet which is lowered and raised accordingly(this is not to happen unnecessary moves due to magent).This total setup is to be kept below the board.
### Commmunication between the chess boards
Since we want use this project for large distances, Wifi module is used for this project which has access for high internet connection. Bluetooth module is used for smaller range of distance.

## Follow-Up
**Detection of movement of pieces**

1.Sensors used:
