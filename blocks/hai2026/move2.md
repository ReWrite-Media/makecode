### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Code Yard Maze 2

## Step 1

Solve the maze by dragging the ``||agent: agent move||`` block into the ``||loops: on start||`` block, then press the green **Start** button. You'll need more than one ``||agent: agent move||`` block to reach the gold block!

#### ~ tutorialhint
Use the following sequence to complete the maze:

Forward 1 -> Left 2 -> Forward 2 -> Right 2 -> Forward 2 -> Right 1 -> Forward 1

```ghost
agent.move(SixDirection.Forward, 1)
```
```template
agent.move(SixDirection.Forward, 1)
agent.move(SixDirection.Left, 1)
agent.move(SixDirection.Right, 1)
```
