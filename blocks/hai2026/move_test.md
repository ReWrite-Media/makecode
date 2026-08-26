### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Agent Maze

## Step 1
Hi! This is where you write code. Press the green **Start** button to run your code. Stuck? Click the **lightbulb** for a hint. Made a mistake? Click the **back arrow** to undo. Press **next** to begin!

#### ~ tutorialhint
Press the green button to run your code.
Click the lightbulb for a hint.
Click the back arrow to undo.

## Step 2
Your Agent starts on the **emerald block** ![Emerald Block](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2026/img/emerald_block.png "Emerald Block")

It needs to reach the **gold block** ![Gold Block](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2026/img/gold_block.png "Gold Block")

The **glass** walls ![Glass](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2026/img/white_stained_glass.png "Glass") block the way, so the Agent has to zig-zag! The floor is a checkerboard of light and dark wood. Each square is one block. Use the squares to count your moves.

#### ~ tutorialhint
Find the emerald block and the gold block in the maze. Each floor square is one move.

## Step 3
Let's take the first step. Drag an ``||agent: agent move forward by 1||`` block into the ``||player: on chat command "run"||`` block. Then type **run** in chat and watch the Agent move one square!

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

## Step 4
Now the Agent needs to go **left**. Add another ``||agent: agent move||`` block. Use the dropdown to pick **left**. Count the floor squares to the left before the glass. Change the number to match.

#### ~ tutorialhint
Add a ``||agent: agent move||`` block. Change **forward** to **left**. Count the squares to the left until the glass wall.

## Step 5
Time to go **forward** again! Add a new ``||agent: agent move||`` block. Count the squares in front of the Agent until the glass. That's your number!

#### ~ tutorialhint
Add a ``||agent: agent move forward||`` block. Count the open squares in front of the Agent.

## Step 6
Now go **right**. Add a ``||agent: agent move||`` block and pick **right**. Count the squares to the right. Stop before the glass!

#### ~ tutorialhint
Add a ``||agent: agent move||`` block and change it to **right**. Count the open squares to the right.

## Step 7
Almost there! Go **forward** until you are in the same row as the gold block. Add a ``||agent: agent move forward||`` block and count the squares.

#### ~ tutorialhint
Add a ``||agent: agent move forward||`` block. Count the squares until the Agent lines up with the gold block.

## Step 8
Last move! Go **left** to the gold block. Add a ``||agent: agent move||`` block, pick **left**, and count the squares.

#### ~ tutorialhint
Add a ``||agent: agent move||`` block and change it to **left**. Count the squares between the Agent and the gold block.

## Step 9
Type **run** in chat and watch the Agent go! Did it reach the gold block? If it got stuck, check your numbers and try again. You can do it!

#### ~ tutorialhint
Type **run** in chat. If the Agent bumps a wall, check the number on that move block.
