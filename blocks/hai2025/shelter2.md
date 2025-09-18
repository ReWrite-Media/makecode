### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Add to it's model

## Step 1
Train the agent on how to craft a door.

#### ~ tutorialhint 
Doors should be made out of wood.

Door Pattern
![Craft Door](https://raw.githubusercontent.com/ReWrite-Media/makecode/master/blocks/hai2025/img/door_crafting.png "Craft Door")

```ghost
hai.craftWith()
hai.craftWith(hai.wood())
hai.craftWith(hai.cobblestone())
hai.craftWith(hai.grass())
hai.crafting(hai.craftingPattern(`
...
...
...`))
```

```template
hai.craftWith(hai.ghostBlock())
hai.crafting(hai.craftingPattern(`
...
...
...`))
```

```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.78
```
