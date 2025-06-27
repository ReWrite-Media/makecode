### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Rails

## Step 1
# Connect the towns
The Illagers feel like the Villagers don't like them because very few ever come to their fair. The reason few Villagers go is because it’s too difficult to get up the hill between the two towns. Use `agent.give()` to give the Agent a minecart `rail` and `agent.place()` to create a minecart railway between the two towns.

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
# this will give the Agent two rails
# then place one down and move forward
agent.give("rail", 2, 1)
agent.place("down", 1)
agent.move("forward")
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

```python
# move the Agent forward one block.
agent.move("forward")
# move the Agent backward one block.
agent.move("back")
# move the Agent left one block.
agent.move("left")
# move the Agent right one block.
agent.move("right")
```

---

## Step 3
# Pro Tip:
Use a `for` loop to do a group of actions multiple times.

```python
# this will make the agent place
# a rail under it and then move forward.
# this will repeat four times.
for i in range(4):
    agent.give("rail", 2, 1)
    agent.place("down", 1)
    agent.move("forward")
```

---

## Step 4
# Activity:
Create a railway inside the tunnel between the two wood and stone posts.

**Note: You can reset the activity by speaking with the NPC or by using the Reset World button.**



---

