<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

__Intake__: This is where the ticket is first created.
- *Source*: Tickets can come in via email, web portal, phone (entered by staff), or API
- *Initial Capture*: The system records details like subject, description, requester info, department, and priority
- *Ticket Number*: A unique ID is assigned so it can be tracked
- *Auto-Response*: The customer usually gets an acknowledgment email confirming receipt
</p>
To create a ticket, users must access the ticket portal and log in if required. Once inside, they can submit a request and provide details about their IT-related issue.
</p>
<p>
<img width="863" height="715" alt="image" src="https://github.com/user-attachments/assets/539c3ab4-a179-45fd-a0b5-9ba8f2935ad5" />
</p>
<br />
<p>

---

__Assignment and Communication__: Once a ticket exists, it needs to be directed and clarified.
- *Assignment*: The ticket is routed to the correct department or agent. This can be done automatically (via rules/filters) or manually by staff
- *Prioritization*: Staff may adjust urgency/priority levels (e.g., low, normal, high, emergency)
- *Communication*: Agents may reach out to the requester for clarification, additional details, or updates. Internal notes can also be added for team collaboration.
- *Visibility*: Everyone involved can see the history of communications and actions taken.
</p>
Once a ticket is created, it is assigned to the appropriate department or agent, with priority levels adjusted as needed. During this stage, agents communicate with the requester for clarification, share updates, and use internal notes to ensure team collaboration and visibility.
</p>
<br />
<p>
  
<img width="700" height="750" alt="image" src="https://github.com/user-attachments/assets/9540e080-e9a4-4b80-b08d-00e949f78aae" />

---

__Working the Issue__: This is the active problem-solving stage.
- *Investigation*: Agents analyze the problem, replicate issues if needed, and look for solutions
- *Collaboration*: The ticket may be transferred, escalated, or collaborated on with other teams
- *Progress Tracking*: Status changes reflect movement (e.g., Open → In Progress → Awaiting Reply)
- *Customer Updates*: The requester is kept in the loop via replies or status changes
</p>
In the working stage, agents actively investigate the issue, collaborate with other teams if needed, and track progress through status updates. The requester is kept informed throughout the process with regular communication and updates.
</p>
<br />
<p>

---
  
__Resolution__: The ticket reaches closure when the issue is handled.
- *Solution Delivery*: The agent provides the resolution, instructions, or fix.
- *Verification*: The requester may confirm if the solution works.
- *Closure*: The ticket status is changed to Closed or Resolved.
- *Post-Resolution Actions*: Some setups include customer satisfaction surveys or feedback collection. Reports can also be generated for metrics (e.g., average resolution time).
</p>
In the resolution stage, the agent delivers the fix or instructions and confirms the issue is resolved. The ticket is then closed, with optional follow-up actions like feedback surveys or reporting for performance metrics.
<br />

<h2>Closing Thoughts</h2>

Ticket management protocols can vary across different work environments. Some teams may have quotas for resolving a set number of tickets within a given timeframe, while others prioritize tickets based on urgency or impact. By building osTicket from the ground up, I gained a clear understanding of how tickets are handled in an IT role.
</p>
<br />
