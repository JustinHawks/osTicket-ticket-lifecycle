# osTicket-ticket-lifecycle

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

1. Log in as a help desk User and open a new ticket.

![01_openaticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/72a5d255-93d0-4519-9a3e-337877e16def)

2. Enter the User's contact information. Select a Help Topic. For example, Darth Vader has a "Business Critical Outage" and explains that the organization's customer-facing application is down.

![02_sevAticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/f1d23cdc-9de2-446f-9ec2-76a3bc935446)
![03_sevAticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/38a2c433-a864-42fa-a3dc-fc55c717657f)

3. Jar Jar Binks opens a new ticket because the shipping department fulfillment software cannot process orders after an upgrade from the day before. He uses the Help topic called "Personal Computer Issues". 
   
![04_sevBticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/5653ab05-c120-4506-8d35-c1b7da54ffac)

4. Darth Vader opens another ticket because the tablets on the showroom floor are running very slowly. He wants to inquire about when his team will receive upgraded hardware. He uses the Help Topic called "General Inquiry".

![05_sevCticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/2cf312dd-dc1f-4255-80fe-7d142b94907a)

5. Log into the osTicket agent portal to resolve tickets. Luke Skywalker logs in as an admin.

![06_agentlogin](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/74a41908-f9e6-4826-8dd7-c84a36446fce)

6. The "Tickets" tab displays all of the tickets that were submitted by Darth Vader and Jar Jar Binks. Now Luke can open the tickets and read the details.

![07_opentickets](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/76554d87-c36b-48cc-b55c-f4a0174332d8)
![08_opentickets](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/2248aadf-cb0b-4520-b6d2-74c61ba18cd4)

7. Based on the details of this ticket. Luke changes the priority level to "Emergency" with a brief description.

![09_opentickets_priority level](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/0a04c31d-0ef0-443a-a0a3-d6f392f95801)

8. Luke assigns this ticket to himself to resolve.

![10_opentickets_assign](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/bafc2dee-16cf-41fb-a883-958db0df6d28)

9. Luke updated the SLA Plan to "SEV-A", meaning this needs to be resolved within the hour that the ticket was opened.

![11_opentickets_SLA](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/5e9e6492-9e14-4c45-ae5c-3ad76a17b067)

10. Now we can see the open ticket with all of the updates. Luke posts a reply with a simple update to Darth Vader stating that he is "coordinating with sys-admin team to bring customer-facing app online."

![12_opentickets_updatedticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/495220f8-fbeb-4e52-ad84-aaa6915042b7)
![13_opentickets_comments](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/e2119cfb-a9ee-458d-a336-10bc5f9facc8)

11. If we go to Tickets > Open, we can see that the ticket was given "Emergency" priority and it was assigned to Luke Skywalker.

![14_opentickets_updated portal](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/ed796d83-9617-4149-9cd9-cdaf1f9b4059)

12. Now Luke will resolve and close the ticket. He posts a reply updating Darth Vader that "Yoda from the engineering team found and corrected a failed line of code. App is back online." He updated the Ticket Status to "Resolved".

![15_resolveopentickets](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/b708762f-2ae9-4790-8de7-aafee2aede68)
![16_closedticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/cf252d5f-fc36-488d-8bca-b7c298bd0ea4)

13. Luke addresses another ticket opened by Jar-Jar Binks stating that, "Ever since the upgrade last night, our staff is unable to process customer orders." He updated the Priority to "High" and the SLA Plan to "SEV-B" with a brief description of the issue stating that it's, "Effeting the productivity of the whole department." He then assigned the ticket to R2-D2,  another help desk agent. He leaves an update stating that he "Re-assigned to SEV-B, and reached out to R2-D2 for a warm hand-off." Luke uses internal communication via email/instant messaging to let R2-D2 know to look at the ticket.
    
![18_sevBassignticket](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/13d9922b-7204-4356-9369-24f71e7eb382)
![17_sevB](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/0cc4eb2d-85de-4724-834f-4e97b621a06f)

14. In the meantime, Darth Vader has another issue and opens another ticket stating "Most of our tablets are running very slow while assisting customers on the showroom floor. We need new tablets ASAP. When are they being sent to us?". Luke updates the priority level to "Low", and assigns the department to "Support". He updated the SLA Plan to "SEV-C", and assigned the ticket to himself. He feels that he can resolve the ticket now with a quick replay to Darth Vader offering a temporary solution stating "New tablets are slated to ship in Q1. We may have a few of the new tablets here for testing purposes that you can use temporarily. I will come over to your department later today." He updates the Ticket Status to "Resolved" and closes the ticket.

![19_sevC](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/21291fc8-9cb4-4b81-9b37-dc93dce60662)

15. R2-D2 logs in to the osTicket Agent portal.

![20_loginr2d2](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/318d3704-97c3-439b-b717-a133cb482a15)

16. R2-D2 sees that Luke Skywalker assigned a ticket to him which was opened by Jar-Jar Binks. R2-D2 has found a solution and leaves an update stating that he "Rolled back version of the software to the previous version to allow shipping to process orders for now. In the meantime, I will look into why the new version doesn't work on the shipping department hardware. He updates the Ticket Status to "Resolved" and closes the ticket.

![21_sevCresolved](https://github.com/JustinHawks/osTicket-ticket-lifecycle/assets/88342524/b5371720-658e-4631-99d7-2306768bd8cf)

