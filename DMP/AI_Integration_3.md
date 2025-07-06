# AI Integration Constellation 3 – Poe and Shadcn
```
import { chess, board } from '../../chess'

def render_board(square):
    # Simple rendering of chess board
    board_str = [[] for _ in range(1, 8)]
    for row_id in range(8):
        row = ["" for _ in range(8)]
        board_str[row_id] = ["  " * 8]
    // place kings on chess board
    for col_id in range(8):
        row_letters = list(chess.choose(player for cell in range(8))
        for cell_id in range(8):
            board_str[row_id][cel_id] = chess.renter_key(choice, col_id)
    return board_str
