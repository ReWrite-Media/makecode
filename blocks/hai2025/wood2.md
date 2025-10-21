### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Add to it's model

## Step 1
``||haiInputs: Classify||`` the ``||hai: birch log||`` as wood too. Click the lightbulb for help or press play when ready to continue.

#### ~ tutorialhint 
Now classify the birch log as wood by dragging the ``||hai: birch log||`` block into a new ``||haiInputs: classify wood as||`` block.
```ghost
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.logBirch()) 
hai.classifyWood(hai.grass()) 
hai.craftWith(hai.lava())
hai.craftWith(hai.soulSand())
```
```template
hai.trainingStart(function () {
    hai.classifyWood(hai.logOak())
    hai.classifyWood(hai.ghostBlock())
})

```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.105
```
