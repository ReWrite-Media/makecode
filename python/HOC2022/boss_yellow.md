### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Boss Yellow

## Step 1
# Prepare the Cannons

There's a lever! Move the Agent to the lever and then pull it down! Use `agent.move()` to position the Agent in front of the lever and then `pull_lever_down()` to flip the lever on.

The `agent.move()` function takes one parameter that defines what direction it should move in.

Valid directions are: 
- `forward`
- `back`
- `left`
- `right`
- `up`
- `down`

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the agent 3 blocks forward
# and then pull the lever down

agent.move("forward")
agent.move("forward")
agent.move("forward")
pull_lever_down()
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

# move the agent 3 blocks forward
# and then pull the lever down

for i in range(3):
    agent.move("forward")

pull_lever_down()
```

---

## Step 3
# Activity:

There's a lever! Use that to power up the generator to activate this room's cannon! Position the Agent on the Gold block in front of the lever, then pull it down! 

The included code below is broken. Can you fix it? Run the code to see what happens, then debug it by editing it to the correct solution.

```python
# code here

agent.move("forward")
agent.move("forward")
agent.move("forward")
pull_lever_down()
```

---

