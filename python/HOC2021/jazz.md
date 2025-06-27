### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Jazz

## Step 1
# Big Band Jazz

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
# Activity

Move the Agent through the maze and collect the trumpet.

**Note: You can reset the activity by using your T.A.L.K. device or by using the Reset Activity button.**



---

