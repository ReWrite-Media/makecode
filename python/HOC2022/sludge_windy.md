### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Sludge Windy

## Step 1
# Windy Bridge

You need to get across the bridge, but the wind is too strong! You'll need to place blocks inside the holes where the wind is coming from to block it. Use `move_cursor()` to position the cursor and `place_block()` to place a block in the position you have selected.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor right by 1 block,
# place a block, and then move the cursor 
# right 4 more times.

move_cursor("yellow")
place_block()
move_cursor("yellow")
move_cursor("yellow")
move_cursor("yellow")
move_cursor("yellow")
```

---

## Step 2
# Activity:

Fill all the holes that have wind blowing from them so you can safely cross the bridge!

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

move_cursor("yellow")
place_block()
```

---

