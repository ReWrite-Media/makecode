### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Ravager

## Step 1
# Introduce the ravager
Unlike the Illagers, the Villagers are afraid of ravagers. Help the Villagers get over their bias by meeting a ravager. Use the Agent to lead the ravager to each Villager using `agent.move()`.

The `agent.move()` function takes one parameter, direction.

Valid directions are: 
- forward
- back
- left
- right
- up
- down

The `agent.turn()` function takes one parameter, turn_direction.

Valid directions are: 
- left
- right

```python
# move the Agent forward three blocks
# and then come back to its starting location.
agent.move("forward")
agent.move("forward")
agent.move("forward")
agent.turn("left")
agent.move("forward")
agent.turn("left")
agent.move("forward")
agent.move("forward")
agent.move("forward")
agent.turn("left")
agent.move("forward")
agent.turn("left")
```

---

## Step 2
# Pro Tip:
Use a `for` loop to easily run `agent.move()` multiple times.

```python
# This code will move the Agent forward five times
for i in range(5):
    agent.move("forward")
```

---

## Step 3
# Activity:
Introduce the ravager to the Villagers by programming the Agent to walk up to each Villager with an arrow above its head.

**Note: You can reset the activity by speaking with the NPC or by using the Reset World button.**



---

