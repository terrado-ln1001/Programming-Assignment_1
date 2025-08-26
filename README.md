# Programming-Assignment_1
## Description
This lesson is about learning the basic codes and functions in Python. It also shows how to use them to make simple programs.

## Learning Outcomes
1. Identify the basic codes and functions in Python programming.  
2. Apply the different codes and functions in creating a Python program.

## Alphabet Soup Problem
Create a function that takes a string and returns a string with its letters in alphabetical order.

### Example:
```python
def alphabet_soup(text):
    return ''.join(sorted(text))

print(alphabet_soup("hello"))
# Output: ehllo

print(alphabet_soup("hacker"))
# Output: acehkr
