### @flyoutOnly true
### @hideIteration false
### @explicitHints true

# Scene1

## Step 1
# Food Dispenser

The automatic food dispenser can't detect some students. Review the code and make changes so it can identify all students.

You should focus on the `scan()` function, which is the function that controls how the food dispenser detects a person. The function takes one string as a parameter and has two settings – `horizontal` or `smart`.

Valid scan types are: 
- `horizontal`
- `smart`

```python
# CODE EXAMPLE - YOU CAN NOT EDIT HERE
# RUN IT TO SEE WHAT HAPPENS

while lunch_time():
    scan("horizontal")
    if detect_student():
        serve_lunch()
    wait_for_student()
```

---

## Step 2
# Activity:

Update the code to change the scan type from `horizontal` to `smart`

```python
# code here

while lunch_time():
    scan("horizontal")
    if detect_student():
        serve_lunch()
    wait_for_student()
```

---

