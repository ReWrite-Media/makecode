### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Torches

## Step 1
Train the agent on how to craft torches.

#### ~ tutorialhint 
Torches use coal and sticks.

Torch Pattern
![Torch](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/stick_crafting.png "Torch")

```ghost
hai.craftWith(hai.stick())
hai.craftWith(hai.coal())
hai.crafting(hai.pocketcraftingPattern(`
..
..`))
hai.crafting(hai.craftingPattern(`
...
...
...`))
```

```template
hai.craftWith(hai.ghostBlock())
hai.craftWith(hai.ghostBlock())
hai.crafting(hai.craftingPattern(`
...
...
...`))
```

```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.91
```
