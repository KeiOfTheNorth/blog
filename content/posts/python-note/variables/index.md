---
title: "Variables"
date: 2022-02-11T12:29:39-05:00
draft: false
cover:
    image: /images/python_logo.png
    alt: 'python logo'
    caption: 'Python'
resources:
    - src: "variables.png"
      title: Variables
tags: ["coding", "programming", "variable", "python"]
categories: ["Coding", "Programming Language"]
---

- __Variables__ are memory location references which store values

```python
morning_message = "Hello, Good Morning!"

evening_message = "Hello, Good Evening!"

print(id(morning_message))
print(morning_message)

print(id(evening_message))
print(evening_message)
```

![Variables](variables.png)


- __Variable Name Rules__ :
	1. A variable name must start with a letter or an underscore
	2. Can only contain alphanumeric characters (A-Z, a-z, 0-9) and underscores (\_)
	3. Case sensitive