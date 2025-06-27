### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Paleontology

## Step 1
# Paleontology Puzzle

Someone has removed bones from the dinosaur skeleton and replaced them with orange blocks. Code your Agent to DESTROY all 4 orange blocks and PLACE `BONE BLOCK` blocks. Use the `agent.give()` function to give your Agent a stack of `BONE BLOCK` and `agent.move()` to position your Agent above the orange block Then use `agent.destroy()` to break the orange block and `agent.place()` to replace it with a `BONE BLOCK`.

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

The `agent.destroy()` function takes one parameter, direction.

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
# give the agent a stack of bloneblocks
# then move forward two, break the below below
# and then place the bone block
# do that 2 times.

agent.give("BONE BLOCK", 64, 1)
agent.move("forward")
agent.move("forward")
agent.destroy("down")
agent.place("down", 1)
agent.move("forward")
agent.move("forward")
agent.destroy("down")
agent.place("down", 1)
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# give the agent a stack of bloneblocks
# then move forward two, break the below below
# and then place the bone block
# do that 2 times.

agent.give("BONE BLOCK", 64, 1)
for i in range(2):
    agent.move("forward")
    agent.move("forward")
    agent.destroy("down")
    agent.place("down", 1)
```

---

## Step 3
# Activity

Remove each orange block and replace them with a `BONE BLOCK`.

**Note: You can reset the activity by using your T.A.L.K. device or by using the Reset Activity button.**



---

