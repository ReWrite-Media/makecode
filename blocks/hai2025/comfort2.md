### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Shears

## Step 1
Train the agent on how to craft a bed. Click the lightbulb for help or press play when ready to continue.

#### ~ tutorialhint 
Bed Pattern
![Craft Bed](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/bed_crafting.png "Craft Bed")

```ghost
hai.craftWith(hai.wood())
hai.craftWith(hai.cobblestone())
hai.craftWith(hai.wool())
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
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.96
```
