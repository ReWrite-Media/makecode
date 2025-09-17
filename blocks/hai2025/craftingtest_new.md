### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Sticks

## Step 1
Train the agent on how to craft sticks

#### ~ tutorialhint 
Stick Pattern
![Craft Stick](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/stick_crafting.png "Craft Stick")

```ghost
hai.craftWith()
hai.craftWith(hai.wood())
hai.crafting(hai.craftingPattern(`
...
...
...`))
hai.crafting(hai.pocketcraftingPattern(`
..
..`))
```

```template
hai.craftWith(hai.ghostBlock())
hai.crafting(hai.craftingPattern(`
...
...
...`))
```




```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.66
```
