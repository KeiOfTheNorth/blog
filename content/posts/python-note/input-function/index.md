---
title: "Input Function"
date: 2022-02-12T04:11:50-05:00
draft: false
cover:
    image: /images/python_logo.png
    alt: 'python logo'
    caption: 'Python'
resources:
    - src: "waiting_for_input.png"
      title: "Waiting for input"
    - src: "taking_input.png"
      title: "Taking input from user"
tags: ["coding", "programming", "python", "input", "function"]
categories: ["Coding", "Programming Language"]
---

- The __Input function__ is used to take input from the user.

```python
user = input("Please enter your name: ")

print(50 * "=")

print(f"Hello {user}, Good Morning!")

first_num = input("Enter a number to multiply: ")
second_num = input("Enter a second number to multiply: ")
result = int(first_num) * int(second_num)

print(f"{first_num} * {second_num} = {result}")
```

- Because Python runs from top down, it will not execute the next line of code until I typed the input

![Waiting for input](waiting_for_input.png)

![Taking input](taking_input.png)
