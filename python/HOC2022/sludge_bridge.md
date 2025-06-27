### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Sludge Bridge

## Step 1
# Bridge Builder

The Crate Minion is stuck! Oh no! Your're both stuck! You should build a bridge for the Crate Minion to get to the other side so they can press that button to reveal a staircase to help you out! Use the `move_cursor()` function to position the cursor and the `place_block()` function to place a block in the position you have selected.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# place a block and move
# the cursor 3 times

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

# place a block and move
# the cursor 3 times

for i in range(3):
    place_block()
    move_cursor("yellow")
```

---

## Step 3
# Activity:

Create a bridge so the Crate Minion can reach the button to reveal a staircase for you!

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

place_block()
move_cursor("yellow")
place_block()
move_cursor("yellow")
place_block()
```

---

