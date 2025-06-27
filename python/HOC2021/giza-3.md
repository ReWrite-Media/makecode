### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Giza-3

## Step 1
# Great Pyramid at Giza (Solution)

Help the Architect finish the triangle, a design that will stand the test of time. Think how to
create a pyramid. There are 2 more levels needed: 3 blocks on the bottom, and 1 block on the top. Code the solution by using `agent.give()` to give your Agent a stack of `SANDSTONE`, `agent.move()` to position the agent, and `agent.place()` to place the blocks in a 3 layer pyramid shape.

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
# give the agent a stack of sandstone
# move the agent forward
# and place the sandstone blocks
# do that 5 times

agent.give("SANDSTONE", 64, 1)
agent.move("forward")
agent.place("back", 1)
agent.move("forward")
agent.place("back", 1)
agent.move("forward")
agent.place("back", 1)
agent.move("forward")
agent.place("back", 1)
agent.move("forward")
agent.place("back", 1)
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# give the agent a stack of sandstone
# move the agent forward
# and place the sandstone blocks
# do that 5 times

agent.give("SANDSTONE", 64, 1)
for i in range(5):
    agent.move("forward")
    agent.place("back", 1)
```

---

## Step 3
# Activity:

The below code is the correct solution to the activity. Run the code to see it in action.

**Note: Use the Reset Code button below to reset the coding box back to the solution**

```python
# code here

agent.give("SANDSTONE", 64, 1)

for i in range(3):
    agent.move("forward")
    agent.place("back", 1)

agent.move("up")
agent.turn("left")
agent.turn("left")
agent.move("forward")
agent.move("forward")

agent.move("forward")
agent.place("back", 1)
```

---

