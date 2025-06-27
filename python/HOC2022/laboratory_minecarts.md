### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Laboratory Minecarts

## Step 1
# Minecart Redirection

The mobs need to be sorted into the right passageways! Look at the mobs queued up to be sorted and sort them based on the order they are waiting. Use the `sort_mob()` function to set the order they should be sorted.

The `sort_mob()` function takes one parameter that defines which mob should be sorted next.

Valid mobs are:
- `zombie` ![Zombie](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/zombie_head.png "Zombie")
- `skeleton` ![Skeleton](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/skeleton_head.png "Skeleton")
- `creeper` ![Creeper](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/python/HOC2022/img/creeper_head.png "Creeper")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# sort the first 4 mobs all
# to the zombie passageway.

sort_mob("zombie")
sort_mob("zombie")
sort_mob("zombie")
sort_mob("zombie")
```

---

## Step 2
# Activity:

Pay attention to the order the mobs are in and write your code to sort each mob into the correct passageway.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
#code here

sort_mob("zombie")
sort_mob("zombie")
sort_mob("skeleton")
sort_mob("creeper")
sort_mob("creeper")
sort_mob("skeleton")
sort_mob("zombie")
```

---

