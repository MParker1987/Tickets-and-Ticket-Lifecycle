# Tickets and Ticket Lifecycle
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

Tickets
=======

**Agent Panel > Tickets**

When an agent logs in to the help desk, they will be automatically routed to the Open Ticket Queue.

<img src="https://osticket.com/wp-content/uploads/2021/01/Assign_Transfer_Referral_1.jpg"/>

These are tickets the Agent has access to based on their Department and Group assignments as well as tickets that are assigned directly to them or a team they are included.

Tickets are sorted first by the Priority Level and second by the Date- which is the date of last update. Each column of the queue is sortable but the default will return to the Priority/Date sorting each time they log-in.

There are 5 Queues along the sub-tab including:

**Open:** these are tickets Open in the Help Desk including both New Tickets and tickets that the end user is the last respondent on. These will have a BOLD ticket number to give the visual

**Answered:** These are tickets that have been responded to by Agents and are awaiting response back from the ticket owner. This queue can be collapsed into the Open ticket queue. Tickets that have been answered will not have a bold ticket number to visually represent the last action was by the Agent.

**My Tickets:** These are ticket that are assigned directly to the Agent or a team the Agent is assigned.

**Overdue:** These tickets have exceeded the assigned SLA Plan or Due Date assigned to the ticket. SLA Plans can be determined by the Department, Help Topic or Ticket Filter configuration. Due Dates are manually assigned to tickets when an Agent creates a ticket from the client portal or when they edit an existing ticket.

**Closed:** Tickets in this queue have been marked closed by the Agent either upon response to the end user or from the quick button of the ticket queue. Tickets that are marked closed can be reopened on response by the end user.

Tickets in these queues are not unique to each queue meaning that there may be some overlaps- For example, a ticket can be Answered and Overdue at the same time and therefore, will appear in both ticket queues.

Agents can preview the metadata of the ticket by hovering over the ticket number. A pop-up box will appear allowing the Agent access to actions along the bottom of the pop-up as well as access to the collaborators of the ticket.

<img src="https://d3bql97l1ytoxn.cloudfront.net/app_resources/44678/screenshot/img2147879080862405240.png"/>

Agents can open up the ticket by clicking on the Ticket Number or the Subject of the ticket. When an agent opens the ticket, the default will be to direct them to the Reply box at the bottom of the ticket.

<img src="https://docs.osticket.com/en/latest/_images/collabs_ticket_reply.png"/>

Based on their Role permissions, Agents can reply back to the end user by typing their response into the box- including adding attachments, links and embedding YouTube videos. Agents can select a canned response from the drop down in the reply box even if typing some of the response. All canned responses can also be edited by the Agents in the reply box prior to being sent. Collaborators can be added here to have access to the ticket. If necessary, the status of the ticket can be changed from the drop down prior to posting the response.

If a response is required yet the Agent does not want to send the response to the user but still post the response to the ticket thread, they can select the “Do Not Email Reply” from the drop down above the reply box for the user. This will also not send email replies to any collaborators on the ticket.

This response will be in the thread and visible to the ticket owner and any collaborators when they check the status of the ticket from the Client Portal of the help desk.
