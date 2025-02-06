# HW4-2 Test Cases
### Example graph for test04 - not a DAG
```mermaid
graph TD;
    A[0] --> B[1];
    B[1] --> C[2];
    C[2] --> D[3];
    D[3] --> B[1];
    
