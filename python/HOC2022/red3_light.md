### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Red3 Light

## Step 1
# Light Power

You need to open the door by powering all of the lights! Each light you turn on will open the door just a little more. Use the `move_cursor()` function to position the cursor over a light, then use the `turn_light_on()` function to turn on all the lights to open the door! 

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor up) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor down)  ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor right and then turn 
# on the light. repeat this 3 times

move_cursor("yellow")
turn_light_on()
move_cursor("yellow")
turn_light_on()
move_cursor("yellow")
turn_light_on()
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the cursor right and then turn 
# on the light. repeat this 3 times

for i in range(3):
    move_cursor("yellow")
    turn_light_on()
```

---

## Step 3
# Activity:

Turn on all of the lights so the door fully opens and you can get through.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

move_cursor("yellow")
move_cursor("yellow")
turn_light_on()
move_cursor("yellow")
move_cursor("yellow")
turn_light_on()
```

---

