# Intro
In Python🐍 there are different kinds of data that can be given to a variable. It is important to understand these data types well enough to be able to use other peoples' tools or programs.

## Data Types
* A variable is whatever you assign it with.
* A string (e.g., `Nelson`) or sequence of letters `hihi`.
* Integer are numbers (e.g., `1`, `100`)
* Flaot are numbers with decimals (e.g., `1.1`, `100.1`)
* List `[]` are a collection of data types (e.g., `['haha', 'nelson', 'Ben']`)
* Dictionary `{}` has a key and a value respectively (e.g., `{'age' : '24', 'name': 'Nelson'}`).
* Boolean are True or False given to a variable (e.g., `a = True` or `a = False`).

## Useful tools for list and dictionary
* To add a integer into a list with strings, we have to use `'variable name'.append()`.
* For dictionary, we can use `'variable name'['key']` to

## Slicing 
Slicing is an operation that lets you extract a sequence portion of a sequence.

> To search for what data is at a specific place

``` Python
# for example
b = ['human', 'haha', 100, True, 1.2, 1, 2, 3] # a list of data

type(b) # Would give us list

b[0] # this would give us the 'human'

b[1] # would give us 'haha'
b[-1] # would give us 3

b[:3] # would give us 'human', 'haha', and 100
b[-2:] # would give us 3, 2
```

> To search for a specific data associated within that sequence, you can use `'variable name'.index['data']`.

``` python
# searching for 'human'
b = ['human', 'haha', 100, True, 1.2, 1, 2, 3] # a list of data
b.index ('human') # would get '0'

# adding 'banana'
b.append ('banana') # would add banana to the list
```


> To search for keys, values, or add new ones.
```python
# searching
a = {'name': 'nello', 'location': 'singapore', 'age' : '99'}

a.keys() # would return all the keys
a.values() # would return all the values

# adding keys and values
a['interest'] = 'basketball # this would add it into the dictionary
print(a) # would return the dictionary with the newly added key and value
```






