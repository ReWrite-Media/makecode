### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Laboratory Pipes

## Step 1
# Pipes

You'll need to add a specific amount of blocks to each of the hoppers. Maybe there is something in the room that can tell you how many? Use the `drop_block()` function to drop the correct amount of colored block into the pipes.

The `drop_block()` function takes one paramaters (a string) that defines what color block should be dropped.

Valid colors are:
- `yellow` ![Yellow Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/yellow_arrow.png "Yellow Arrow")
- `blue` ![Blue Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/blue_arrow.png "Blue Arrow")
- `orange` ![Orange Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/orange_arrow.png "Orange Arrow")
- `magenta` ![Magenta Arrow](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/magenta_arrow.png "Magenta Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# drop 4 yellow blocks and
# 1 blue block

drop_block("yellow")
drop_block("yellow")
drop_block("yellow")
drop_block("yellow")
drop_block("blue")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# drop 4 yellow blocks and
# 1 blue block

for i in range(4):
    drop_block("yellow")

drop_block("blue")
```

---

## Step 3
# Activity:

Look around the area to figure out how many of each colored block should be dropped into the pipes and write code to match that amount.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

drop_block("yellow")
drop_block("blue")
drop_block("orange")
drop_block("magenta")
drop_block("magenta")
```

---

