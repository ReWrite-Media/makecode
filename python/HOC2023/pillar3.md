### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Pillar3

## Step 1
# Green Pillar

Use code to cross the void and reach the Green Pillar. You have access to two functions. `agent_move()` and `agent_place()`

The `agent_move()` function takes one parameter which is a string. It defines what direction the agent should move in.

Valid directions are: 
- `forward`
- `back`
- `up`
- `down`

The `agent_place()` function takes one parameter which is a string. It defines what direction the agent should move in.

Valid directions are: 
- `up`
- `down`

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

agent_move("forward")
agent_place("down")
agent_move("forward")
agent_place("down")
agent_move("forward")
agent_place("down")
```

---

## Step 2
# Pro Tip:

Use a `for` loop to do one or more actions multiple times.

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS
    
for i in range(3):
    agent_move("forward")
    agent_place("down")
```

---

## Step 3
# Activity:

Build a bridge to reach the top of the green pillar.

```python
# code here
    
for i in range(3):
    agent_move("forward")
    agent_place("down")
```

---

