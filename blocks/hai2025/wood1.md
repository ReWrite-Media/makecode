### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Train the agent

## Step 1
Train the agent on what wood is by ``||classifying||`` an Oak log as wood.

#### ~ tutorialhint 
Drag the ``||hai: oak log||`` block into the ``||haiInputs: classify as wood||`` block.
```ghost

hai.classifyWood(hai.ghostBlock())
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.grass()) 
hai.trainingStart()
```
```template
//

```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.93
```
