### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Tutorial 2

## Step 1
# Plant the sapling
The Agent has given you a `sapling` to commemorate your arrival! To put the sapling in your hotbar, we'll use the `player.give()` function.

The `player.give()` function takes two parameters. 
- item (*string*): the item you want
- count (*integer*): the number of items you'll receive

```python
# give yourself 5 stone blocks
player.give("stone", 5)
# give yourself 3 dirt blocks
player.give("dirt", 3)
```

---

## Step 2
# Activity:
Accept the gift from your Agent by giving yourself a `sapling`. When you're done, manually plant it on the grass block by selecting it on your hotbar, aiming your cursor at the grass block, and right-clicking.

**Note: You can reset the activity by speaking with the NPC or by using the Reset World button.**

```python
# code here
player.give()
```

---

