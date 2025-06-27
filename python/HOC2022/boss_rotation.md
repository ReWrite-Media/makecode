### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Boss Rotation

## Step 1
# Activate the Trap

Now's your chance to capture the Time Agents! Head to the center of the boss arena and look down! You'll need to align all 3 rings with the center colors of the trap to activate it! Use the `rotate_ring()` function to rotate each ring either clockwise or counterclockwise to align all the colors!

The `rotate_ring()` function takes two parameters. The first one defines which ring you want to rotate and the second one defines which direction it should rotate in.

Valid rings are:
- `outer` ![Outer Ring](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/outer_ring.png "Outer Ring")
- `middle` ![Middle Ring](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/middle_ring.png "Middle Ring")
- `inner` ![Inner Ring](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/inner_ring.png "Inner Ring")

Valid directions are:
- `clockwise` ![Clockwise Rotation](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/clockwise_ring.png "Outer Ring")
- `counterclockwise` ![Counterclockwise Rotation](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/counterclockwise_ring.png "Counterclockwise Rotation")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# rotate the outer ring 3 times clockwise
# and then rotate the middle ring 1 time
# counterclockwise

rotate_ring("outer", "clockwise")
rotate_ring("outer", "clockwise")
rotate_ring("outer", "clockwise")
rotate_ring("inner", "counterclockwise")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# rotate the outer ring 3 times clockwise
# and then rotate the middle ring 1 time
# counterclockwise

for i in range(3):
    rotate_ring("outer", "clockwise")

rotate_ring("inner", "counterclockwise")
```

---

## Step 3
# Activity:

Rotate the rings! Align all three rings with the center colors of the trap to activate it!

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

rotate_ring("outer", "clockwise")
rotate_ring("middle", "counterclockwise")
rotate_ring("middle", "counterclockwise")
rotate_ring("middle", "counterclockwise")
```

---

