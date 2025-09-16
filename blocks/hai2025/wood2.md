### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Add to it's model

## Step 1
Classify the birch log as wood too.

#### ~ tutorialhint 
Drag the ``||hai: Birch Log||`` block into the ``||hai: classify as wood||`` block.
```ghost
hai._classifyWood(hai.logOak())
hai._classifyWood(hai.logBirch())
```
```template
hai._classifyWood(hai.logOak())
hai._classifyWood(0)
```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts
```
