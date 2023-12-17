# Project 5: Make a Square - Java Multithreading

<!-- ![Project Demo](vr.mp4) -->

<video width="640" height="360" controls>
  <source src="./vr.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


## Overview

The goal of this project is to create a 4X4 square using 4 or 5 given pieces. The pieces can be rotated or flipped, and all pieces must be used to form a square.

## Input

The input consists of the following:

1. The number of pieces.
2. For each piece:
   - Number of rows and columns in the piece.
   - Shape of the piece represented by 0 or 1 characters.

Example input for piece A:
```plaintext
2 3
111
101
```

# Output


The program should output all solutions in a 4-row by 4-column square. Each piece should occupy its location in the solution. The solid portions of piece #1 should be replaced with '1' characters, piece #2 with '2' characters, and so on.

Example output:

```
1112
1412
3422
3442
```
