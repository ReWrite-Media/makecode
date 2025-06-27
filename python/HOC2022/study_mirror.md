### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Study Mirror

## Step 1
# Wrong Reflection

Things in the mirror appear differently than in the room you're in. Find all the differences and modify the room to make them match. Use `move_cursor()` to position the cursor and `place_block()` to place a block in the position you have selected.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# create a line of blocks

place_block()
move_cursor("blue")
place_block()
move_cursor("blue")
place_block()
move_cursor("blue")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# create a line of blocks

for i in range(3):
    place_block()
    move_cursor("blue")
```

---

## Step 3
# Activity:

Look into the mirror and pay attention to the design of blocks above the fireplace. Recreate the same design above the fireplace on your side of the mirror.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here


move_cursor("blue")
place_block()
move_cursor("blue")
place_block()
move_cursor("blue")
place_block()
move_cursor("blue")
```

---

