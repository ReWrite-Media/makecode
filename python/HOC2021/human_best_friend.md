### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Human Best Friend

## Step 1
# Human's Best Friends

Dogs have been friends with people for thousands of years. But something has scared the dogs away. Code your Agent to leave a trail of `BEETROOT` items 5 blocks apart to help the people tame the wolves into dogs. Use the `agent.give()` function to give your Agent a stack of `BEETROOT`, then use `agent.move()` to position your Agent, and `agent.drop()` to drop a `BEETROOT`.

The `agent.give()` function takes three parameters.  

- item (*string*): The item you want to give the Agent.
- count (*integer*): How many items the Agent will receive.
- slot (*integer*): The inventory slot where the Agent receives the item.

The `agent.move()` function takes one parameter, direction (*string*).

Valid directions are: 
- forward
- back
- left
- right
- up
- down

The `agent.drop()` function takes three parameters.
- direction (*string*)
    - Valid directions are: 
        - forward
        - back
        - left
        - right
- quantity (*integer*): The number of items the Agent will drop.
- slot (*integer*): The inventory slot where the Agent drops the item from.

```python
# give the agent a stack of beetroot
# then drop one, and move forward 5

agent.give("BEETROOT", 64, 1)
agent.drop(1,1)
agent.move("forward")
agent.move("forward")
agent.move("forward")
agent.move("forward")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# give the agent a stack of beetroot
# then drop one, and move forward 5

agent.give("BEETROOT", 64, 1)
agent.drop(1,1)
for i in range(4):
    agent.move("forward")
```

---

## Step 3
# Activity

Drop a `BEETROOT` every 5 blocks leading the wolves to the campfire directly ahead of the Agent's starting position.

**Note: You can reset the activity by using your T.A.L.K. device or by using the Reset Activity button.**



---

