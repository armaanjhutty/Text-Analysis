# Text-Analysis
This is a python code that analyzes the a text file and provides info on that file

** How The Code Works:

1. The script opens the file that txt file that you want to be interpreted, reading its content into a string variable
2. It then counts the word count of the txt file by splitting the string and then counting the number of resulting substrings using whitespaces
3. The code then counts the total number of punctuation in the text by iterating each character in the text and seeing if it appeals to the string.punctuation set
4. The code then counts the number of specific puncuation in the text (periods, exclamations, commas, colons) by using count()
5. The code counts the total amount of uppercase letters in the txt file by checking over each character to see if its uppercase using the isupper() method
6. It then sees the most common word using the counter class from the collections module, this allows us to see how many times a word is repeated
7. The code then prints out all the results

## Sources
Commented in code
- https://www.reddit.com/r/learnpython/comments/rbqk4u/how_to_check_for_punctuations_in_a_string/
- https://stackoverflow.com/questions/53376146/what-does-sum1-for-c-in-sentence-if-c-isupper-mean-in-non-programming-terms
