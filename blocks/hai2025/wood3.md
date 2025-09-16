### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Add to it's model

## Step 1
The agent figured out that Acacia wood is a log as well. Click the play button to continue.

#### ~ tutorialhint 
Make sure all three log types are being classified and press the play button.

```ghost
actions.classifyWood(values.logOak())
actions.classifyWood(values.logBirch()) 
actions.classifyWood(values.logAcacia()) 
actions.classifyWood(values.grass()) 
```
```template
actions.classifyWood(values.logOak())
actions.classifyWood(values.logBirch())
actions.classifyWood(values.logAcacia())
```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.18
```
