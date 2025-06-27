### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Potion Vent

## Step 1
# Vent

Move the clay ball to the Gold block so it can open up the door to the next section. Use the `clay_ball_move()` function to navigate the ball through the wall.

The `clay_ball_move()` function takes one parameter that defines what direction it should move in.

Valid directions are: 
- `up`
- `down`
- `left`
- `right`

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the clay ball
# left one space and then
# forward three spaces

clay_ball_move("left")
clay_ball_move("right")
clay_ball_move("right")
clay_ball_move("right")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the clay ball
# left one space and then
# forward three spaces

clay_ball_move("left")

for i in range(3):
    clay_ball_move("forward")
```

---

## Step 3
# Activity:

Move the clay ball through the wall to reach the Gold block at the end.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

clay_ball_move("right")
clay_ball_move("right")
clay_ball_move("left")
clay_ball_move("left")
```

---

