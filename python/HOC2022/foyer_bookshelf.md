### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Foyer Bookshelf

## Step 1
# Bookcase Staircase

There seems to be something at the top of the bookcase. See if you could create a way to get up there. Use `move_cursor()` to position the cursor and `place_block()` to place a block in your selected position. 

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor right 4 times
# while placing a block before
# each movement

place_block()
move_cursor("yellow")
place_block()
move_cursor("yellow")
place_block()
move_cursor("yellow")
place_block()
move_cursor("yellow")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor right 4 times
# while placing a block before
# each movement

for i in range(4):
    place_block()
    move_cursor("yellow")
```

---

## Step 3
# Activity:

Create a staircase that can get you to the top of the bookcase and see what is waiting up there for you.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

place_block()
move_cursor("yellow")
place_block()
move_cursor("yellow")
place_block()
move_cursor("yellow")
place_block()
move_cursor("yellow")
```

---

