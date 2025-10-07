### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Shears

## Step 1
Train the agent on how to craft shears. Click the lightbulb for help, and press play when ready to continue.

#### ~ tutorialhint 
Shears Pattern
![Craft Shears](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/shears_crafting.png "Craft Shears")

```ghost
hai.craftWith(hai.wood())
hai.craftWith(hai.cobblestone())
hai.craftWith(hai.coal())
hai.craftWith(hai.ironIngot())
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
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.95
```
