---
title: "Dictionaries"
date: 2022-02-22T14:45:41-05:00
draft: false
cover:
    image: /images/python_logo.png
    alt: 'python logo'
    caption: 'Python'
resources:
    - src: "add_key_val.png"
      title: "add key and value"
    - src: "all_keys.png"
      title: "see all keys"
    - src: "add_key_val.png"
      title: "add key and value"
    - src: "all_keys.png"
      title: "see all keys"
    - src: "all_values.png"
      title: "see all values"
    - src: "change_value.png"
      title: "change values"
    - src: "dic_for-loop.png"
      title: "using for loop"
    - src: "dict_items.png"
      title: "all_items"
    - src: "using_get.png"
      title: "use get method"
    - src: "work_with_dict.png"
      title: "dictionary"
    - src: "example_dictionary.png"
      title: "dictionary example"
    - src: "dict_built-in_funcs.png"
      title: "Built-in functions"

tags: ["coding", "programming", "python", "dictionary", "function", "method", "key", "value", ]
categories: ["Coding", "Programming Language"]
---

- __Dictionaries__ using key-value pair for the elements

- Example of a Dictionary

```python
animals = {
  	"marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer",
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }
```

![a dictionary example](example_dictionary.png)

- I can use __dir__ function to list the built-in methods and functions I can use to work with Dictionaries
```python
animals = {
		   "marshmallow":"a black dog who likes to bark at things", 
           "rudolph":"the very shiny red-nosed reindeer",
           "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
}

print(dir(animals))
```

![Built-in functions](dict_built-in_funcs.png)



- I can use __keys__ method to see all the keys in a dictionary
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

print(animals.keys())
``` 

![all keys](all_keys.png)

- Similarly I can also use __values__ method to see all the values in a dictionary
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

print(animals.values())
```

![all values](all_values.png)

- To see both keys and values I can use __items__ method
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

print(animals.items())
```

![dictionary items](dict_items.png)

- I can access a certain value by using its key
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

print(animals)
print("\n")

print(animals["rudolph"])
print("\n")

print(f"Who is Doraemon? \nDoraemon is {animals['doraemon']}")
```

![work with dictionary](work_with_dict.png)

- I can also use __get()__ function 
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

print(animals.get('marshmallow'))
```

![using get](using_get.png)

- To add an item to a dictionary I can do like so
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

animals["sonic"] = "a blue hedgehog who runs extremely fast"

print(animals)
```

![add key-value](add_key-val.png)

- To change the value of an item in a dictionary I can do like so
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

animals['doraemon'] = "a cat who speaks Japanese fluently"

print(animals)
```

![change value](change_value.png)

- To iterate through a dictionary I can use __For__ loop
```python
animals = {
    "marshmallow":"a black dog who likes to bark at things", 
    "rudolph":"the very shiny red-nosed reindeer", 
    "doraemon":"a cat with a pocket to access very advanced technological stuffs from the future"
    }

for key, val in animals.items():
    print(key,val)
```

![dict_for-loop](dict_for-loop.png)
