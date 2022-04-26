---
title: "Importing Module"
date: 2022-02-11T23:08:26-05:00
draft: false
cover:
    image: /images/python_logo.png
    alt: 'python logo'
    caption: 'Python'
resources:
    - src: "lowercase.png"
      title: "Importing ASCII lowercase"
    - src: "uppercase.png"
      title: "Importing ASCII uppercase"
tags: ["coding","programming", "python", "import", "module", "method", "function"]
categories: ["Coding", "Programming Language"]
---

- To use a Python module I can import it by typing `import` followed by the name of the module. 
   This will import the module with all its functions and methods

```python
import string

print(string.ascii_lowercase)
```

![Importing ASCII lowercase](lowercase.png)


- I can just import a particular method or function in a module instead of the whole module

```python
from string import ascii_uppercase
  
print(ascii_uppercase)
```

![Importing ASCII uppercase](uppercase.png)

