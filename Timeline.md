- Gantt code/syntax: https://mermaid.js.org/syntax/gantt.html 
- markdown syntax: https://www.markdownguide.org/cheat-sheet/ 

- Assuming project cycle from 2/28 to 5/2
- More specialized sprints when project specifications recieved


```mermaid
gantt
    title AWS Project: Software Timeline
    dateFormat YYYY-MM-DD
    section Sprint Schedule 
        Project Initiation and Requirements        :a1, 2025-02-28, 7d 
        Project Plan Development      :after a1, 7d
        AWS and Data Center Research      :2025-03-14, 7d
        Data Center Design        :2025-03-21, 7d
        Environment Initialization and Configuration        :2025-03-28, 7d
        CI/CD Pipeline Setup        :2025-04-04, 7d
        Application Development        :2025-04-11, 7d
        Stakeholder Feedback Edits        :2025-04-18, 7d
        Testing and Validation        :2025-04-25, 7d
        Production Deployment       :2025-05-02, 7d
    
```
