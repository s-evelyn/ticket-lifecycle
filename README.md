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

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

**Intake**

- In this step we will act as a user creating a ticket. First we must navigate to the [end user osTicket URL](http://localhost/osTicket/ )
- Then lick on " Open a New Ticket "

    <img width="50%" height ="50%" alt="OPen a new ticket" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/bfe07b7f-9691-49fd-8f32-6c7f43740eee">

- Input an email address and full name.
- Choose a Help Topic that seems most appropriate for the issue, e.g. Business Critical Outage.
- Provide a brief summary of the issue, and enter into the Issue Summary box e.g. Entire Online Banking System is Down
- A user would then provide more details into the issue they summarized e.g. Customers have been calling to say that when they tried to access the online banking platform they are met with 404 error.

    <img width="50%" height ="50%"  alt="Create Ticket stub" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/8bd905ab-59cc-460d-a4ff-08fbe00d5b98">

- Then click "Create Ticket"

-----------------------------------------------------------------------------------------------------------------------

**Assignment and Communication**

- In this stage of the lifecycle of the ticket we will look at the steps an Agent goes through when the ticket has been received and the assignments and communications that take place.
- Log into the osTicket ticketing platform via help desk [login page](http://localhost/osTicket/scp/login.php ) using one the agent you created during the [Post-Install Configuration](https://github.com/s-evelyn/osTicket-PostInstallConfig).

    <img width="50%" height ="50%" alt="sign in with agent worker" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/5b1197fc-cbcc-487d-bfca-56f83cdb3543">

- Observe the ticket that was just created is available for the agent to view. Click on the ticket to start working it.

   <img width="50%" height ="50%" alt="Ticket available" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/e5a3a41e-6a46-4d10-9604-f273f536bc2f">

- Notice that the Priority, Department, SLA and the Assign To section currently do not coorelate with the issue described in the ticket. We are going to continue to update these area.
    - Priority
        - The current priority is set to Normal, given the business critical nature of the event the priority must be changed to match the severity of the issue.
        - Click on Normal to commence the process of changing the priotity.
              
            <img width="50%" height ="50%" alt="Setting priority" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/684efb45-12b7-48a0-9785-d034f0c50e85">

        - Click on the drop down arrow and change the priority to emergency and provide a justification for the change in priority.

             <img width="50%" height ="50%" alt="Update Priority" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/f4347ef2-2dca-4881-becd-476fd2038ee9">

        - Press Update to complete the change in priority.

    - SLA
        - Observe that the current SLA is set to default SLA, this should be changed to reflect the tickets priority.  Click on default SLA, and then update to SEV-A, provide a justification for the change.

            <img width="50%" height ="50%" alt="Update SLA" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/4b1aa609-30af-4959-be0d-1a56e39006a3">

        - Click Update.

    - Assign To
        - Currently there is nobody assigned to the ticket. Click on Unassigned, and select the agent that are logged in as to be the one who works on the ticket.
              
            <img width="50%" height ="50%" alt="Assign to Agent" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/b79b5939-c0b2-4bb1-a50d-62beee5cdf8a">

          - Click Assign to.

    - Department
        - Currently the department for the ticket is set to the Support department. Support would not be the most appropriate department therefore this must be changed. Click on Support to begin updating the department.
        - Set the department to System Administrator.

            <img width="50%" height ="50%" alt="Setting department of ticket" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/bdbb8be3-8237-4bf3-8703-cf13716c93c9">

        - Click Transfer.

- Notice that every change that has been made to the ticket continue to be recorded in a thread.

    <img width="50%" height ="50%" alt="osticket thread" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/4ab09b53-cab8-4cd5-a3c0-35f4296d76d8">

- Observe what the ticket looks like after the updates, by clicking on My Ticket to go back to the list of tickets.

    <img width="50%" height ="50%" alt="Ticket after triaging" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/c9f334fd-50a3-45aa-ad54-79d027a4e4a1">


--------------------------------------------------------------------------------------------------------------------------

**Working the Issue**

- Now that the ticket has been properly assigned it is time to work the issue. The agent chooses to coordinate with the Sys Admin team to bring the online banking back up.
- Make a comment reflecting the choice to further coordinate with the Sys Admin Team. 

    <img width="50%" height ="50%" alt="work ticket" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/ae431564-2672-4e81-bfa7-cd297bfb81c3">


--------------------------------------------------------------------------------------------------------------------------

**Resolution**

- After the issue has been resolved we need to resolve the ticket. The agent who was assigned the ticken will make a comment indicating the source of the problem, and how it was fixed.
  
    <img width="50%" height ="50%" alt="Resolve Ticket" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/a694da1a-a736-4d94-9003-1aba8ca4a9d6">

- Then change the ticket status to resolve and click post reply, ultimately resolving the ticket. Note the ticket is no longer is My Tickets after it has been resolved.

    <img width="50%" height ="50%" alt="Agent ticket area after resolved" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/332beb9f-5b55-4132-b60b-a2ea7886bf40">

- To access resolved tickets click on the Ticket tab and then Closed, which will bring you to the resolved ticket.
  
    <img width="50%" height ="50%" alt="Accessing a closed ticket for review" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/c2651210-261f-422f-a6e2-7f9031599f12">

  
-------------------------------------------------------------------------------------------------------------------------

Congratulations you have successfully run through the lifecycle of a ticket on osTicket!
