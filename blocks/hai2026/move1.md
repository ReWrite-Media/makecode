### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Code Yard Maze 1

## Code Yard Maze 1 @unplugged

Your Agent is stuck in a maze! It starts on the green emerald block and needs to reach the gold block. The floor is a checkerboard of light and dark wood. Each square is one block. Use the squares to count your moves.

![The Agent maze from above](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2026/img/maze1.png "The Agent maze from above")

## First step

Press the green **Start** button to run your code. Stuck? Click the **lightbulb** for a hint. Made a mistake? Click the **back arrow** to undo.

Drag an ``||agent: agent move forward by 1||`` block into the ``||player: on chat command "run"||`` block. Then type **run** in chat and watch the Agent move one square!

#### ~ tutorialhint
Drag the ``||agent: agent move forward by 1||`` block into the ``||player: on chat command "run"||`` block.
```ghost
agent.move(SixDirection.Forward, 1)
agent.move(SixDirection.Left, 1)
agent.move(SixDirection.Right, 1)
```
```template
player.onChat("run", function () {
})
```

## Go left

Now the Agent needs to go **left**. Add another ``||agent: agent move||`` block and use the dropdown to pick **left**. Count the floor squares to the left before the glass. Change the number to match.

#### ~ tutorialhint
Add a ``||agent: agent move||`` block. Change **forward** to **left**. Count the squares to the left until the glass wall.

## Forward, then right

Add a ``||agent: agent move forward||`` block. Count the squares in front of the Agent until the glass. Then add a ``||agent: agent move||`` block, pick **right**, and count the squares to the right. Stop before the glass!

#### ~ tutorialhint
Two new blocks: one **forward** and one **right**. Count the open squares for each one.

## Forward, then left

Almost there! Add a ``||agent: agent move forward||`` block and count the squares until the Agent lines up with the gold block. Then add a ``||agent: agent move||`` block, pick **left**, and count the squares to the gold block.

#### ~ tutorialhint
Two more blocks: one **forward** and one **left**. The last move should land the Agent right on the gold block.

## Run it!

Type **run** in chat and watch the Agent go! Did it reach the gold block? If it got stuck, check your numbers and try again. You can do it!

#### ~ tutorialhint
Type **run** in chat. If the Agent bumps a wall, check the number on that move block.
