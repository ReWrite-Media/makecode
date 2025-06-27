### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Lazerroom Lazer

## Step 1
# Laser Puzzle

Solid blocks stop the laser! Shift the row of green blocks to make the laser pass through the glass blocks to turn on the light on the other side. Use the `shift_row()` function to shift the rows either left or right to enable the laser to pass through the glass blocks.

The `shift_row()` function takes two parameters (strings). The first parameter defines which color row you want to shift, and the second parameter defines the direction the row should shift.

Valid colors are:
- `green` ![Green](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/green_right.png "Green")

Valid directions are:
- `right` ![Right](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/gray_right.png "Right")
- `left` ![Left](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/gray_left.png "Left")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# shift the green row right
# 3 times

shift_row("green", "right")
shift_row("green", "right")
shift_row("green", "right")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# shift the green row right
# 3 times

for i in range(3):
    shift_row("green", "right")
```

---

## Step 3
# Activity:

Shift the green row either left or right so the laser passes through the glass block and turns on the light.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

shift_row("green", "right")
shift_row("green", "right")
```

---

