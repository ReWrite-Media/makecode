### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Scene2

## Step 1
# Lawnmower

Oh no! The Smart Lawnmower is not working correctly. It's damaging the sprinklers. Review the code and make changes so that the lawnmower will first check if a sprinkler is present before cutting the grass. 

The `cut_grass()` function makes the lawnmower cut the grass in the block underneath it. Changing this to `check_sprinkler_cut_grass()` will make the mower check if a sprinkler is present before proceeding to cut the grass.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

for i in range(8):
    move_lawnmower_forward()
    cut_grass()
    move_lawnmower_forward()
    cut_grass()
    move_lawnmower_forward()
    cut_grass()
    move_lawnmower_next_row()
```

---

## Step 2
# Pro Tip:

You can nest `for` loops together to make it even easier. The below code has the same result as the example above.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

for i in range(8):
    for i in range(3):
        move_lawnmower_forward()
        cut_grass()
    move_lawnmower_next_row()
```

---

## Step 3
# Activity:

Update the code to make sure the lawnmower checks for sprinklers before mowing a block.

```python
# code here

for i in range(8):
    for i in range(3):
        move_lawnmower_forward()
        cut_grass()
    move_lawnmower_next_row()
```

---

