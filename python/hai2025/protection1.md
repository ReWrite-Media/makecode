### @flyoutOnly true
### @hideIteration false
### @explicitHints true

```python-template
# connection variables
api_url = 'minecraft://agent.ai/'
api_endpoint = 'classify'
api_key = 'MC-KEY-821-597'
 
# training data
training_data = {
    'ore': 'coal_ore'
}
 
# API request
ai.make_api_request(
    api_url,
    api_key,
    api_endpoint,
    training_data
)
```

# Classifying Materials

## Step 1
Train the agent that iron_ore is also an ore.

```python
training_data = {
    'ore': 'coal_ore',
    'ore2': 'iron_ore'
}
```
#### ~ tutorialhint 
Modify the code to classify `iron_ore` as an `ore` to the training data.


```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.112
```
