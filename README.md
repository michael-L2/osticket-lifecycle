<p align="center">
<img src="https://osticket.com/wp-content/uploads/2021/03/osticket-supsys-new-1-e1616621912452.png" alt="osTicket logo" />
</p>

<h1 align="center">osTicket: Ticket Lifecycle and Practice</h1>

The goal of this exercise is to demonstrate understanding of SLAs, and the ticketing lifecycle within our osTicket by resolving tickets as Agents.

---

## **Environments and Technologies Used**

- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop Protocol (RDP)**
- **Internet Information Services (IIS)**
- **osTicket**

---

## **Operating System Used**

- **Windows 10** (21H2)

---

## **Prerequisites**

Before starting, make sure you've completed the [osTicket: Post-Installation Configuration](https://github.com/michael-L2/osticket-postinst/tree/main)!
---

## **Initial Ticket Management**

### **1. Create A Trouble Ticket**
1. We need to pretend we are a customer reporting a problem, so head to **localhost/osTicket/open.php**
2. Select **Open A New Ticket**, and fill out the contact information with that of our previously created User.
3. Set the topic accordingly, and type some realistic fluff in the **Issue Summary**, then **Create Ticket**.
![Ticket](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/2CreatingTicket.png?raw=true)

---

### **2. Sign In As Agent & View Ticket**
(Ignore the typo in the screenshot!)
1. Sign in as your **Agent** with a support role in your **first team**, and click on **Tickets**.
2. Click the only ticket in the queue to view it. We can see the **User**, John Doe, left information regarding the problem.
![Ticket2](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/6Ticket.png?raw=true)
3. We must add an SLA appropriate of the implied severity. Click **Default SLA**, and update the SLA Plan with an appropriate level.
![Ticket3](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/9Ticket.png?raw=true)
4. Our user failed to choose the appropriate Help topic, so change it by clicking **Report A Problem** and updating the Help Topic.
![Ticket4](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/11Ticket.png?raw=true)
5. Assign the Ticket to a the correct team by clicking the text next to **Assigned To**.
![Ticket5](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/14Ticket.png?raw=true)

---

### **3. Working On The Ticket**
1. Sign in as an **Agent** in the team you've assigned the ticket for.
2. Click on the ticket, and **Assign it to yourself** by clicking on the team name in the ticket. Include a reason.
![Ticket6](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/18Ticket.png?raw=true)

---

### **4. Resolving the Ticket**
1. After resolving the issue, close the ticket by **right-clicking** the status, and set it to **Resolved**.
![Ticket7](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/22Ticket.png?raw=true)
![Ticket8](https://github.com/michael-L2/osticket-lifecycle/blob/main/6OsTicketTicketLifecycle/23Ticket.png?raw=true)

---

### **Congratulations!**
You understand how to close and work on a ticket with basic SLAs! Of course, in the real world, you will actually be on a tight schedule to operate on such tickets. Feel free to create more tickets with varying levels of severity, and other help topics. Look into this repositorie's "6OsTicketTicketLifecycle" folder for more examples. 🎉
