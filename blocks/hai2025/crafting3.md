### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Tools

## Step 1
Train the agent on how to make an axe, pickaxe, and shovel. Click the lightbulb for help or press play when ready to continue.

#### ~ tutorialhint 
Axe Pattern
![Craft Axe](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/axe_crafting.png "Craft Axe")
Pickaxe Pattern
![Craft Pickaxe](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/pickaxe_crafting.png "Craft Pickaxe")
Shovel Pattern
![Craft Shovel](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/sword_crafting.png "Craft Shovel")

```ghost
hai.craftWith(hai.wood())
hai.craftWith(hai.stick())
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
    hai.craftWith(hai.ghostBlock())
    hai.crafting(hai.craftingPattern(`
    ...
    .#.
    .#.`))
    hai.crafting(hai.craftingPattern(`
    ...
    ...
    ...`))
    hai.crafting(hai.craftingPattern(`
    .#.
    .#.
    .#.`))
})
```




```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.112
```
