### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Classify Iron

## Step 1
Train the agent that iron is also an ore.

#### ~ tutorialhint 
Drag the ``||hai: iron ore||`` block into the ``||haiInputs: classify as ore||`` block. Make sure not to remove the coal are.

```ghost
hai.classifyOre(hai.wood())
hai.classifyOre(hai.grass())
hai.classifyOre(hai.coalOre())
hai.classifyOre(hai.ironOre())
```
```template
hai.classifyOre(hai.coalOre())
hai.classifyOre(hai.ghostBlock())
```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.91
```
