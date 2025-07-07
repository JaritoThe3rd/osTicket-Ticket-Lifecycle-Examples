# osTicket Ticket Lifecycle Lab

## Login Pages

- Admin/Analyst Login:  
  http://localhost/osTicket/scp/login.php

- End User Portal:  
  http://localhost/osTicket

## Objective

Simulate real-world help desk workflows by:

- Creating tickets as end users
- Observing and modifying ticket properties
- Assigning SLAs and departments
- Resolving tickets as help desk agents
- Understanding access control and escalation processes

## Initial Setup

1. Change the "SysAdmins" Department to a Top Level Department.
2. Delete the "Maintenance" Department (do not archive).

---

## Ticket 1: Entire Mobile/Online Banking System is Down

### As an End User

- Create a ticket with the following issue:  
  "Entire mobile/online banking system is down"

  

https://github.com/user-attachments/assets/8ca2b8bd-8c06-4d3b-9d88-964bd6befd11



### As Help Desk Agent "john"

- Observe ticket properties:
  - Priority
  - Department
  - SLA
  - Assigned To

- Set the following properties:
  - SLA: Sev-A (1 hour, 24/7)
  - Department: Online Banking

- Attempt to observe the ticket again as "john". Can you view or change it?

### As Help Desk Agent "jane"

- Work the ticket to completion

---

## Ticket 2: Adobe Upgrade Request

### As an End User

- Create a ticket with the following issue:  
  "Accounting department needs Adobe upgrade, broken"

### As Help Desk Agent "john"

- Observe ticket properties:
  - Priority
  - Department
  - SLA
  - Assigned To

- Set the following properties:
  - SLA: Sev-B (4 hours, 24/7)
  - Department: Support

- Work the ticket to completion

---

## Ticket 3: CFO’s Laptop Will Not Turn On

### As an End User

- Create a ticket with the following issue:  
  "CFO’s laptop will no longer turn on"

### As Help Desk Agent "john"

- Observe ticket properties:
  - Priority
  - Department
  - SLA
  - Assigned To

- Set the following properties:
  - SLA: Sev-B (4 hours, 24/7)
  - Department: Support

- Work the ticket to completion

---

## SLA Escalation and Access Control

- Set all ticket properties; ensure SysAdmins ticket is set to Sev-A
- Observe the ticket becomes inaccessible to agent "john"
- As Admin:
  - Assign "View-only" access to SysAdmins department
- Switch back to agent panel:
  - Observe escalated ticket
  - Note that you can no longer make changes

- Solve all tickets

---

## Ticket Communication Features

Most ticketing systems, including osTicket, support email notifications.  
Each time a ticket is updated, the end user receives an email update and can respond through that email.

---

## Real-World Ticket Intake

In real-world environments, tickets may originate from:

- Phone calls
- Chat applications
- Emails
- Web forms
- In-person requests

While quick fixes on-the-spot are common, it is essential to log all issues into the ticketing system. This builds data for reporting and helps track team metrics.

---

## Finishing Up and Additional Practice

- osTicket includes many more features not covered here
- Practice this lab multiple times until familiar with the full lifecycle
- Explore the email notification feature
- Use this checklist to reinforce your technical support process

---

## Technical Skill Development

Repetition builds technical intuition. This lab supports the foundational pillar of technical ability. Re-do the exercise until you can complete it without assistance.
