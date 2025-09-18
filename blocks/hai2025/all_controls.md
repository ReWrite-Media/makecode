### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Tools

## Step 1
Train the agent on how to make an axe, pickaxe, and sword.

#### ~ tutorialhint 
Rember to use wood and sticks.

Axe Pattern
![Craft Axe](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/axe_crafting.png "Craft Axe")
Pickaxe Pattern
![Craft Pickaxe](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/pickaxe_crafting.png "Craft Pickaxe")
Sword Pattern
![Craft Sword](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/sword_crafting.png "Craft Sword")

```ghost
hai.craftWith()
hai.craftWith(hai.wood())
hai.craftWith(hai.stick())
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
hai.classifyWood(hai.grass()))
hai.upgradeTool(hai.pickaxe(),hai.wood())
hai.upgradeTool(hai.axe(),hai.cobblestone())
hai.upgradeTool(hai.shovel(),hai.cobblestone())
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
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.73
```
