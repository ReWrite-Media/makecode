### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Scene3

## Step 1
# Bird Trouble

We've decoded the message, and it seems like the birds are being told to move trash, but there's no place to put it. So, let's change the instructions in the code. Instead of moving the trash, we'll make the birds fly the trash to a dumpster and release the trash there. 

Replace the `move_trash()` function with the `fly_to_dumpster()` function, followed by the `release_trash()` function.

## New Functions:

`fly_to_dumpster()` This function will make the birds fly to the dumpster you loaded the coordinates for.

`release_trash()` This function will make sure all trash is only dropped into the appropriate container instead of dropping it anywhere.

```python
# code here

while search_for_trash():
    if trash == True:
        pickup_trash()
        move_trash()
    continue_flight_loop()
```

---

