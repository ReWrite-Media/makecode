### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crafting Torches

## Step 1
Train the agent on how to craft torches. Click the lightbulb for help or press play when ready to continue.

#### ~ tutorialhint 
Torch Pattern
![Torch](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/torch_crafting.png "Torch")

```ghost
hai.craftWith(hai.stick())
hai.craftWith(hai.coal())
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
    ...
    ...`))
})
```

```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.112
```
