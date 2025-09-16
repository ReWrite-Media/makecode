### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Train the agent

## Step 1
Train the agent on what wood is by ``||actions: classifying||`` an Oak log as wood.

#### ~ tutorialhint 
Drag the ``||value: oak log||`` block into the ``||actions: classify as wood||`` block.
```ghost
actions.classifyWood(values.logOak())
actions.classifyWood(values.cobblestone()) 
```
```template
actions.classifyWood()
```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.18
```
