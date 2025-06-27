### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Red3 Lazerbattery

## Step 1
# Laser Reveal

Fill in all the holes in the floor with the cursor to open the curtain. Use `move_cursor()` to position the cursor and `place_block()` to place a block in the position you have selected.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor forward) ![Orange Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor back)  ![Magenta Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# place a block then move forward
# by 4 blocks

place_block()
move_cursor("orange")
move_cursor("orange")
move_cursor("orange")
move_cursor("orange")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# place a block then move forward
# by 4 blocks

place_block()

for i in range(4):
    move_cursor("orange")
```

---

## Step 3
# Activity:

Fill in all the holes in the floor to open the curtain and reveal the final activity.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

place_block()
move_cursor("orange")
move_cursor("orange")
move_cursor("orange")
place_block()
move_cursor("yellow")
move_cursor("yellow")
move_cursor("yellow")
move_cursor("yellow")
move_cursor("yellow")
```

---

