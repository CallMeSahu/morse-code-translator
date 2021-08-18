# Morse Code Translator
Translation app based on VanillaJS. User can enter phrase in english and the app will converts it to morse code (used in military to pass secret messages) using an API from [Fun Translations](https://funtranslations.com/).

## Working
1. User enters a phrase in english language in the input section.
1. On clicking the CONVERT TO MORSE button the app reads the value of the input section.
1. It then fetches the translation URL of the API and passes the user input string collected and waits for a response from the API server.
1. Upon receiving a response from the server in JSON format it converts the string into text and displays it in the output section.