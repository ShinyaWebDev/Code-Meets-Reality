# Repository Model

Code Meets Reality is the portfolio and knowledge hub.

Each substantial application or firmware project has its own repository.

```mermaid
flowchart TD
    H[Code Meets Reality<br/>hub repository]
    H --> D[Daily Checker<br/>application repository]
    H --> G[Guitar Humidity Monitor<br/>future repository]
    H --> M[Medication Reminder<br/>future repository]
    H --> K[Karate Motion Analyser<br/>future repository]
```

## Why separate repositories?

Each project can have its own:

- source history
- issues
- releases
- build instructions
- dependencies
- CI workflow
- licence
- contributors

The hub repository provides:

- shared vision
- overall roadmap
- knowledge notes
- project catalogue
- learning journal
- decision records
- links to source repositories

## What does not belong here?

- copied application source code
- build outputs
- secrets
- personal health records
- proprietary work code
- confidential employer information
