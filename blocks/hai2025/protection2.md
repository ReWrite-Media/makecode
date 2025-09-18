### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Furnaces

## Step 1
Train the agent on how to craft a furnace.

#### ~ tutorialhint 
Remember furnaces are made from cobblestone

Furnace Pattern
![Craft Furnace](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/furnace_crafting.png "Craft Furnace")

```ghost
hai.craftWith(hai.wood())
hai.craftWith(hai.cobblestone())
hai.craftWith(hai.grass())
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
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.91
```
