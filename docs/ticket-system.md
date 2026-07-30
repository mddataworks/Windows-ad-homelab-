# Ticket System - Help Desk Simulation

This section simulates real-world IT help desk tickets using Spiceworks Cloud Help Desk (free, web-based). It applies proper ticket components (summary, description, priority, category) and practices the full ticket lifecycle — creation, response, and closure.

## Tools
- Spiceworks Cloud Help Desk (free)

## Setup

- Signed up for a Spiceworks account and accessed IT Tools > Cloud Help Desk
- Opened the Cloud Help Desk dashboard to begin creating and managing tickets

![Spiceworks IT Tools menu](spiceworks-menu.png)

![Cloud Help Desk landing page](spiceworks-helpdesk-landing.png)
![Initial ticket queue](spiceworks-ticket-queue-initial.png)

## Lab 1: Simulated Ticket Creation

**Goal:** Practice creating a properly detailed ticket using the components covered in the lecture (requestor, summary, description, priority, category).

- Created a new ticket for a hardware issue: monitor not displaying anything
- Included device/host name, detailed description, troubleshooting already attempted, and availability for contact
- Set priority to Medium and category as Hardware

![Blank ticket creation form](create-ticket-blank.png)
![Filled ticket - monitor issue](create-ticket-monitor-filled.png)
![Ticket queue showing new ticket created](ticket-queue-monitor-created.png)

## Lab 2: Ticket Closure

**Goal:** Properly resolve and close a ticket, including confirming resolution with the user and documenting notes.

- Created a ticket for a Wi-Fi connectivity issue (laptop not auto-connecting in the office)
- Investigated and responded to the user with the root cause and fix
- Practiced confirming resolution before closing the ticket

![Filled ticket - Wi-Fi issue](create-ticket-wifi-filled.png)
![Ticket response and resolution](ticket-wifi-response.png)

## Bonus: Account Lockout Ticket

- Created and resolved an additional ticket simulating a locked-out user account due to an expired password (tied to the domain's 90-day password policy configured earlier in the AD lab)
- Responded to the user with the cause and a temporary password, including password requirements

![Password lockout ticket](ticket-password-lockout.png)

## Closing Tickets

- Verified both resolved tickets appear correctly under the **Closed** queue

![Closed ticket queue](ticket-queue-closed.png)
