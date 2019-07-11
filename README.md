## Depolyed Link:

[Click here](https://73aye7dbzc.execute-api.us-west-2.amazonaws.com/repeatedword?input=)

- Copy and paste this link in the browser.
- At the end of the link add a sentence.
- Press enter and you will see a result.

# Challenge Summary
Write a function called RepeatedWord which takes a String as an argument.

## Challenge Description
Without utilizing any of the built-in methods available to your language, return the first word that is repeated in the 
given string.

## Approach & Efficiency
First step is to create a string array that will hold the each word of the given string, this is done by doing string split.
Next is to set an empty string variable `current` that will hold the value of a word. Now we have to use a HashMap so that 
we can get the key and value pairs for a comparison of the words. Now we loop through the array to give `current` the value
of the given word and store it to the HashMap. If the value is repeated we return `current` and if there are no repeated values 
we return `null`