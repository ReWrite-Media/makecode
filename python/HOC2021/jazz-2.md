### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Jazz-2

## Step 1
# Big Band Jazz (Debug)

The Jazz Musician lost his trumpet and is using a kazoo instead. Use the `agent.move()` function to get through the maze and then use `agent.collect()` to pick the trumpet up.

The `agent.move()` function takes one parameter, direction.

Valid directions are: 
- forward
- back
- left
- right
- up
- down

The `agent.collect()` function doesn't take any parameters.

```python
# move the agent 3 blocks forward
# and try to collect the trumpet

agent.move("forward")
agent.move("forward")
agent.move("forward")
agent.collect()
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# move the agent 3 blocks forward
# and try to collect the trumpet

for i in range(3):
    agent.move("forward")
agent.collect()
```

---

## Step 3
# Activity:

The below code has incorrect values. Run the code to see what happens and then try to debug and fix the code to complete the activity.

**Note: Use the Reset Code button below to reset the coding box back to the debug code**

```python
# code here
for i in range(2):
    agent.move("forward")
    
agent.move("up")
agent.move("forward")
agent.move("forward")
agent.move("down")
agent.move("down")
agent.move("down")
agent.move("forward")
agent.move("up")
agent.move("up")
agent.move("forward")

agent.collect()
```

---

