```mermaid
sequenceDiagram
user->>browser: open page 
browser->>server: request for url new-note-spa
server->>browser: url new_not_spa
browser->>server: get request for json.data
server->>browser: json.data 
server->>browser: status code 201 
note left of browser: page rendered
```
