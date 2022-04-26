---
title: "Strings"
date: 2022-02-11T11:17:41-05:00
draft: false
cover:
    image: /images/python_logo.png
    alt: 'python logo'
    caption: 'Python'
resources:
    - src: "no_output.png"
      title: No output
    - src: "strings_on_quotes.png"
      title: "Strings on quotes"
    - src: "syntax_error.png"
      title: "Syntax error message"
    - src: "backslash.png"
      title: "Escape character"
tags: ["coding","programming", "python", "string"]
categories: ["Coding", "Programming Language"]
---


- __Strings__ in Python can be represented by wrapping them by using ' ' (single quotes), " "(double quotes), or ''' ''' (triple quotes)

```python
'This is Hello World using single quotes.'

"This is Hello World using double quotes."

"""This is Hello World using

triple quotes

This is also called multi-line strings."""

```

![No output](no_output.png)

- To display the string as an output to the screen I can use Python bulit-in function, __print()__
```python
print('This is Hello World using single quotes.')

print("This is Hello World using double quotes.")

print("""This is Hello World using

triple quotes

This is also called multi-line strings.""")
```

![Strings on quotes](strings_on_quotes.png)

- There will be a syntax error if I'm using an apostrophe in a string that is wrapped by single quotes, likewise I also will get a syntax error when I use quotes in a string that is wrapped by double quotes.
```python
print('I'am using an aposthrope here.')
```

![Syntax Error message](syntax_error.png)

- This error can be prevent by using the escape character \ (backslash). 
Without the backslash, the apostrophe and quotes are seen by Python as the end of the string. 
```python
print('I\'am using an aposthrope here.')

print("I am using \"quotes here\" in a string wrapped by double quotes.")
```

![Escape character](backslash.png)


