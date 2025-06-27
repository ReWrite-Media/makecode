### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Test

## Step 1
# Codebuilder Runtime Bug
Running the command `/codebuilder runtime stop @s` does not stop the execution of code from AZNB causing the code to continuously run. 

Run the below code and then in game issue the command `/codebuilder runtime stop @s`

```python
for i in range(50):
    agent.move("forward")
```

---

## Step 2




---

