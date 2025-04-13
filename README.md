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

![image](https://github.com/user-attachments/assets/c1fd8bfe-507a-492f-8ee6-67e9679c32bd)

<p>
Operating as an end user, we will create a ticket within the support center and circle back around as a technical support representative and edit/fix the issue outlined by the end user, so copy the above information and add your end users support contact info, once finished click "create ticket" at the bottom of the page
</p>
<br />

![image](https://github.com/user-attachments/assets/38ce2fde-e38d-4019-8455-22daca8cbe89)

<p>
Now that the ticket has been created, while logged in as the adminuser, select the ticket created and observe the ticket information
</p>
<br />

![image](https://github.com/user-attachments/assets/cfc61231-b834-4389-bc61-5536f9693459)

<p>
Now we will set the priority to high, assign the ticket to online banking, set the SLA plan to sev-A, and change the help topic to Report a Problem/Business Critical Outage, optionally adding a note in each of the changes as to observe in the ticket thread updates
</p>
<br />

![image](https://github.com/user-attachments/assets/679e1aaa-12eb-4f2c-93b5-155b9ce5fd06)

<p>
Now we want to login as a support user, assign the ticket to ourself, add a note and observe the ticket thread change
</p>
<br />

![image](https://github.com/user-attachments/assets/113ce3d3-4aa1-4e21-a966-5df80ca76336)

<p>
Next, post a reply at the bottom of the ticket page to update the customer on what you believe the problem may be, referencing the picture for help, and observe the change. Beyond this we can pretend we resolved the issue on the back end, post a reply in the notes referring to the fix, observe the fix in the thread. At the top of the ticket page, select the status and change it from open to resolved to close out the ticket
</p>
<br />

![image](https://github.com/user-attachments/assets/68c5f885-3441-42bf-ae81-442b3e115b24)

<p>
Once the ticket is closed you will observe an empty ticket page, tickets may also be closed from this page as well by selecting the ticket and setting the status to resolved or closed
</p>
<br />

![image](https://github.com/user-attachments/assets/c99c9a87-335d-4592-a3ed-ba5f39021820)

<p>
Depending on how your permissions are set up, you may see closed tickets as well. If you log back in as the adminuser, you can select tickets -> closed and view any tickets no longer in the open queue
</p>
<br />

![image](https://github.com/user-attachments/assets/3c86e5ff-c1eb-493f-b9f0-c7bf284b2260)

<p>
Let's create another ticket, use information above and use your desired end user information
</p>
<br />

![image](https://github.com/user-attachments/assets/3a3bc5e0-87a9-47ed-876d-7e3336d0325b)

<p>
I will set this to sev-c priority and assign the ticket to John, but feel free to assign this to whichever user that is desired, make some notes with your changes and observe all changes
</p>
<br />

![image](https://github.com/user-attachments/assets/d9610d4c-50f7-441b-959c-10959abd42b5)

<p>
As it shows above we went through the process of having the customer restart their device and it fixed the issue
</p>
<br />

![image](https://github.com/user-attachments/assets/f5f212b5-5769-455d-93e9-5b0cd37ffc74)

<p>
Before we completely close out the ticket, insert some internal notes by selecting "Post internal Note" and observe the difference in color in the thread, we can do this to communicate with other tech support users about issues pertaining to the issue that we do not wish to involve the end user as it is either not pertinent to them, or the comment could create an angry customer. Either way it is used, I would highly recommend only sharing neccesary information with the customer in documentation.
</p>
<br />

![image](https://github.com/user-attachments/assets/cf05026b-17ed-40d4-a67a-f9ba56b04b9e)

<p>
Once you are finished exploring the notes section, close out the ticket and observe it in the closed ticket section
</p>
<br />

![image](https://github.com/user-attachments/assets/584a0f57-5f78-4cb2-9214-67174d31264b)

<p>
osTicket also allows the tech to create tickets when a problem is discovered or on the behalf of an end user if needed. Under "Tickets" select new ticket and you will be able to play around with different siuations that my arise on the day to day job. Use google or Chatgpt to create prompts and explore permissions of osTicket, it is a very capable open source tool that can be fully exploited for anyone new trying to learn a new skill. We have only scratched the surface in this tutorial, but the best part about this software is, if you break it, you can also fix it by reinstalling it and starting from new. Hope you learned something new!
</p>
<br />
