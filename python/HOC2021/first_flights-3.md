### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# First Flights-3

## Step 1
# First Flight (Solution)

One of the first planes is about to take off, but there are holes in the runway! Code
your Agent to fill the holes. Use the `agent.give()` function to give your Agent a stack of `DIRT` blocks and use the `agent.move()` function to position the Agent above the holes, and then use `agent.place()` to fill the holes.

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

The `agent.turn()` function takes one parameter, turn_direction.

Valid directions are: 
- left
- right

```python
# give the agent a stack of dirt blocks
# move forward 1 and place down
# do that 2 times

agent.give("DIRT", 64, 1)
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
# give the agent a stack of dirt blocks
# move forward 1 and place down
# do that 2 times

agent.give("DIRT", 64, 1)
for i in range(2):
    agent.move("forward")
    agent.place("down", 1)
```

---

## Step 3
# Activity:

The below code is the correct solution to the activity. Run the code to see it in action.

**Note: Use the Reset Code button below to reset the coding box back to the solution**

```python
# code here

agent.give("DIRT", 64, 1)
for i in range(2):
    agent.move("forward")
    agent.place("down", 1)

agent.move("forward")
agent.move("forward")
agent.move("right")
agent.move("right")

for i in range(2):
    agent.move("forward")
    agent.place("down", 1)

agent.move("forward")
agent.move("forward")
agent.move("right")
agent.move("right")

for i in range(2):
    agent.move("forward")
    agent.place("down", 1)
```

---

