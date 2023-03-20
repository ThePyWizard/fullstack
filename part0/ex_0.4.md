```mermaid
sequenceDiagram
    participant browser
    participant server
    
    browser->>server : http get request to <site>
    activate server
    server-->>browser: request
    deactivate server
    Note right of browser : hi there this a new request
```
