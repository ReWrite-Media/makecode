### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Greenhouse Flowers

## Step 1
# Flower Planting

There's some pattern with these flowers. Figure out the pattern and plant the flowers on the empty dirt using `move_cusor()` to position the cursor and then `plant_flower()` to plant a flower.

The `move_cursor()` function takes one parameter that defines its direction. That parameter is the color of the arrow that represents the direction you want to move.

Valid directions are:
- `orange` (moves the cursor forward) ![Orange Arrow](img/orange_arrow.png "Orange Arrow")
- `magenta` (moves the cursor back)  ![Magenta Arrow](img/magenta_arrow.png "Magenta Arrow")
- `blue` (moves the cursor left)  ![Blue Arrow](img/blue_arrow.png "Blue Arrow")
- `yellow` (moves the cursor right)  ![Yellow Arrow](img/yellow_arrow.png "Yellow Arrow")

The `plant_flower()` function takes one parameter that defines what type of flower should be planted.

Valid flowers are:
- `blue` ![Blue Flower](img/blue_flower.png "Blue Flower") 
- `yellow` ![Yellow Flower](img/yellow_flower.png "Yellow Flower") 
- `red` ![Red Flower](img/red_flower.png "Red Flower")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move right and plant a blue flower 
# 5 times, then move back one and
# plant a red flower

plant_flower("blue")
move_cursor("yellow")
plant_flower("blue")
move_cursor("yellow")
plant_flower("blue")
move_cursor("yellow")
plant_flower("blue")
move_cursor("yellow")
plant_flower("blue")
move_cursor("yellow")
move_cursor("magenta")
plant_flower("red")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move right and plant a blue flower 
# 5 times, then move back one and
# plant a red flower

for i in range(5):
    plant_flower("blue")
    move_cursor("yellow")

move_cursor("magenta")
plant_flower("red")
```

---

## Step 3
# Activity:

The flower beds on the sides seem to have a pattern to them! This must be a clue to filling in the larger flower bed in the middle! 

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

plant_flower("blue")
move_cursor("yellow")
move_cursor("yellow")
move_cursor("yellow")
move_cursor("magenta")
plant_flower("yellow")
move_cursor("blue")
move_cursor("magenta")
plant_flower("red")
```

---

