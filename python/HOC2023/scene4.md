### @flyoutOnly true
### @hideIteration false
### @explicitHints true

## Step 1
# Smart Doorlock

We've discovered a significant problem with the door lock system. Right now, anyone can see the event logs, which is a big privacy and security concern. To fix this issue, we need to update the code so that only administrators have access to the event logs.

The `permission_group()` function takes one parameter which defines which permission group it's being compared to.

Valid permission groups are: 
- `anyone`
- `user`
- `admin`

```python
while human_detect():
    if user_authorized():
        check_user_permissions()
        if user_permissions() == permission_group("anyone"):
            enable_log_viewing()
        else:
            disable_log_viewing()
```
