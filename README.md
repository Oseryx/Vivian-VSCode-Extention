# Vivian Language Support

This is the README of the vivian's vscode extension, responsible for the syntax highlighting for now, it stills in beta
For now it supports:
- Keywords
- Operators
- Comments (only one line comments)
- Variables
- Procedures
- Classes, Enums and Structs

## Known issues

- Wrong tokens, for now the extension has been focused on the highlight part but not the tokens, for example the ``+`` is considered as an assignment operator it will be fixed soon

## To Do

- Improve regex, some of the regex are just ugly and should be improved
- Add conversion tokenization, so it'll handle differently some functions like ``float64(x)`` ``uint8(x)`` etc
- Add Multi-Line comments support
- Add semantic highlight support for better syntax and UX

## Test and Debug

Clone the project 
Open it with vscode and hit ``F5`` which will open a new window with the extension loaded