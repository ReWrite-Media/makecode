### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Furnaces

## Step 1
Train the agent on how to craft a furnace. Click the lightbulb for help or press play when ready to continue.

#### ~ tutorialhint 
Furnace Pattern
![Craft Furnace](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/furnace_crafting.png "Craft Furnace")

```ghost
hai.craftWith(hai.wood())
hai.craftWith(hai.cobblestone())
hai.craftWith(hai.grass())
hai.craftWith(hai.lava())
hai.craftWith(hai.soulSand())
hai.crafting(hai.craftingPattern(`
...
...
...`))
```

```template
hai.trainingStart(function () {
    hai.craftWith(hai.ghostBlock())
    hai.crafting(hai.craftingPattern(`
    ...
    ...
    ...`))
})
```




```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.110
```
