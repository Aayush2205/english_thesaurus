# english_thesaurus
This code create a thesaurus using a json file which give the meaning of the word that the user types as the input.

## Libraries imported

**json**
**get_close_matches** using the difflib library

## Steps

First we open the data.json file.
next we create a function in which we pass a variable which is the word that we need to search for(mainly an input from the user), inside the function we use an if statement to check whether the word is present in the data.json file or not so we check for the word directly , else we check for the word by making the 1st character to uppercase, else we convert the whole word to uppercase(eg- USA,NATA).
or else we can check whether the word that the user enter is mistyped and then we use the get_close_matches to guess the correct word which the user was entering and ask whether this is the word the user was looking for if he press yes then we'll show the result or else re-enter the word.
