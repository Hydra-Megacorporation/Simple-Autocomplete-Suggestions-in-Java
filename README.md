# Simple-Autocomplete-Suggestions-in-Java
Simple Autocomplete Suggestions in Java writed by ChatGPT from scratch which repeats exactly the same as Android Studo, Jetbrains, Intellij and etc .

The discription by ChatGPT:
In this modified version, we keep track of the previous index of the character found in the word. The autocomplete method uses indexOf to find each character in the input string starting from the previous index + 1. This ensures that the characters are found in the same order as in the input string.

With the updated code, when the input is "al", it will only show "apple" because "apple" contains both "a" and "l" in the same order. "elephant" will not be included in the suggestions because "l" comes before "a" in "elephant".
