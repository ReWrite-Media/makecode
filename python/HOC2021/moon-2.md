### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Moon-2

## Step 1
# Mission Moon (Debug)

Send your agent to the space module to deliver the calculations. You cannot count the spaces that the Agent must move to complete the mission. Think about the moves required and use the Mathematician’s calculations to determine how many moves the agent must make. Use `agent.move()` to get your Agent to the lunar module and dock with it.

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
# move the agent forward 5
# then turn right
agent.move("forward")
agent.move("forward")
agent.move("forward")
agent.move("forward")
agent.move("forward")
agent.turn("right")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# move the agent forward 5
# then turn right
for i in range(5):
    agent.move("forward")
agent.turn("right")
```

---

## Step 3
# Activity:

The below code has incorrect values. Run the code to see what happens and then try to debug and fix the code to complete the activity.

**Note: Use the Reset Code button below to reset the coding box back to the debug code**

```python
# code here

for i in range(25):
    agent.move("forward")
agent.turn("right")

for i in range(17):
    agent.move("forward")
agent.turn("left")

for i in range(3):
    agent.move("up")
```

---

