# tiny-fen - Minimal FEN Utilities for Chess Material

`tiny-fen` is a lightweight collection of utilities for working with
**FEN strings**, **ASCII board rendering**, and **PNG board generation**
for chess positions.  
It is designed to be simple, dependency-light, and easy to embed inside
larger chess-related projects.

This directory contains small standalone scripts that demonstrate how to:

- parse a FEN string
- convert FEN into an internal board matrix
- render the board in ASCII (text mode)
- render the board in PNG using Pillow
- experiment with positions from Lichess or other editors

---

## Features

### Parse FEN into an 8×8 matrix  
Supports digits, piece letters, and empty squares.

### ASCII board rendering  
Produces a clean text representation of the board.

### PNG board rendering  
Uses Pillow to draw squares and Unicode chess pieces.

### Works with any FEN  
Including positions copied directly from Lichess, e.g.:
- `8/pbpQ3p/2p3kP/5p2/2p2P2/2N3r1/PPP5/1K6 w - - 3 27`
