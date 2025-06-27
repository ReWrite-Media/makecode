### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Elements Discovery-3

## Step 1
# Elements of Discovery (Solution)

When the chemist left the room, someone hid her research inside the bookcase. Code your
Agent to break the green glowing bookcase, so that she can share her discoveries. Use the `agent.move()` function to move the Agent toward the green glowing bookcase, and then use `agent.destroy()` to break them.

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
# move the Agent up 2 blocks, forward 2 blocks
# and then break the block to the left

agent.move("up")
agent.move("up")
agent.move("forward")
agent.move("forward")
agent.destroy("left")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# move the Agent up 2 blocks, forward 2 blocks
# and then break the block to the left

agent.move("up")
for i in range (2):
    agent.move("forward")
```

---

## Step 3
# Activity:

The below code is the correct solution to the activity. Run the code to see it in action.

**Note: Use the Reset Code button below to reset the coding box back to the solution**

```python
# code here

agent.move("up")

for i in range (4):
    agent.move("forward")

agent.destroy("left")
```

---

