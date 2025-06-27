### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Computer Scientist-2

## Step 1
# First Computer Scientist (Debug)

The computer scientist has created punch cards that contain the instructions for the first algorithm, but the punch card holes are blocked. Use `agent.move()` to move your agent to above the brown blocks and then use `agent.destroy()` to break the block below it.

The `agent.move()` function takes one parameter, direction.

Valid directions are: 
- forward
- back
- left
- right
- up
- down

The `agent.destroy()` function takes one parameter, direction.

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
# move the Agent and forward 2 blocks
# and break the blow below it.

agent.move("forward")
agent.destroy("down")
```

---

## Step 2
# Activity:

The below code has incorrect values. Run the code to see what happens and then try to debug and fix the code to complete the activity.

**Note: Use the Reset Code button below to reset the coding box back to the debug code**

```python
# code here

agent.move("forward")
agent.destroy("up")
agent.move("forward")
agent.move("forward")
agent.destroy("up")
agent.move("forward")
agent.move("forward")
agent.destroy("up")
agent.turn("left")
agent.move("forward")
agent.move("forward")
agent.turn("left")
agent.destroy("up")
agent.move("forward")
agent.move("forward")
agent.destroy("up")
agent.move("forward")
agent.move("forward")
agent.destroy("up")
```

---

