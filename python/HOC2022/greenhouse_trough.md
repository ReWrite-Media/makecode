### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Greenhouse Trough

## Step 1
# Trough

Oh no! Holes in the canal stop the water from flowing into the garden! Fill those holes to help the water along! Use the `move_cursor()` function to position the cursor over a hole, and then `place_block()` to fill it in.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor forward) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor back)  ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor and place a block twice
# then move right 2 blocks.

move_cursor("orange")
place_block()
move_cursor("orange")
place_block()
move_cursor("yellow")
move_cursor("yellow")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor and place a block twice
# then move right 2 blocks.

for i in range(2):
    move_cursor("orange")
    place_block()

move_cursor("yellow")
move_cursor("yellow")
```

---

## Step 3
# Activity:

Fill in all six holes in the canal to get the water flowing to the garden! 

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

move_cursor("orange")
place_block()
move_cursor("orange")
place_block()
move_cursor("yellow")
move_cursor("yellow")
move_cursor("orange")
place_block()
```

---

