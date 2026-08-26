### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Agent Maze

## Step 1
See if you can get the Agent to the **gold block** by using the ``||agent.agent move()||`` block to navigate through the maze. The glass walls are in the way, so you will have to zig-zag! Each floor square is one move. Count the squares to pick your numbers.

#### ~ tutorialhint
Start by moving the Agent ``||agent.forward 1||``, then ``||agent.left 2||``. Look at the maze and keep going: forward, right, forward, then left to the gold block. Count the squares for each move.

```ghost
    agent.move()
```
```template
    agent.move(FORWARD, 1)
    agent.move(LEFT, 1)
    agent.move(FORWARD, 1)
    agent.move(RIGHT, 1)
```
