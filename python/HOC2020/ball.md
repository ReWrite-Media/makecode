### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Ball

## Step 1
# Get the ball

It looks like the levers are stuck on the Villager's elevator. Use `agent.move()` to position the Agent and then use `agent.interact()` to flip all the levers so the Villager can bring down the children's ball.

The `agent.move()` function takes one parameter, direction.

Valid directions are: 
- forward
- back
- left
- right
- up
- down

The `agent.interact()` function takes one parameter, direction.

Valid directions are:
- forward
- back
- left
- right
- up
- down

```python
# move the agent up one block
# flip the lever in front of it
agent.move("up")
agent.interact("forward")
```

---

## Step 2
# Pro Tip:
Use a `for` loop to do a group of actions multiple times.

```python
# this code will move the agent right
# three times
for i in range(3):
    agent.move("right")
```

---

## Step 3
# Activity:
Move the Agent up to each lever and interact with it to flip it and turn on the elevator.

**Note: You can reset the activity by speaking with the NPC or by using the Reset World button.**



---

