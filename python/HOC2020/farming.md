### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Farming

## Step 1
# Building a farm
The Villagers offered to teach the Illagers how to farm, but they need help to prepare the land. Use `agent.till()` to make the Agent till the first 2 rows of dirt.

The `agent.till()` function takes one parameter, direction.

Valid directions are: 
- forward
- back
- left
- right

The `agent.move()` function takes one parameter, direction.

Valid directions are: 
- forward
- back
- left
- right
- up
- down

```python
# move the agent forward and till
# the block behind it
agent.move("forward")
agent.till("back")
```

---

## Step 2
The `agent.turn()` function takes one parameter, turn_direction.

Valid directions are: 
- left
- right

```python
# this will turn the Agent right
agent.turn("right")
# this will turn the Agent left
agent.turn("left")
```

---

## Step 3
# Pro Tip:
Use a `for` loop to do a group of actions multiple times.

```python
# this will move the agent forward
# and till behind it nine times
for i in range(9):
    agent.move("forward")
    agent.till("back")
```

---

## Step 4
# Activity:
Till the first two rows of the farm.

**Note: You can reset the activity by speaking with the NPC or by using the Reset World button.**



---

