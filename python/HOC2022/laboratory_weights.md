### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Laboratory Weights

## Step 1
# Weights

You need the scale to reach a weight of exactly 23lbs. Maybe there is a sign around here to tell me how much each mob weighs? Use the `summon_animal()` function to summon a combination of animals that add up to 23lbs. 

The `summon_animal()` function takes on parameter that defines which animal should be summoned.

Valid animals are:
- `chicken` ![Chicken](img/chicken_weight.png "Chicken")
- `sheep` ![Sheep](img/sheep_weight.png "Sheep")
- `cow` ![Cow](img/cow_weight.png "Cow")

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# summon 5 chickens and
# two cows

summon_animal("chicken")
summon_animal("chicken")
summon_animal("chicken")
summon_animal("chicken")
summon_animal("chicken")
summon_animal("cow")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# summon 5 chickens and
# two cows

for i in range(5):
    summon_animal("chicken")

summon_animal("cow")
```

---

## Step 3
# Activity:

Search the area for information on how much each animals weighs, and then write code to summon enough animals to weigh exactly 23lbs.

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

summon_animal("chicken")
summon_animal("chicken")
summon_animal("sheep")
summon_animal("cow")
```

---

