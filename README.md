# Real Links Code Challenge

Thank you for interest in a position with the Engineering team at Real Links!

In this repository, you will find the skeleton of a web application for finding anagrams of a given input.

Your task is to complete the application by implementing the functionality described in the User Story below.

Please clone the repository and [email a link to your completed project to the Engineering team](mailto:dev@reallinks.io).

## User Story

- As a user
- When I enter a string of characters into the input field
- If there are matching anagrams, I want to see a list of those words (including the input, if it is a valid word)
- If there are no matching anagrams, I want the lack of matches to be clearly communicated

An anagram is defined as a word formed by rearranging the letters of a different word. In this case, we consider any word containing exactly the same alphanumeric characters to be an anagram, ignoring any punctuation or changes in case. For example:

1. “iceman” and “cinema” are considered anagrams.
2. “engineer” and “re-engineer” are considered anagrams, ignoring the hyphen.
3. “3D” and “3-D” are considered anagrams, ignoring the hyphen.
4. “Worth” and “throw” are considered anagrams, ignoring the capital letter.

### Acceptance Criteria

- The user can enter a string of characters into an input field.
- The user can see a list of anagrams of the input string.
- The user can see a message if there are no anagrams of the input string.

### Test Cases

1. When the input is empty, the user should see no message or list of results.
2. For the input “asdfghjk”, the user should see the message “No anagrams found”.
3. For the input “steak”, the user should a list of result including the words: “Keats”, “skate”, “Skeat”, “stake”, “steak”, “takes”, “teaks”.
4. For the input “eeenginr”, the user should a list of result including the words: “engineer”, “re-engine”.
