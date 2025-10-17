### @flyoutOnly true
### @hideIteration false
### @explicitHints true
### @hideDone true

# Classifying Materials

## Step 1
Before we're able to train the agent's AI, we'll need to learn how to access its Application Programming Interface (API). The first step is to define the API's endpoint (what part of the API you're accessing) and authentication parameters.

```python
api_url = 'minecraft://agent.ai/'
api_endpoint = 'classify'
api_key = "dsf3sSFssf42"
```
#### ~ tutorialhint 
Copy over the authentication parameters.


## Step 2
Now we need to define the data we want to send.

```python
training_data = {
    'wood': 'oak_log'
}
```
#### ~ tutorialhint 
Copy over the data we need to send.

## Step 3
Now we need to call the function when the code is run.

```python
ai.make_api_request(
    api_url,
    api_key,
    api_endpoint,
    training_data
)
```
#### ~ tutorialhint 
Copy over the function we need to call.

## Step 4
When we put it all together it looks like this.

     
```python
api_url = 'minecraft://agent.ai/'
api_endpoint = 'classify'
api_key = "dsf3sSFssf42"

training_data = {
    'wood': 'oak_planks'
}

ai.make_api_request(
    api_url,
    api_key,
    api_endpoint,
    training_data
)

```  
#### ~ tutorialhint 
Make sure your code matches the provided code.

```package
hai2025-ts=github:ReWrite-Media/hai2025-ts#v0.0.102
```
