# Introduction to Python
## Description
This lesson is about learning the basic codes and functions in Python. It also shows how to use them to make simple programs.

## Learning Outcomes
1. Identify the basic codes and functions in Python programming.  
2. Apply the different codes and functions in creating a Python program.

## Alphabet Soup Problem
The problem is asking to create a function that receives a string as input, arranges all the letters of that string in alphabetical order, and then returns the arranged letters as the output.

### Example:
```python
def alphabet_soup(text):
    return ''.join(sorted(text))

print(alphabet_soup("hello"))
# Output: ehllo

print(alphabet_soup("hacker"))
# Output: acehkr
```

### 

## Emoticon Problem
The problem is asking to create a function that takes a sentence as input and replaces the words smile, grin, sad, and mad with their matching emoticons, then returns the updated sentence. For example, the word 'smile' is replaced to the emoticon ':)', so that whenever the words appear in a sentence, they are shown with their corresponding emoticons.”

### Example:
```python
def str(emoticons):
    emoticons = emoticons.replace("smile", ":)")
    emoticons = emoticons.replace("grin", ":D")
    emoticons = emoticons.replace("sad", ":(")
    emoticons = emoticons.replace("mad", ">:(")
    return emoticons
    
print (str("Make me smile"))
# Output: Make me :)

print (str("I am mad"))
# Output: I am >:(
```

## Unpackin List Problem
The problem asked to take the list of numbers and split it to three variables, where the first variable stores the first element of the list, the last variable stores the last element, and the middle variable stores all the remaining elements in between, and then display all three variables as output.

### Example:
```python
writeyourcodehere = [1, 2, 3, 4, 5, 6]

first, *middle, last = writeyourcodehere

print("First:", first)
# Output: 1

print("Middle:", middle)
# Output: 2, 3, 4, 5

print("Last:", last)
# Output: 6
```


