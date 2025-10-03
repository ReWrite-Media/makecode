### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Classifying Materials

## Step 1
Before we're able to train the agent's AI, we'll need to learn how to access its Application Programming Interface (API). The first step is to define the API's endpoint (what part of the API you're accessing) and authentication parameters

```python
api_url = 'minecraft://agent.ai/'
api_endpoint = 'classify'
api_key = "dsf3sSFssf42"
```

## Step 2
Now that we've defined the API's endpoint we want to use, we'll want to write a function that takes an input and sends it to the API endpoint.

```python
def make_classify_api_request(resource, data):
    client = MinecraftAI(
        url = api_url,
        endpoint= api_endpoint,
        key = api_key
    )

    try:
        response = client.chat.completions.create(
            messages=[
                {resource : data}
            ]
        )
        ai_message = response.content
        print("AI Response")
        print(ai_message)
    
    except Exception as e:
        print("An error occurred: {e}")

```

## Step 3
Now we need to call the function when the code is run.

```python
make_classify_api_request("oak log","wood")
```

## Step 4
When we put it all together it looks like this

```python
api_url = 'minecraft://agent.ai/'
api_endpoint = 'classify'
api_key = "dsf3sSFssf42"

def make_classify_api_request(resource, data):
    client = MinecraftAI(
        url = api_url,
        endpoint= api_endpoint,
        key = api_key
    )

    try:
        response = client.chat.completions.create(
            messages=[
                {resource : data}
            ]
        )
        ai_message = response.content
        print("AI Response")
        print(ai_message)
    
    except Exception as e:
        print("An error occurred: {e}")

make_classify_api_request("oak log","wood") 
```       
