### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Great Wall

## Step 1
# The Great Wall of China

The pandas keep eating the bamboo scaffolding, stopping the Engineer from completing the wall. Lead the pandas away from the wall. Use `agent.give()` to give your Agent a stack of `BAMBOO`, then use `agent.move()` to position your Agent, and `agent.place()` to place the `BAMBOO`

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
        - down
- slot number (*integer*): Which inventory slot the Agent should use.

```python
# give the agent a stack of bamboo
# place the bamboo under the agent
# and then move the agent forward
# do this 2 times

agent.give("BAMBOO", 64, 1)
agent.place("down", 1)
agent.move("forward")
agent.place("down", 1)
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# give the agent a stack of bamboo
# place the bamboo under the agent
# and then move the agent forward
# do this 2 times

agent.give("BAMBOO", 64, 1)
for i in range(2):
    agent.place("down", 1)
    agent.move("forward")
```

---

## Step 3
# Activity

Place a row of 5 `BAMBOO` to lure the pandas away from the wall so the Engineer can finish working.

**Note: You can reset the activity by using your T.A.L.K. device or by using the Reset Activity button.**



---

