### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Add to it's model

## Step 1
Classify the birch log as wood too.

#### ~ tutorialhint 
Now classify the birch log as wood by dragging the ``||values: birch log||`` block into a new ``||actions: classify wood as||`` block.
```ghost
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.logBirch()) 
hai.classifyWood(hai.grass()) 
```
```template
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.ghostBlock())
```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.34
```
