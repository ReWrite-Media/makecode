### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Sludge Break

## Step 1
# Block Breaker

You need to break the blocks blocking the door so you can get out! Use `move_cursor()` to position the cursor and `break_block()` to break the block in the position you've selected.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# break the selected block and
# then move the cursor right
# do this 4 times.

break_block()
move_cursor("yellow")
break_block()
move_cursor("yellow")
break_block()
move_cursor("yellow")
break_block()
move_cursor("yellow")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# break the selected block and
# then move the cursor right
# do this 4 times.

for i in range(4):
    break_block()
    move_cursor("yellow")
```

---

## Step 3
# Activity:

Use your cursor to break open a path through the wall to leave this room!

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

move_cursor("yellow")
move_cursor("yellow")
break_block()
```

---

