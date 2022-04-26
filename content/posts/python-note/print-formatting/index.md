---
title: "Print Formatting"
date: 2022-02-11T23:20:59-05:00
draft: false
cover:
    image: /images/python_logo.png
    alt: 'python logo'
    caption: 'Python'
resources:
    - src: "print_formatting.png"
      title: "Print formatting"
tags: ["coding","programming", "python", "print", "string", "format"]
categories: ["Coding", "Programming Language"]
---

- There are several ways to output the result using __print()__

```python
apples_in_basket = "111"

print("There are " + apples_in_basket + " apples in the basket")
print("There are",apples_in_basket,"apples in the basket")
print("There are {} apples in the basket".format(apples_in_basket))
print(f"There are {apples_in_basket} apples in the basket")
```

![Print formatting](print_formatting.png)



