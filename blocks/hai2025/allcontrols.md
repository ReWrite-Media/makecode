### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Tools

## Step 1
All available inputs and values LAST UPDATED: 2025-09-18 03:50PM ET

#### ~ tutorialhint 
Axe
![Craft Axe](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/axe_crafting.png "Craft Axe")
Pickaxe
![Craft Pickaxe](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/pickaxe_crafting.png "Craft Pickaxe")
Sword
![Craft Sword](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/sword_crafting.png "Craft Sword")
Crafting Table
![Craft Crafting Table](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/bench_crafting.png "Craft Crafting Table")
Stick or Torch
![Craft Stick](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/stick_crafting.png "Craft Stick")
Door
![Craft Door](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/door_crafting.png "Craft Door")


```ghost
hai.craftWith()
hai.craftWith(hai.wood())
hai.craftWith(hai.stick())
hai.classifyOre(hai.coal())
hai.classifyOre(hai.ironIngot())
hai.craftWith(hai.cobblestone())
hai.crafting(hai.craftingPattern(`
...
...
...`))
hai.crafting(hai.pocketcraftingPattern(`
..
..`))
hai.classifyWood(hai.ghostBlock())
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.logBirch())
hai.classifyWood(hai.logAcacia())
hai.classifyWood(hai.coalOre())
hai.classifyWood(hai.ironOre())
hai.classifyWood(hai.Wool())
hai.classifyWood(hai.grass()))
hai.upgradeTool(hai.pickaxe(),hai.wood())
hai.upgradeTool(hai.axe(),hai.cobblestone())
hai.upgradeTool(hai.shovel(),hai.cobblestone())
hai.buildingMaterials(hai.wood())
```

```template
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
```




```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.96
```
