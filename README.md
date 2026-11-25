### Workflow Architecture Overview
```
                Employee / Requester
                        │
                 Service Portal
                        │
             New Hire Onboarding Package
                   (Order Guide)
                        │
                    REQ0010030
                        │
       ┌────────────────┼────────────────┐
       ▼                ▼                ▼
   RITM (IT)     RITM (Facilities)   RITM (HR)
       │                │                │
       └────── Manager Approval ─────────┘
                 (Zainab Bello)
       │                │                │
       ▼                ▼                ▼
    SCTASK           SCTASK           SCTASK
       │                │                │
   IT Fulfillment  Facilities Team    HR Team
       │                │                │
  Closed Complete  Closed Complete  Closed Complete
```
