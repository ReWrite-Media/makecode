### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Scene3B

## Step 1
# Bird Trouble

Great news! We've successfully uncovered the hidden words. Now, we've noticed that there are two new functions in the code that might be useful. However, before we can use them, we need to input the exact location or coordinates of the dumpster. 

There is no need to change this code yet, instead exit the coding window and find the dumpster. 

## New Functions:

`fly_to_dumpster()` This function will cause the birds to bring whatever trash they collect over to a dumpster. Before we could use it we must upload the cordinates by scanning a dumpster.

`release_trash()` This function will make sure all trash is only dropped into the appropriate container instead of dropping it anywhere.

```python
while search_for_trash():
    if trash == True:
        pickup_trash()
        move_trash()
    continue_flight_loop()
```

---

