### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Foyer Chess

## Step 1
# Chess Pieces

You've freed the king and queen! But the door still isn't opening. They must be in the wrong positions. Move them into the correct positions so you can finally escape this place! Use the `move_chess_piece()` function to move the king and queen into the correct positions.

The `move_chess_piece()` function takes two parameters. The first one is which chess piece you want to move, the second one is what direction it should move in.

Valid chess pieces are:
- `king` ![King](img/king_icon.png "King")
- `queen` ![Queen](img/queen_icon.png "Queen")

Valid directions are:
- `orange` (moves the chess piece forward) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the chess piece back) ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the chess piece left) ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the chess piece right) ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the queen forward 3 blocks
# move the king left 3 blocks

move_chess_piece("queen", "orange")
move_chess_piece("queen", "orange")
move_chess_piece("queen", "orange")

move_chess_piece("king", "blue")
move_chess_piece("king", "blue")
move_chess_piece("king", "blue")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the queen forward 3 blocks
# move the king left 3 blocks

for i in range(3):
    move_chess_piece("queen", "orange")

for i in range(3):
    move_chess_piece("king", "blue")
```

---

## Step 3
# Actvitiy:

Search the room to find where you should move each chess piece, and then write code to position them to the correct spots on the black and white checkered floor. Make sure the chess pieces don't bump into each other.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

move_chess_piece("king", "orange")
move_chess_piece("king", "orange")
move_chess_piece("king", "orange")
move_chess_piece("king", "blue")
move_chess_piece("queen", "yellow")
move_chess_piece("queen", "yellow")
move_chess_piece("queen", "orange")
```

---

