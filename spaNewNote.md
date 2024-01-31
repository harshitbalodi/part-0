````mermaid
    sequenceDiagram
    participant browser
    participant server

   

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: {content: "Single page app", date: "2024-01-31T18:18:06.155Z"}
    deactivate server

    Note right of browser: The browser executes the callback function that renders the note.
````