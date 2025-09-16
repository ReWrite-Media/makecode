### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Add to it's model

## Step 1
Classify the birch log as wood too.

#### ~ tutorialhint 
Now classify the birch log as wood by dragging the ``||hai: birch log||`` block into a new ``||hai: classify wood as||`` block.
```ghost
hai.logOak()
hai.logBirch()
```
```template
hai.classifyWood(hai.logOak())
hai.classifyWood(0)
```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts
```
