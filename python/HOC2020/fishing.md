### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Fishing

## Step 1
# Build a dock
Before the Illagers can teach the Villagers how to fish, they need a dock. Build the outside edges of the dock using `agent.give()` to give the Agent a block to place, `agent.place()` to place the block, `agent.turn()` to turn the Agent and `agent.move()` to move the Agent.

The `agent.give()` function takes three parameters.  

- item (*string*): The item you want to give the Agent.
- count (*integer*): How many items the Agent will receive.
- slot (*integer*): The inventory slot where the Agent receives the item.

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
# this will give the Agent two planks
# move forward one space
# and place a plank below
agent.give("planks", 2, 1)
agent.move("forward")
agent.place("down", 1)
```

---

## Step 2
The `agent.move()` function takes one parameter, direction.

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
# move the Agent forward one block.
agent.move("forward")
# move the Agent backward one block.
agent.move("back")
# move the Agent left one block.
agent.move("left")
# move the Agent right one block.
agent.move("right")

# this will turn the Agent right
agent.turn("right")
# this will turn the Agent left
agent.turn("left")
```

---

## Step 3
# Pro Tip:
Use a `for` loop to do a group of actions multiple times.

```python
# this code will move the Agent forward
# and place a plank under them five times
for i in range(5):
    agent.move("forward")
    agent.give("planks", 2, 1)
    agent.place("down", 1)
```

---

## Step 4
# Activity:
Build the outside edges of the dock extending from the cobblestone which will be 6 blocks long and 4 blocks wide.

**Note: You can reset the activity by speaking with the NPC or by using the Reset World button.**



---

