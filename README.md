# py-hangman

The goal of this excercise is to write a python program for guessing the word a player has chosen. Just like the game of hangman.

## Rules
1. Initially the program ask you the length of your chosen word.
> How many chars your chosen word has ==> ?
2. We give to the computer, the number of tryouts for guessing our word.
> How many times can I fail before being hanged ==> ?
3. Your program should make the **best informed decision** for selecting the chars on the word the  player has chosen. Use the English dictionary present on each POSIX system, each word is lowercase.
> cat /usr/share/dict/words | tr '[:upper:]' '[:lower:]' > words.txt

otherwise download it from here on folder **assets**

4. The player informs the computer if the proposed char is present on the word, If yes players provide a list of occurrences of the char. We assume on strings first char it a 0 (zero) position. 
> Is the char 't' present (y/n) ==> n|y [0-9]+?
5. Dont get hanged!