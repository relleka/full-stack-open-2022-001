```mermaid
sequenceDiagram
user->>browser: user clicks submit
browser->>server: http post request for new note over
server->>browser: 302 status code / http get request
note left of browser: browser reloads
```
