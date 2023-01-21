Create a similar diagram depicting the situation where the user creates a new note on the page https://studies.cs.helsinki.fi/exampleapp/notes by writing something into the text field and clicking the submit button.


```mermaid
sequenceDiagram
    participant browser
    participant server

    <!-- user clicks input box
    user types into input field -->
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    
```