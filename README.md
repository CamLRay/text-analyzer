Describe: wordCounter()

Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

Test: "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

Test: "It should return 0 for an empty string."
Code: wordCounter("");
Expected Output: 0

Test: "It should return 0 for a string that is only spaces."
code: wordCounter("          ");
Expected Output: 0

Test: "It should not count integers as words."
Code: wordCounter("hi there 77 19");
Expected Output: 2

Describe: numberOfOccurencesInText();

Test: "It should return 0 occurences of a word for an empty string."
code:
const text="";
const word="red";
numberOfOccurencesInText(word, text);
Expected Output:0
Expected Output: 0

Test: "It should return 1 occurrence of a word when the word and the text are the same."
Code:
const text = "red";
const word = "red";
numberOfOccurrencesInText(word, text);
Expected Output: 1