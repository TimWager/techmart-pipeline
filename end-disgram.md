# ERD Diagram

```mermaid
erDiagram
    AUTHOR {
        int author_id
        string name
    }
    BOOK {
        int book_id
        string title
    }
    AUTHOR ||--o{ BOOK : writes
```
