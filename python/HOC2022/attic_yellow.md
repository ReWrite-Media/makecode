### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Attic Yellow

## Step 1
# Attic Tutorial (Yellow Path)

You'll need to get the Agent more power to open the Yellow door! There are trapdoors above the Agent blocking moonlight from coming in. Maybe you can use that to charge the Agent? Use the `move_cursor()` function to position the cursor and then `open_trapdoor()` to open the selected trapdoor.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor forward) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor back)  ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# open the first trapdoor and
# then move the Agent 4 blocks forward

open_trapdoor()
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

# open the first trapdoor and
# then move the Agent 4 blocks forward

open_trapdoor()

for i in range(4):
    move_cursor("yellow")
```

---

## Step 3
# Activity:

We need to get the Agent more power! Those closed trapdoors on the ceiling let in a bit of moonlight. Maybe opening them using code will be enough to charge the Agent! 

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

open_trapdoor()
move_cursor("yellow")
move_cursor("yellow")
move_cursor("orange")
```

---

