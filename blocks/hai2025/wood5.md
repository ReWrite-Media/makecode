### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Table

## Step 1
Train the agent on how to create wood planks.

#### ~ tutorialhint 
You could use any type of wood log to create planks.

Crafting Table Pattern
![Craft Wood Plank](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/plank.png "Craft Wood Plank")

```ghost
hai.craftWith(hai.logOak())
hai.craftWith(hai.logBirch())
hai.craftWith(hai.logAcacia())
hai.crafting(hai.pocketcraftingPattern(`
..
..`))
```

```template
hai.craftWith(hai.ghostBlock())
hai.crafting(hai.pocketcraftingPattern(`
..
..`))
```

```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.91
```
