### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Red1 Maze

## Step 1
# Maze

Direct the Enderman Butler to the emerald blocks on the other side of the maze! The levers on the wall seem to have a color that matches a set of doorways in the maze. You should flip these levers to create a safe path to direct the Enderman Butler through to the emerald blocks! Then use the `move_enderman_direction()` function to help navigate them through the maze.

The `move_enderman_direction()` function takes one parameter that defines which direction it should move in.

Valid directions are:
- `forward`
- `back`
- `left`
- `right`

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the enderman 4 blocks forward
# and then 1 block right

move_enderman_direction("forward")
move_enderman_direction("forward")
move_enderman_direction("forward")
move_enderman_direction("forward")
move_enderman_direction("right")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the enderman 4 blocks forward
# and then 1 block right

for i in range(4):
    move_enderman_direction("forward")

move_enderman_direction("right")
```

---

## Step 3
# Activity:

The levers on the wall seem to have a color that matches a set of doorways in the maze. You should flip these levers to create a safe path to direct the Enderman Butler to the emerald blocks!

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

move_enderman_direction("forward")
move_enderman_direction("forward")
move_enderman_direction("forward")
move_enderman_direction("right")
move_enderman_direction("right")
```

---

