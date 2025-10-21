### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Table

## Step 1
Train the agent on how to craft a crafting table. Click the lightbulb for help or press play when ready to continue. 

#### ~ tutorialhint 
Crafting Table Pattern
![Craft Crafting Table](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/bench_crafting.png "Craft Crafting Table")

```ghost
hai.craftWith(hai.wood())
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
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.107
```
