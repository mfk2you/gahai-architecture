# Workflow Engine Diagram

```mermaid
flowchart LR

    Event[Business Event]

    Event --> Workflow[Workflow]

    Workflow --> Task[Task]

    Task --> Approval[Approval]

    Approval --> Reminder[Reminder]

    Reminder --> Escalation[Escalation]

    Escalation --> Completion[Completion]

    Completion --> Audit[Audit Trail]

    Completion --> Notification[Notification]
```
