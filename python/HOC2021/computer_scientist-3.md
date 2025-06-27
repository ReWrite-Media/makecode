### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Computer Scientist-3

## Step 1
# First Computer Scientist (Solution)

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

The below code is the correct solution to the activity. Run the code to see it in action.

**Note: Use the Reset Code button below to reset the coding box back to the solution**

```python
# code here

agent.move("forward")
agent.destroy("down")
agent.move("forward")
agent.move("forward")
agent.destroy("down")
agent.move("forward")
agent.move("forward")
agent.destroy("down")
agent.turn("right")
agent.move("forward")
agent.move("forward")
agent.turn("right")
agent.destroy("down")
agent.move("forward")
agent.move("forward")
agent.destroy("down")
agent.move("forward")
agent.move("forward")
agent.destroy("down")
```

---

