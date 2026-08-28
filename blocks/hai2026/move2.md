### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Code Yard Maze 2

## Code Yard Maze 2 @unplugged

A new maze! Your Agent starts on the green emerald block and needs to reach the gold block. This maze has more turns, so count carefully. The floor is a checkerboard pattern of light and dark wood. Each square is one block. Use the squares to count your moves.

![The Agent maze from above](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2026/img/maze2.png "The Agent maze from above")

## First step
Drag an ``||agent: agent move forward by 1||`` block into the ``||loops: on start||`` block. Then press the green **Start** button and watch the Agent move one square! If you're ever stuck, click the **lightbulb** for a hint or click the **back arrow** to go back a step.

#### ~ tutorialhint
Drag the ``||agent: agent move forward by 1||`` block into the ``||loops: on start||`` block.
```ghost
agent.move(SixDirection.Forward, 1)
agent.move(SixDirection.Left, 1)
agent.move(SixDirection.Right, 1)
```
```template
\
```

## Go left

Now the Agent needs to go **left**. Add another ``||agent: agent move||`` block and use the dropdown to pick **left**. Count the floor squares to the left before the glass. Change the number to match.

#### ~ tutorialhint
Add an ``||agent: agent move||`` block. Change **forward** to **left** and then change the count to the amount of squares left before the glass wall.

## Forward, then right

Add an ``||agent: agent move forward||`` block. Count the squares in front of the Agent until the glass. Then add an ``||agent: agent move||`` block, pick **right**, and count the squares to the right. Stop before the glass!

#### ~ tutorialhint
Two new blocks: one **forward** and one **right**. Count the open squares for each one.

## Forward again

Add an ``||agent: agent move forward||`` block. Count the squares in front of the Agent until the glass. The Agent should end up one row below the gold block.

#### ~ tutorialhint
One **forward** block. Count the open squares in front of the Agent.

## Right, then forward

Almost there! Add an ``||agent: agent move||`` block, pick **right**, and count the squares until the Agent is right under the gold block. Then add an ``||agent: agent move forward||`` block to step onto the gold block.

#### ~ tutorialhint
Two more blocks: one **right** and one **forward**. The last move should land the Agent right on the gold block.

## Run it!

Press the green **Start** button and watch the Agent go! Did it reach the gold block? If it got stuck, check your numbers and try again. Really stuck? Click the **lightbulb** to see the solution.

#### ~ tutorialhint
Forward 1 -> Left 2 -> Forward 2 -> Right 2 -> Forward 2 -> Right 1 -> Forward 1

![The maze with the solution path](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2026/img/maze2_solve.png "The maze with the solution path")
