### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Add to it's model

## Step 1
The agent figured out that an Acacia log is wood too. Click the play button to continue.

#### ~ tutorialhint 
Make sure all three log types are being classified and press the play button.

```ghost
hai.classifyWood(hai.ghostBlock())
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.logBirch())
hai.classifyWood(hai.logAcacia())
hai.classifyWood(hai.grass()))
```
```template
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.logBirch())
hai.classifyWood(hai.logAcacia())
```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.78
```
