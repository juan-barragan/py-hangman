# py-hangman

The goal of this excercise is to write a python program for guessing the word a player has chosen. Just like the game of hangman.

## Rules
1. Initially the program ask you the length of your chosen word.
> How many chars your chosen word has ==> ?
2. Your program should make the **best informed decision** for selecting the chars on the word the  player has chosen. Use the English dictionary present on each POSIX system, each word is lowercase. Read it from (use lowercases or upercases)
> /usr/share/dict/words

otherwise download it from here on folder **assets**

3. The player informs the computer if the proposed char is present on the word, If yes players provide a list of occurrences of the char. We assume on strings first char it a 0 (zero) position. And the position will be given as p1,p2,p3...
> Is the char 't' present (y/n) ==> n|y [0-9]+?
4. Dont get hanged!
