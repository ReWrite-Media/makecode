### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Laserroom Laser3

## Step 1
# Laser Puzzle (Part 3)

Solid blocks stop the laser! Shift the row of red, yellow and green blocks to make the laser pass through the glass blocks and turn on the light on the other side. Use the `shift_row()` function to shift the rows either left or right to enable the laser to pass through the glass blocks.

The `shift_row()` function takes two parameters (strings). The first parameter defines which color row you want to shift, and the second parameter defines the direction the row should shift.

Valid colors are:
- `green` ![Green](img/green_right.png "Green")
- `yellow` ![Yellow](img/yellow_right.png "Yellow")
- `red` ![Red](img/red_right.png "Red")

Valid directions are:
- `right` ![Right](img/gray_right.png "Right")
- `left` ![Left](img/gray_left.png "Left")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# shift the green row right
# 3 times, the yellow row
# left 1 once and the red row
# right 3 times.

shift_row("green", "right")
shift_row("green", "right")
shift_row("green", "right")
shift_row("yellow", "left")
shift_row("red", "right")
shift_row("red", "right")
shift_row("red", "right")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# shift the green row right
# 3 times, the yellow row
# left 1 once and the red row
# right 3 times.

for i in range(3):
    shift_row("green", "right")
    
shift_row("yellow", "left")

for i in range(3):
    shift_row("red", "right")
```

---

## Step 3
# Activity:

Shift the green, yellow and red rows either left or right so the lasers pass through the glass blocks and turns on the lights.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

shift_row("green", "left")
shift_row("yellow", "right")
shift_row("red", "right")
shift_row("red", "right")
shift_row("red", "right")
```

---

