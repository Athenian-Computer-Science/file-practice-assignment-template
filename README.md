# File Practice

## Problem Description
### Task 1
In this exercise, you will create a text file and save it in this repo. Then, write a program that reads the file and
 prints it 3 times:
1) Print the contents once by reading the entire file at once
2) Print the contents by looping over the file object
3) Print the contents by storing the lines in a list and then working with them outside the `with` block

### Task 2
Next, use the  `replace()` method to replace a specific word with another word (for every occurrence). Print the
 modified text to the screen.

Example:
 ```
message = 'I like winter break.'
message.replace('winter', 'summer')

>>> I like summer break.
```
Then, use `replace()` again to reverse the changes so the file is in its original state. (This will allow the program to run again without throwing errors.)

### Task 3
Finally, count the number of words in the file.
* Use the `split()` method to separate each word and then use `len()` to find the number of words:
```
words = message.split()
num_words = len(words)
print('Choose your own message about how many words are in the file.')
```

