### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Elements Discovery

## Step 1
# Elements of Discovery

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

for i in range (2):
    agent.move("up")
for i in range (2):
    agent.move("forward")
agent.destroy("left")
```

---

## Step 3
# Activity

Move the Agent to bookcase that's glowing green and then destroy it.

**Note: You can reset the activity by using your T.A.L.K. device or by using the Reset Activity button.**



---

