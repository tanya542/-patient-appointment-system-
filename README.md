# Patient Appointment Rescheduling System

## System Context Diagram
```mermaid
graph TD
    Patient([Patient / User]) -->|Requests Reschedule / View Details| System[Appointment Management System]
    System -->|Sends Confirmations / Alerts| NS[Notification Service]
    System -->|Persists Data| DB[(Appointment Database)]
