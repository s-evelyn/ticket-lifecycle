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

- In this step we will outline the process of a ticket being created. First a user would navigate to the [end user osTicket URL](http://localhost/osTicket/ )
- They would then click on Open a New Ticket

    <img width="50%" height ="50%" alt="OPen a new ticket" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/bfe07b7f-9691-49fd-8f32-6c7f43740eee">

- The user would enter their email address and their name.
- They would then choose a Help Topic that seems most appropriate for the issue, e.g. Business Critical Outage.
- They would then put in an Issue Summary, e.g. Entire Online Banking System is Down
- The user would then provide more insight into the aformentioned issue e.g. Customers have been calling to say that when they tried to access the online banking platform they are met with 404 error.

    <img width="50%" height ="50%"  alt="Create Ticket stub" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/8bd905ab-59cc-460d-a4ff-08fbe00d5b98">

- Then Click Create Ticket

-----------------------------------------------------------------------------------------------------------------------

**Assignment and Communication**

- In this stage of the lifecycle of the ticket we will look at the stages an Agent goes through when the ticket has been received and any assignments and communications that need to be made.
- An agent would then log onto the osTicket ticketing platform.

    <img width="50%" height ="50%" alt="sign in with agent worker" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/5b1197fc-cbcc-487d-bfca-56f83cdb3543">

- Observe the ticket that was just created is available for the agent to view. The agent would then click on the ticket to start working it.

   <img width="50%" height ="50%" alt="Ticket available" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/e5a3a41e-6a46-4d10-9604-f273f536bc2f">

- The agent would then look at the ticket and make updates to the priority, department, SLA, as well as assign an agent to the ticket if necessary.
    - Priority
        - The current priority is set to Normal, given the business critical nature of the event the priority will be changes. Click on Normal to commence the process of changing the priotity.
              
            <img width="50%" height ="50%" alt="Setting priority" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/684efb45-12b7-48a0-9785-d034f0c50e85">

        - The priority will be changed to emergency and a justification for the change will be provided.

             <img width="50%" height ="50%" alt="Update Priority" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/f4347ef2-2dca-4881-becd-476fd2038ee9">

        - Press Update to complete the change in priority.

    - SLA
        - Observe that the current SLA is set to default SLA, given to severity of the ticket, it should be changed to reflect the tickets priority. Provide a justification for the change. Click on default SLA, and then update to SEV-A.

            <img width="50%" height ="50%" alt="Update SLA" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/4b1aa609-30af-4959-be0d-1a56e39006a3">

        - Click Update.

    - Assign To
        - Currently there nobody assigned to the ticket. Click on Unassigned, and select the current agent to be the one who works on the ticket.
              
            <img width="365" alt="Assign to Agent" src="https://github.com/s-evelyn/ticket-lifecycle/assets/53543374/b79b5939-c0b2-4bb1-a50d-62beee5cdf8a">

          - Click Update.

    - Department
        - Currently the department for the ticket is set to the Support department. Support would not be the most appropriate department therefore this must be changed. Click on Support to begin updating the department.

             

                


