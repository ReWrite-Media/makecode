### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Beets

## Step 1
# Protect the beets
Something keeps getting into the garden and taking beets. Have the Agent build an enclosure around the farm to keep the beets safe. Use `agent.give()` to give the Agent `iron_bars`, `agent.place()` to place the iron_bars, `agent.turn()` to turn the Agent and `agent.move()` to move the Agent around the garden.

The `agent.give()` function takes three parameters.  

- item (*string*): The inventory slot where the Agent receives the item.
- count (*integer*): How items the Agent will receive.
- slot (*integer*): What inventory slot the Agent receives the item in.

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
# this will move the Agent forward one block
# give the Agent iron_bars, and then place 
# the iron_bars below it.
agent.move("forward")
agent.give("iron_bars", 2, 1)
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
# and place iron_bars below it five times
for i in range(5):
    agent.move("forward")
    agent.give("iron_bars", 2, 1)
    agent.place("down", 1)
```

---

## Step 4
# Activity:
Place iron bars around the beet garden between the stone blocks. 

**Note: You can reset the activity by speaking with the NPC or by using the Reset World button.**



---

