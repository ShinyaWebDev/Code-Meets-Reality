# Medication Reminder

**Status:** Planned

## Purpose

Explore an accessible physical reminder and acknowledgement device connected to a local desktop application.

## Concept

```mermaid
sequenceDiagram
    participant App as C# application
    participant Device as ESP32 device
    participant User
    App->>Device: Reminder command
    Device->>User: Light and brief sound
    User->>Device: Press confirmation button
    Device->>App: Acknowledgement event
    App->>App: Save local record
```

## Safety boundaries

- This is a learning and reminder aid, not a medical device.
- A button press does not prove medication was taken.
- Device or connection failure must be visible.
- It must not dispense medication.
- It must not replace clinical advice or caregiver processes.
