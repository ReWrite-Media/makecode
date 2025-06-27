### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Mona Lisa

## Step 1
# The Mona Lisa

The Mona Lisa has a frown, not her famous smile. This is because her garden has been destroyed. Use the `agent.give()` function to give your Agent a stack of `WHITE GLAZED TERRACOTTA`, then use `agent.move()` to position your Agent, and `agent.place` to place the `WHITE GLAZED TERRACOTTA`.

The `agent.give()` function takes three parameters.  

- item (*string*): The item you want to give the Agent.
- count (*integer*): How many items the Agent will receive.
- slot (*integer*): The inventory slot where the Agent receives the item.

The `agent.move()` function takes one parameter, direction.

Valid directions are: 
- forward
- back
- left
- right
- up
- down

The `agent.place()` function takes two parameters.  

- direction (*string*): The direction you want the Agent to place the item.
    - Valid directions are: 
        - forward
        - back
        - left
        - right
        - up
        - down,
- slot number (*integer*): Which inventory slot the Agent should use.

```python
# give the agent a stack of white glazed terracotta
# then move forward and place a block below the agent
# do this 5 times

agent.give("WHITE GLAZED TERRACOTTA", 64, 1)
agent.move("forward")
agent.place("down", 1)
agent.move("forward")
agent.place("down", 1)
agent.move("forward")
agent.place("down", 1)
agent.move("forward")
agent.place("down", 1)
agent.move("forward")
agent.place("down", 1)
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# give the agent a stack of white glazed terracotta
# then move forward and place a block below the agent
# do this 5 times

agent.give("WHITE GLAZED TERRACOTTA", 64, 1)
for i in range(5):
    agent.move("forward")
    agent.place("down", 1)
```

---

## Step 3
# Activity

Complete the square outline of `WHITE GLAZED TERRACOTTA` by moving the Agent and placing a block below it.

**Note: You can reset the activity by using your T.A.L.K. device or by using the Reset Activity button.**



---

