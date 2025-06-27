### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Greenhouse Crackedwall

## Step 1
# Cracked Wall

You need more water and it looks like those cracked blocks are leaking! Use the `move_cursor()` function to position the cursor over a cracked block, and then `break_block()` to break it and to let the water flow into the canal! 

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor down and break the block
# and then move 4 blocks to the right

move_cursor("magenta")
break_block()
move_cursor("yellow")
move_cursor("yellow")
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

# move the cursor down and break the block
# and then move 4 blocks to the right

move_cursor("magenta")
break_block()

for i in range(4):
    move_cursor("yellow")
```

---

## Step 3
# Activity:

Break all the cracked blocks leaking water to fill the canal! 

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

move_cursor("magenta")
break_block()
move_cursor("yellow")
move_cursor("yellow")
break_block()
```

---

