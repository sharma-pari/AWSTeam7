- Gantt code/syntax: https://mermaid.js.org/syntax/gantt.html 
- markdown syntax: https://www.markdownguide.org/cheat-sheet/ 

- assuming we work on the project from 2/28 to 5/2
- should we categorize our sprint weeks into diff sections, ex: phase 1 of project: infrastructure?????
- sprint week doesn't necessarily have to be a week long, we could make some sprint weeks many weeks long?
- also maybe instead of naming sprint week 1, 2, 3, etc, we name it the specific task goal, or combine them ex: "sprint week 1: task"

```mermaid
gantt
    title AWS Project: Software Timeline
    dateFormat YYYY-MM-DD
    section Section
        Sprint Week 1        :a1, 2025-02-28, 7d
        Sprint Week 2        :after a1, 7d
        Sprint Week 3        :2025-03-14, 7d
        Sprint Week 4        :2025-03-21, 7d
        Sprint Week 5        :2025-03-28, 7d
        Sprint Week 6        :2025-04-04, 7d
        Sprint Week 7        :2025-04-11, 7d
        Sprint Week 8        :2025-04-18, 7d
        Sprint Week 9        :2025-04-25, 7d
        Sprint Week 10       :2025-05-02, 7d
    section Another
        Task in Another    :2025-05-02, 7d
```
