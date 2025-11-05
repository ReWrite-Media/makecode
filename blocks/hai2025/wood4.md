### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Wood Planks

## Step 1
Train the agent on how to create wood planks. Click the lightbulb for help or press play when ready to continue.

#### ~ tutorialhint 
Wood Plank Pattern
![Craft Wood Plank](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/plank.png "Craft Wood Plank")

```ghost
hai.craftWith(hai.logOak())
hai.craftWith(hai.logBirch())
hai.craftWith(hai.logAcacia())
hai.craftWith(hai.lava())
hai.craftWith(hai.soulSand())
hai.craftWith(hai.lava())
hai.craftWith(hai.soulSand())
hai.crafting(hai.pocketcraftingPattern(`
..
..`))
```

```template
hai.trainingStart(function () {
    hai.craftWith(hai.ghostBlock())
    hai.crafting(hai.pocketcraftingPattern(`
    ..
    ..`))
})

```

```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.115
```
