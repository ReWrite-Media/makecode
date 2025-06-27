### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Boss Red

## Step 1
# Open Doors

Each hole represents a chamber door in the four corners of the boss arena! Fill all the holes with the correct color to open the chamber doors! Use `move_cursor()` function to position the cursor in a space, then use `place_block()` function to place a colored block to fill in each space!

The `place_block()` function takes one parameter that defines the color of the block you'd like to place.

Valid colors are:
- `magenta`
- `green`
- `yellow`
- `blue`

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# place a green block, move
# 2 spaces right and then place
# a blue block

place_block("green")
move_cursor("yellow")
move_cursor("yellow")
place_block("blue")
```

---

## Step 2
# Activity:

Place colored blocks into the correct spaces to open the chamber doors.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

place_block("green")
move_cursor("yellow")
move_cursor("yellow")
place_block("blue")
```

---

