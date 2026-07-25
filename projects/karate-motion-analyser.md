# Karate Motion Analyser

**Status:** Planned

## Research question

Can a small IMU produce repeatable enough data to compare several controlled repetitions of one karate technique?

## Concept

```mermaid
flowchart LR
    I[IMU] --> E[ESP32]
    E --> A[C# capture app]
    A --> D[Trial data]
    D --> V[Time-series visualisation]
    V --> R[Compare repeatability]
```

## First milestone

Record accelerometer and gyroscope data for five controlled repetitions of one technique.

## Important limitations

- acceleration is not the same as impact force
- wrist data does not describe the whole kinetic chain
- sensor placement affects results
- this is not a clinical or validated sports-science system
