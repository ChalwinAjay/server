# Overview

## Introduction 
**arc.flow** is a comprehensive workflow management system designed to streamline and optimize task allocation within Access Healthcare. This application efficiently routes work tasks to associates for both production & audit checks based on their individual profiles and predefined rules.
The Workflow and Reporting allow us to map process areas to our client’s practice management system to sequence, queue, track, report, and manage all work queues transferred to Access Healthcare.

**arc.flow** does not replace the client’s practice management/revenue cycle system but complements it by dynamically optimizing and prioritizing workload to deliver to the agreed SLAs.
The purpose of this user manual is to make the transition to the interface and the functionalities of arc.flow easier for the users.

## System Requirements
Before using arc.flow, please ensure that your computer or device meets the following system requirements. These requirements are essential for optimal performance and compatibility with our application.

| System Requirements     | Minimum                                           | Recommended                                       |
| ----------------------- | ------------------------------------------------- | ------------------------------------------------- |
| Operating System        | Windows 8 or macOS 10.12 Sierra and above         | Windows 10 or macOS 11 Big Sur and above           |
| Processor               | Dual-core processor (Intel or AMD)                | Quad-core processor (Intel or AMD)                |
| Memory (RAM)            | 8 GB                                              | 16 GB or more                                     |
| Graphics                | Integrated graphics or dedicated GPU with OpenGL 2.1 support | Dedicated GPU with OpenGL 3.3 support |
| Internet Connection     | Broadband internet connection                    | Broadband internet connection                    |
| Browser Requirements    | Chrome, Firefox, Safari, and Microsoft Edge      | Chrome and Safari                                 |

## Point of contact for arc.flow

| Activity            | Ownership             | Email                            |
| ------------------- | ---------------------- | -------------------------------- |
| Project Leader      | Arun Kumar P           | Arunkumar.p@accesshealthcare.com  |
| Project Management  | Sakkaravarthi K        | Sakkaravarth.k@accesshealthcare.com |


## Support Matrix

| Activity                       | Ownership                | Email                                   |
| -------------------------------| -------------------------| --------------------------------------- |
| L1 Support                     | Support Team             | Arc_Apps_Support@accesshealthcare.com   |
| L1 Support                     | Support Team             | Hanger.arcsupport@accesshealthcare.com  |
| L2 Support                     | Karmegan C               | Karmegan.c2@accesshealthcare.com        |
| L3 Support                     | Arunkumar P              | Arunkumar.p@accesshealthcare.com        |
| L3 Support                     | Udhayaganesh P           | Udhayaganesh.p@accesshealthcare.com     |
| Critical issue escalation      | Sakkaravarthi K          | Sakkaravarth.k@accesshealthcare.com     |


## Accessing arc.flow
**arc.flow** is a web-based application that doesn't require traditional installation. Users can access it directly through a web browser. Here's how to set up and access the application:

1. **Open a Web Browser:** Launch your preferred web browser (e.g., Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge).

2. **Internet Connection:** Ensure you have a stable internet connection to use arc.flow effectively.

3. **Navigate to the Application URL:** In the address bar of your web browser, enter the URL Details provided by your organization or the web address you use to access the application.

4. **New User:**  If you are using the system for the first time, please reach out to your supervisor to initiate the onboarding process as a new user in arc.flow. Once your user details are established, the offshore team (Access Healthcare) will grant you access to arc.flow.

5. **Login Credentials:** The system will verify your credentials using Single Sign-On (SSO) login, which is activated for your company's domain.

6. **Access "arc. flow":** Once you navigate to arc.flow URL, the system will automatically redirect you to your company domain login page. Input your login credentials, and once the system successfully authenticates your access, you will be directed to the home page of arc.flow.

### User Profile and access permissions

After successfully logging in, based on the access rights and roles provided for your profile, you might have different access levels within the application.
Please get in touch with your supervisor if you have questions about your role or permissions.

### Browser Compatibility

**arc.flow** is designed to work with various modern web browsers. For the best experience, we recommend using the latest versions of browsers like Google Chrome and Safari. Ensure your browser is regularly updated to take advantage of new features and security improvements.

### Mobile Access

While arc.flow is primarily designed for web browsers, it does not support mobile access.

## Roles and definition in arc.flow

| Role Name                         | Definition                                                                                                 |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Application Administrator         | Application administrators oversee system setup, user management, security, training, and maintenance to ensure smooth workflow operations |
| Manager/Team Leader/Director      | Configure basic setup to use the application, new user onboarding, create team workflows, set targets, assign tasks, monitor progress, and ensure timely completion. |
| Entry User                        | Production users execute tasks within workflows, follow instructions, provide feedback, and help achieve workflow goals. |
| Audit User                        | Audit users review and verify workflows, ensure compliance, and maintain data accuracy through inspections. |
| Management                        | Management oversees strategy, resources, and overall performance using reports and analytics to drive workflow efficiency and achieve organizational goals. |

## Getting Started

In this section, we'll guide you through the essential steps to get started with Arc. Flow. Whether you are a new user or returning after a break, this section will help you set up your account, understand the user interface, and ensure a smooth onboarding experience.

### Setup
**Description:**

The Setup feature in arc. flow is essential for configuring and customizing the system according to your organization's needs. It involves defining user roles, permissions, workflow templates, and other settings to optimize the system's functionality.

**Benefits:**

• Tailor the system to your organization's unique workflow requirements.

• Enhance security and control by managing user access and permissions.

• Streamline processes by creating standardized workflow templates.

**Common Issues:**
1. Incorrectly configured user permissions, leading to access issues.

2. Mapping incorrect values in the master setup will result in inaccurate outputs within the arc.flow.

**How to access the setup menu?**

To access the setup, the user must click on the .setup tile.

![setup](/img/arflow/arc-setup.png)

### How to set up a user in arc.flow?

**Description:**

The "User Master Screen" feature in the arc.flow will be enabled by offshore team based on the request raised by onshore team. Once the module is completed, we will add the detailed explanation in this section.


### How to create a Sub-client group?

**Description:**

The “Sub client Group” Management feature within the arc.flow allows users to create and configure Sub-client groups. Sub-client groups are used to organize clients and set targets for work allocation. Users can attach a list of Sub-clients to these groups, and each Sub-client can belong to one or multiple Sub-client groups. Additionally, users can define "Target" and "Allocation per pull" settings for each Sub-client group.

**How to access?**

To access the Group of Sub-clients, the user must click on .setup>Allocation setup>Group of Sub-clients. 

**Step-by-step process:**

![subclientgroup](/img/arflow/subclientgroup.png)

**Enter the "Sub-client Group Name":**

• Enter a unique and descriptive name for the Sub-client Group in the provided text field. Ensure that the name is meaningful and distinctive.

**Select a Service:**

• Choose one of the services from the dropdown list. The available options depend on the service mapped for the specific client.

**Set Production Target:**

• Enter the production target for each user assigned to the Sub-client Group. This represents the amount of work expected from each user.

**Allocate Claims per Pull:**

• Specify the number of claims allocated to users per "pull" or "Pull tickets" within their inbox. This determines the workload distribution.

**Select Clients:**

• Use the "Client list box" on the left side to select the clients that will be associated with this Sub-client Group.

**Drag and Drop Clients:**

• After selecting the clients, drag and drop them to the right side, indicating that they are part of this Sub-client Group.

**Save the Configuration:**

• To confirm and save the Sub-client Group configuration, click the "Submit" button. The details will be saved, and the newly created group will be displayed in a grid format.

### How to create a user group?

**Description:**

The "User Group" feature in the arc.flow enables users to associate individual users under sub-client groups. These user groups, often called "teams," provide a structured way to align users with specific clients or services, facilitating efficient workflow management.

**How to access?**

To access the User Group master, the user must click on .setup>Allocation Setup>User Group Master. 

**Step-by-step process:**

![usergroup](/img/arflow/usergroupmaster.png)

**Enter the "User Group Name":**

• Start by entering a unique and descriptive name for the User Group in the provided text field. Ensure the name is meaningful and easily distinguishable.

**Select a Sub-client:**

• Choose one of the Sub-clients from the dropdown list. The available options depend on the Sub-client mapped for the specific client.

**Add Users to the User Group:**

• Select the users you want to include from the list of available users in the User Group.

**Drag and Drop Users:**

• After selecting the users, drag and drop them to the right side, indicating that they are part of this User Group.

**Save the Configuration:**

• To confirm and save the User Group Master configuration, click the "Submit" button. The details will be saved, and the newly created User Group will be displayed in a grid format.

### How do you create a Queue-based allocation?

**Description:**

The "Queue Master" is a feature in the arc.flow allows for the creation of queue-based allocation of claims to users' inboxes. This feature helps the team to create the distribution of tasks, shares, or work items among users based on predefined queues, ensuring equitable and efficient task assignment.

**How to access?**

To access the Queue master, the user must click on .setup>Allocation Setup>Queue Master. 

**Step-by-step process:**

![queuemaster](/img/arflow/queuemaster.png)

**Enter the "Queue Name":**

• Start by entering a descriptive name for the Queue in the provided text field. This name should identify the purpose or characteristics of the Queue.

**Select a "Display Column":**

• Choose a column to display from the dropdown menu. The available options in the dropdown are based on the flat file setup done for the user. Note that flat file setup is handled from the backend.

**Choose an "Item Condition":**

• Select an item condition from the dropdown. Item conditions are typically hardcoded and include operators such as “! =" (not equal to), "<" (less than), or ">" (greater than).

| Item condition                    | Description                                                                                                 |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| != ( Not Equal to)	            | This condition can be used when the values in the display column (For e.g., Created date) dropdown does not equal to the value in Filter value dropdown.
| < (Less than)		            | This condition can be used when the values in the display column (For e.g., Created date) dropdown less than to the value in Filter value dropdown.
| <= (Less than Equal to)	    | This condition can be used when the values in the display column (For e.g., Created date) dropdown less than equal to the value in Filter value dropdown.
| = (Equal to)		            | This condition can be used when the values in the display column (For e.g., Created date) dropdown equal to the value in Filter value dropdown.
| > (Greater than)	            | This condition can be used when the values in the display column (For e.g., Created date) dropdown greater than the value in Filter value dropdown.
| >= (Greater than Equal to)	    | This condition can be used when the values in the display column (For e.g., Created date) dropdown greater than equal to the value in Filter value dropdown.
| Begins with		            | This condition can be used when the values in the display column (For e.g., shift) dropdown begins with the value in Filter value dropdown.
| End with		            | This condition can be used when the values in the display column (For e.g., shift) dropdown ends with the value in Filter value dropdown.
| Contains		            | This condition can be used when the values in the display column (For e.g., shift) dropdown contains the value in Filter value dropdown.
| Does not contain		    | This condition can be used when the values in the display column (For e.g., shift) dropdown does not contains the value in Filter value dropdown.

**Select a "Filter Value":**

• Choose a filter value from the dropdown list. These values are typically based on the flat file uploaded by the user.

**Set the "Queue Condition":**

• Select the appropriate queue condition from the dropdown. Options often include "And," "Or," and "Not." This condition dictates how sequential requirements are applied.

**Apply the Filter:**

• Click on the "Apply Filter" button to create the sequential conditions. The configured Queue Master will be displayed in grid form.

**Search Using the Filter Box:**

• To locate specific values within the grid, use the filter box to search and filter the displayed data based on your criteria.

### How do you prioritize work allocation?

**Description:**

The "Priority Setup" feature is vital in the arc.flow allows users to override queue-based claim allocation. Supervisors can set priorities for claims daily (Change if required), enabling the selection and completion of claims before others based on predefined conditions. 

**How to access?**

To access the priority setup, the user must click on .setup>Allocation setup>Priority setup.

**Step-by-step process:**

![Prioritysetup](/img/arflow/prioritysetup.png)

**Select a Sub-client Group:**

• Choose a Sub-client group from the dropdown. The options in the dropdown are based on the setup in "Group of Sub-client." Upon selecting a Sub-client group, the system will default display the user group list.

**Add Queues to Priority:**

• Drag and drop the desired "Queue list" to establish the priority setup for this Sub-client group.
Save the Priority Setup:

• To create the priority setup, click the "Submit" button. The configured priority setup will be displayed in grid form.
Edit or Delete Priority Setup:

• To change an existing priority setup, click the "Edit" button. Alternatively, click the "Delete" button to remove the priority setup data. Exercise caution when deleting configurations, as this action is permanent.

### How do you set up the ramp configuration?

**Description:**

The "Ramp-up Setup Screen" is a feature in the arc.flow facilitates the configuration of production targets based on the tenure of an associate. This feature empowers organizations to set gradual or customized production goals for associates as they gain experience. The target for the freshers will be calculated based on this setup.

**How to access?**

To access the Ramp-up setup, the user must click on .setup>Ramp-up setup. 

**Step-by-step process:**

![Rampsetup](/img/arflow/rampupsetup.png)

**Creating a Ramp-up Name:**

• Click on the "Add" button (near the Ramp-up Name):

• Begin by clicking the "Add" button to create a new Ramp Name.

![Rampup](/img/arflow/rampuppopup.png)

• Once in the creation screen, enter a name for the Ramp-up in the provided text field.

**Select "Experience" from the Dropdown:**

• Choose the experience level from the dropdown. Options include "Experienced," "Fresher," and "Tenured." Each experience level corresponds to different types of associates within the production.

**Select "Request Type" from the Dropdown:**

• Choose the request type from the dropdown. Options include "Entry," indicating that the Ramp-up is intended for entry-level associates.

**Save the Ramp-up Name:**

• Click on the "Submit" button to save the details.

**System Auto populate Ramp-up Information:**

• Note that the system will automatically populate the Ramp-up Name, User Type, and Process Type fields based on the selection in the "Ramp-up Name" dropdown.

**Creating Ramp-up Details:**

• Click on the "Add" button (Ramp-up Detail Section):

• Click the "Add" button to add details for a specific week within the Ramp-up Name.

![Ramppagesetup](/img/arflow/rampagesetup.png)

**Enter Week Details:**

• Enter the "week Name."

• Specify the "From" day target.

• Specify the "To" day target.

• Enter the "%" target.

• Drag and drop the "Sub-client group list."

**Save the Ramp-up Setup:**

• To create the Ramp-up setup for the specified week, click the "Submit" button. The setup is created with the details provided.

**Note:** Creating and configuring at least one Ramp-up for a Sub-client group in the fresher category is mandatory.

### How do you create Issue codes?

**Description:**

The "Issue Code Master" is a feature in the arc.flow assists in updating issue codes with mappings to distinguish between callable and non-callable claims. This feature enhances claim processing by categorizing claims based on call type.

**How to access?**

To access the Issue code master, the user must click on .setup>Issue code setup>Issue Code Master. 

**Step-by-step process:**

![Issuecode](/img/arflow/issuecodestatuscodemaster.png)

**Click on the "Add" button:**

• Start by clicking the "Add" button to initiate the creation of an Issue Code Master.

![Issuecodemaster](/img/arflow/issuecodemaster.png)

**Enter the "Name":**

• In the creation screen, enter a name for the Issue Code in the provided text field.

**Select "Type" from the Dropdown:**

•Choose the type of Issue Code from the dropdown. Options include "Callable" or "Non-Callable."

**Save the Issue Code Master:**

• To create the Issue Code Master, click the "OK" button. The created Issue Code Master will be displayed in grid form.

**Edit or Delete Issue Code Master:**

• To change an existing Issue Code Master, click the "Edit" button. Alternatively, click the "Delete" button to remove the Issue Code Master data. Exercise caution when deleting, as this action is permanent.

**Search Using the Filter Box:**

• To search for specific Issue Codes within the grid, use the filter box to locate and filter the displayed data based on your criteria.

### How to create an audit error parameter?

**Description:**

The "Audit Error parameter/master" feature within the arc.flow enables users to create a hierarchical structure of error details. This structure defines parent and child error relationships while specifying the weightage and criticality of each error. It is designed to streamline the auditing and error resolution processes.

**How to access?**

To access the Audit Error Master, the user must click on .setup>Issue code setup>Audit Error Master. 

**Step-by-step process:**

![newparentname](/img/arflow/newparenterrorname.png)

**Creating a New Parent Error Name:**

**Click on the "Add Parent Name" Button:**

• Begin by clicking the "Add Parent Name" button to create a new Parent Error Name.

![auditerrormaster](/img/arflow/auditerrormaster.png)

**Enter the "New Parent Error Name" in the Popup:**

• After clicking the button, a popup or dialog box will appear, allowing you to provide the necessary details for the new Parent Error Name.

• Enter the "New Parent Error Name" in the designated field within the popup.

**Save the Parent Error Name:**

• Click the "Save" button in the popup to save the new Parent Error Name details.

**Creating an Audit Error Master Name:**

**Click on the "New" Button:**

• To create a new Audit Error Master Name, click the "New" button.

![auditerrormaster2](/img/arflow/auditerrormaster2.png)

**Enter the Name of the Error in the Popup:**

• A new popup will appear for creating the Audit Error Master Name. Enter the "Name" of the error in the designated field within this popup.

**Select the "Parent Name" from the Dropdown:**

Choose the "Parent Name" from the dropdown. The available options in the dropdown are based on the Parent Error Names created.

**Enter the "Weightage" for the Error:**

• Provide the "Weightage" for the error in the appropriate field within the popup.

**Select the "Error" as Critical or Not Critical:**

• From the dropdown, select whether the error is "critical" or "not critical." Options include "Yes" and "No."

**Create the Audit Error Master:**

• Click the "OK" button within the popup to create the Audit Error Master. The created Audit Error Master will be displayed in the grid form.

**Editing and Deleting Audit Error Masters:**

**Edit or Delete Audit Error Masters:**

• To change an existing Audit Error Master, click the "Edit" button. Alternatively, click the "Delete" button to remove the Audit Error Master data. Exercise caution when deleting, as this action is permanent.

**Searching Using the Filter Box:**

• To find specific Audit Error Masters within the grid, use the filter box to search and filter the displayed data based on your criteria.

### How do you set up audit% configuration?

**Description:**

The "Audit% Configuration" feature is designed to ensure compliance with agreed audit sampling as per Service Level Agreements (SLAs) in alignment with the Quality Standard Operating Procedure (SOP). This feature enables the random selection and assignment of audit samples from the production file in .flow.

**How to access?**

To access the Audit% configuration, the user must click on .setup>Audit setup>Audit Configure.

**Step-by-step process:**

![auditsetup](/img/arflow/auditsetup.png)

Please choose the most suitable audit setup option based on their specific requirements and the customization level needed in the audit process.

**Overall Audit:**
• Choose an "Overall" audit setup for a uniform approach.

• Applies a sampling percentage across the entire sub-client group.

• Ensures consistency in the audit process.

![auditsetup1](/img/arflow/auditsetup1.png)

**Select Sub-Client Group:**

• From the dropdown menu, select the specific Sub Client Group for which you wish to configure the audit setup.

**Select Audit Type:**

• Among the radio button options given, select the preferred Audit Type.

**Save the Configuration:**

• Click the "Save" button to save the audit setup details.

**Note:** This audit setup feature is designed to help assign the necessary sampling percentage for the selected sub-client group. The sampling percentage varies based on the Line of Business (LOB) and the specific sub-client group, all in alignment with the Service Level Agreement (SLA) requirements.

**As an example:**

If the number of tasks processed is 500, and the Audit Percentage (Audit %) is set at 5%, 5% of the tasks will be subject to audit.

This results in 25 tasks being randomly selected for audit from the sub-client group associated with a client Partner.

**Custom Audit:**

• Opt for a "Custom" audit setup to tailor the sampling process.

• Empower users to customize the audit approach to meet internal quality standards and training needs.

• Allows fine-grained control, including specifying criteria like Sub Client Group, Kick code, and Audit Percentage.

![auditsetup2](/img/arflow/auditsetup2.png)

**Select Sub-Client Group:**

• Choose the Sub Client Group for which you are configuring the audit setup from the dropdown menu.

**Select Type:**

• Select the Type from the dropdown menu which may pertain to a specific category or criteria for the audit setup.

**Select Issue Code:**

• Choose the relevant Issue Code from the dropdown menu. This specifies the type of issues or errors to be audited.

**Update Audit Percentage:**

• Adjust the Audit Percentage as needed. This percentage indicates the portion of tasks or items that will undergo audit within the specified criteria.

**Update Comments (if required):**

• If necessary, provide additional comments or notes related to the audit setup.

**Save the Configuration:**

• To confirm the audit setup, click the "Submit" button to save the details.

**Note:** The selection of samples for the specific issue codes will be conducted per the master setup established by the SQ Lead/Manager in the screen mentioned earlier.

**Client Partner Audit:**

• Select "Client Partner" audit setup to create customized samples for individual Client Partners.

• Ideal for accommodating Client Partner-specific sampling requirements, whether they are new or experienced in their role.

• Enables a more personalized approach to audits based on unique needs.

![auditsetup3](/img/arflow/auditsetup3.png)

**Select Sub-Client Group:**

• Choose the Sub Client Group from the dropdown. This action should help you list the Client Partner names, as shown in the screenshot.

**Select a Preferred Client Partner:**

• From the listed Client Partner names, select your preferred Client Partner.

**Change the Sample Percentage:**

• Adjust the sample percentage according to your specific requirements. You can change this percentage to align with your desired sampling strategy.

**Save the Details:**

• To confirm the changes, click the "Save" button. This will save the updated sample percentage and configuration.

## How do I process assigned work or claims in arc.flow?

**Description:**

The "Inbox Module" is a pivotal component within the arc.flow, providing users with a dedicated workspace for updating the details of claims allocated for production. This module enhances the efficiency and accuracy of claims processing.

**How to access?**

To access the inbox, the user must click on .inbox. 

**Step-by-step process:**

![Inbox](/img/arflow/inbox.png)

**Click on the Claim Type:**

• Begin by clicking on the claim type, which initiates the update process for production details. This action opens the "Process Claim" popup.

![Inboxpopup](/img/arflow/inboxpopup.png)

**Select the Call Type:**

**From the dropdown menu, choose the "Call Type." Options include "Callable," "Non-Callable," and "Review," each with specific implications:**

• If "Callable" is selected, claims details must be discussed with insurance companies through a call for resolution.

• If "Non-Callable" is selected, claims details will not involve a call; resolution will happen through documentation.

•  If "Review" is selected, claims details can be resolved by call or documentation.

**Select the Issue Code:**

• From the dropdown, choose "Issue Code." The available options should be based on the issue code master setup for the clients in the "Issue Code Master" section.

**Select "Move to Actions" from the Dropdown:**

• Choose an action from the dropdown, such as "Move to Issue Log," "Move to Appeal," or "Move to Coding."

**Select "Issue Log" Option:**

• If " Move to Issue Log " is selected, the claims will be moved to the IssueLog bucket.

• Select the “Issue log” type and “Description.”

**Select "Appeal" Option:**

• If " Move to Appeal " is selected, the claims will be moved to the Appeal bucket.

**Select "Move to Coding" Option:**

• If " Move to coding " is selected, the claims will be moved to the coding bucket.

**Select "Future Follow-Up" Option:**

• Based on the Issue code/Action code review days configuration, the system automatically moves to the future follow-up.

**Enter "Call Notes":**

• In the provided text box, enter "Call Notes.”

**Choose an Action:**

**Depending on the status or action needed for the claim, click on one of the following buttons:**

• "Submit" if the claims are completed.

• "Hold" if the claims are to be put on hold.

• "Save" if the claims are to be reworked earlier.

• Viewing Claim Information in the Grid:

**Claim Information Display:**

• After the appropriate action, the claim information will be displayed in a grid.

![Inboxpopup](/img/arflow/inboxpopup2.png)
 
**Search Using Filter Box:**

• To search for specific claim values within the grid, use the filter box to apply filtering conditions and search for the desired information.

## How do I access my completed work or claims allocated to me in arc.flow?

** Description:** 

The ".Complete Module" is a core component of the arc. flow empowers users to access, and review completed production details. In addition to viewing the finalized work, this module offers the flexibility to make necessary modifications or updates to production records, ensuring data accuracy and quality control.

** How to access?** 

To access the .completed tile, the user must click on .completed. 

** Step-by-step process:** 

![Completed](/img/arflow/completed.png)

![Completed1](/img/arflow/completed1.png)

**Select "Start Date" and "End Date":**

• Choose the "Start Date" and "End Date" from the calendar picker to define the time frame for which you want to view production details.

**Submit to Load Completed Production Details:**

• Click the "Submit" button to load the completed production details within the specified date range.

**Click on the Claim Type:**

• Click on the claim type to modify the production details for a specific claim type. This action opens the "Modify Claim" popup for data entry.

![Completed2](/img/arflow/completed2.png)

**Select the Call Type:**

**From the dropdown menu, choose the "Call Type." Options include "Callable," "Non-Callable," and "Review," each with specific implications:**

• If "Callable" is selected, claims details must be discussed with insurance companies through a call for resolution.

• If "Non-Callable" is selected, claims details will not involve a call; resolution will happen through documentation.

• If "Review" is selected, claims details can be resolved by call or documentation.

**Select the Issue Code:**

• From the dropdown, choose "Issue Code." The available options should be based on the issue code master setup for the clients in the "Issue Code Master" section.

**Select "Issue Log" Option:**

**Choose between "Yes" and "No" for the "Issue Log" option:**

• If "Yes" is selected, the claims will be moved to the IssueLog bucket.

• If "No" is selected, the claims will not be transferred to the IssueLog bucket.

**Select "Appeal" Option:**

**Choose between "Yes" and "No" for the "Appeal" option:**

• If "Yes" is selected, the claims will be moved to the appeal bucket.

• If "No" is set, the claims will not be transferred to the appeal bucket.

**Select "Move to Coding" Option:**

**Choose between "Yes" and "No" for the "Move to Coding" option:**

• If "Yes" is selected, the claims will be moved to the coding bucket.

• If "No" is selected, the claims will not be transferred to the coding bucket.

**Select "Future Follow-Up" Option:**

**Choose between "Yes" and "No" for the "Future Follow-Up" option:**

• If "Yes" is selected, the date picker should enable users to choose a follow-up date.

• If "No" is selected, the date picker should be disabled, preventing users from choosing a follow-up date.

**Enter "Call Notes":**

• In the provided text box, enter "Call Notes" as needed.

**Choose an Action:**

**Depending on the status or action needed for the claim, click on one of the following buttons:**

• "Submit" if the claims are completed.

• "Hold" if the claims are to be put on hold.

• "Save" if the claims are to be reworked earlier.

**Viewing Claim Information in the Grid:**

• After the appropriate action, the claim information will be displayed in a grid.

![Completed3](/img/arflow/completed3.png)

## How do I audit a completed claim/Work?

**Description:**

The "Audit Inbox Screen" is a central component within arc.flow, providing audit users with a dedicated workspace to review and assess production tickets completed by production agents. Audit users can thoroughly examine each claim and mark errors or discrepancies as part of the auditing process. The audit allocation will be based on the audit configuration (Overall, custom, and User) done by the supervisor as mentioned in the Audit configuration. 

**How to access?**

To access the Audit Inbox, the user must click on .audit inbox. 

**Step-by-step process:**

![auditinbox](/img/arflow/inbox.png)

![auditinbox](/img/arflow/auditinbox1.png)

**Click on the Claim Number:**

• The Auditor should click on the claim number to update audit details. This action opens the "Audit Call Sheet" popup for capturing audit details.

![auditinbox](/img/arflow/auditinbox2.png)

**View Ticket Information in Grid Format:**

• Inside the "Audit Call Sheet" popup, the Auditor can view ticket information in a grid format.

**View Claim Details:**

• If needed, the Auditor can click the "Claim Details" button to view additional information about the claims the production user updates.

**Select "Error Parameters" from Dropdown:**

**Choose between "Yes" and "No" from the "Error Parameters" dropdown. This will be based on the controller configuration. The options and actions vary as follows:**

• If "Yes" is selected, the error is marked against an "Error Name," and the Auditor should enter "Error Comments" in the provided text box.

• If "No" is selected, the date picker must not be enabled for user selection.

**Enter "QC Notes":**

• As needed, the Auditor should enter "QC Notes" in the provided text box.

**Select "Re-work" Option:**

• If the claims need to be reworked by the production user, the Auditor can select the "Re-work" option.

**View Processing Time:**

• The Auditor can view how much time they have taken to process a claim by checking the process’s start date and time.

**Complete and Save Error Details:**

• To save the error details and complete the audit, the Auditor should click the "Complete" button.

**Close the "Audit Call Sheet" Popup:**

• Once the audit is complete and the details are saved, the Auditor can click the "Close" button to close the "Audit Call Sheet" window.

##  How do I acknowledge my audit feedback?

**Description:**

The "Audit Feedback Screen" in arc.flow facilitates communication and collaboration between auditors and claim processors. It allows claim processors to acknowledge errors or discrepancies identified by auditors during the audit process.

**How to access?**

The user must click the .inbox>Audit Feedback popup to access the Audit feedback. 

**Step-by-step process:**

![auditinbox](/img/arflow/auditfeedback.png)

**Select the Start Date and End Date:**

• Use the calendar picker to select the "Start Date" and "End Date" to specify the date range for your search.

**Click on "Search":**

• After setting the date range, click the "Search" button to view auditor feedback for a specific ticket number.

**Select an "Action" Option:**

• Choose from the available options "Accept" or "Reject." These options determine the action you want to take regarding the feedback.

**Accept Action:**

• If you select "Accept" and click the "Save" button, the user accepts the error. As a result, the "Status" must be changed to "Accepted."

**Reject Action:**

• If you select "Reject" and click the "Save" button, the user rejects the error. The "Status" must be changed to "Verification." Additionally, it's mandatory to provide comments when the action is selected as "Rejected."

**Navigate Between Pages:**

• To move between different pages of auditor feedback, click on the "page number" for navigation.

**Select "Page Size" in the Dropdown:**

• Use the dropdown menu to choose the "Page Size." This allows you to determine the number of records displayed on each page.

**Search Using the Filter Box:**

• Use the filter box to find specific feedback or apply additional filtering conditions. This feature allows you to search for and refine your view of auditory feedback.

## How do I assign or reassign work/ claims to a production user?

**Description:**

The "Allocate Module" is an integral part of the arc.flow empowers team leaders to manage the priority of claims efficiently. Team leaders have the authority to allocate, reallocate, hold, and release tickets, ensuring optimal resource allocation and workflow efficiency.

**How to access?**

To access the .allocate, the user must click on .allocate. 

**Step-by-step process:**

![allocate](/img/arflow/inbox.png)

Below listed are the parts of the .allocate module.

• Manual Allocation.

• Release Tickets.

• Re-allocate Tickets.

• Re-allocate QC Tickets.

• Remove Tickets.

## How can I manually assign a work/claim to a production user?

**Description:**

The "Manual Allocation Screen" is an essential component within the arc.flow grants Team leaders the ability to manually allocate tickets or tasks to specific agents or team members. This feature will be used according to the client's priority for claims. The manual allocation will be assigned to the production user, and the claims are already auto-allocated.

This enables precise and controlled allocation to ensure the correct agent handles specific work items based on claim priorities.

**How to access?**

The user must click on .allocate>Manual allocation to access the manual allocation. 

**Step-by-step process:**

![manualallocation](/img/arflow/queuefilter.png)

**Select a Sub-client from the Dropdown:**

• Choose one of the Sub clients from the dropdown. The available options are based on the sub-clients mapped for that client.

**Select a Production User:**

• Choose one of the production users listed in the system.

**Create a "Queue Filter":**

**To create a queue filter, follow these sub-steps:**

**Select the "Display Column" from the Dropdown:**

• Choose a column for display from the dropdown menu. The available options should be based on the flat file setup done for the user.

**Select the "Item Condition":**

• Choose an item condition from the dropdown. Item conditions may include operators such as "!=" (not equal), "<" (less than), or ">" (greater than).

**Select the "Filter Value":**

• Choose a filter value from the dropdown menu. The values should be based on the flat file uploaded by the user.

**Select the "Queue Condition":**

• Choose a queue condition from the dropdown. Queue conditions may include "And," "Or," and "End."

**Apply the Filter:**

• Click the "Apply Filter" button to load the ticket details based on the filter criteria.

•After applying the filter, select the tickets you want to allocate to a specific user.

**Click "Allocate" Button:**

• Click the "Allocate" button to allocate the selected tickets to the chosen user.

**Add a Queue Filter:**

• If you need to create additional queue filters, click the "Add" button in the "Create Queue Filter" section to define new filters.

**Delete a Queue Filter:**

• To remove a queue filter, click the "Delete" button to delete the filter details.

**Navigate Between Pages:**

• To move between different pages of ticket details, click on the "page number" for navigation.

**Select "Page Size" in the Dropdown:**

• Use the dropdown menu to choose the "Page Size," determining the number of records displayed on each page.

**Search Using the Filter Box:**

• For more specific filtering or search requirements, use the filter box to refine your view of ticket details. You can apply various conditions to your search.

## How do I release a work/claim from a production user?

**Description:**

The "Release Allocation Screen" is a crucial element of the arc.flow allows users to release tickets or tasks initially assigned to a production user. This feature provides the flexibility to remove work items.

**How to access?**

The user must click on .allocate>Release allocation to access the release allocation. 

**Step-by-step process:**

![releaseallocation](/img/arflow/releaseallocation.png)

**Select Start and End Date:**

Choose the start date and end date using the calendar selector to specify the date range for your search.

**Select Sub-client from Dropdown:**

• Choose a Sub-client from the dropdown. The available options are based on the Sub-client mapping for that client.

**Click "Submit":**

• Click the "Submit" button to view the ticket details based on your selected date range and Sub-client.

**Select Tickets to Release:**

• Select the tickets you want to release from their current assignment to the production user from the list of displayed tickets.

**Click "Release Tickets" Button:**

• After selecting the tickets, click on the "Release Tickets" button to release the chosen tickets that were previously allocated to the production user.

**Search and Filter:**

• Utilize the filter box to search and filter the ticket values according to your specific criteria. You can apply various filter conditions to refine your search.

## How do I re-assign a work/claim in arc.flow?

**Description:**

The "Reallocation Screen" is a vital component in arc.flow system empowers team leaders to reassign tickets or tasks to a new production user. This feature is valuable for ensuring that work items are assigned to the most appropriate team members or agents based on changes in workload, priorities, or expertise.

**How to access?**

To access the re-allocation, the user must click on .allocate> Reallocation.

**Step-by-step process:**

![reallocation](/img/arflow/releaseallocation1.png)

**Select Start and End Date:**

• Use the calendar picker to select the start and end dates to specify the date range.

**Select Sub-client Group from Dropdown:**

• Choose a Sub-client Group from the dropdown. The available options are based on the sub-clients mapped for that client.

**Select User in the "Allocated To" Dropdown:**

• Choose one of the users from the "Allocated To" dropdown. The options are based on the users tagged for that client.

**Click "Search" Button:**

• Click the "Search" button to view the ticket details based on your selected date range, Sub-client Group, and user.

**Select Tickets to Reallocate:**

• Select the tickets you want to reallocate from the displayed list of tickets to a new user.

**Click "Re-Allocate" Tickets:**

• After selecting the tickets, click the "Re-Allocate" button to assign the chosen tickets to a new user.

**Export to XLS:**

• Click the "Export to XLS" button to export the displayed information to an Excel file.

**Back to Main Page:**

• Use the "Back" button to return to the main page.

**Navigate Between Pages:**

• Click on the "page number" to navigate between different pages of ticket details.

**Select "Page Size" in Dropdown:**

• Use the dropdown menu to choose the "Page Size," specifying the number of records displayed on each page.

**Search Using the Filter Box:**

• Utilize the filter box to search and filter ticket values according to your specific criteria. You can apply various filter conditions for refining your search.

## How can I review the issue log claims in arc.flow?

**Description:**

The "Issue Log" feature is an integral part of the arc.flow designed to facilitate the review and escalation of claims to be reviewed with the client/Supervisor for further information ("Move to issue log claims by the production user). This feature ensures that claims requiring additional scrutiny or client user intervention are appropriately handled.

**How to access?**

To access the .issue log, the user must click on .issue log. 

**Step-by-step process:**

![issuelog](/img/arflow/inbox.png)

![issuelog](/img/arflow/issuelog.png)

**Expand Claim Details:**

• Expand the claim details where the Associate notes are displayed to update the Issue Log Notes.

![issuelog](/img/arflow/issuelog1.png)

**Enter Issue Log Notes:**

• Enter the Issue Log Notes in the provided text box in the expanded view.

**Move to AR:**

• Click the "Move to AR" button to send the claim back to the production user's inbox for re-processing.

**Export to XLS:**

• Click the "Export to XLS" button to export the information to an Excel file.

**Navigate Between Pages:**

• Click on the "page number" to navigate between different pages of claim details.

**Select "Page Size" in Dropdown:**

• Use the dropdown menu to choose the "Page Size," specifying the number of records displayed on each page.

**Search Using the Filter Box:**

• Utilize the filter box to search and filter claim values according to your specific criteria. You can apply various filter conditions for refining your search.

## How do I access multi-touch work/claims?

**Description:**

The "Multi-Touch Screen" is a crucial feature within the arc.flow system allows users to view and provide feedback on claims that have undergone multiple processing (More than two times process for completed claims) iterations and are categorized in the "Multi-Touch Bucket." This feature enhances the accuracy and quality of claim processing.

**How to access?**

To access the .multi touch, the user must click on .multi touch.

**Step-by-step process:**

![multitouch](/img/arflow/inbox.png)

![multitouch](/img/arflow/multitouch.png)

**Select Sub-client:**

• Choose a Sub-client from the dropdown. The available options are based on the sub-clients mapped for that client.

**Select User:**

• Choose a user from the dropdown. The options are based on the users tagged for that client.

**Allocate Tickets:**

• Select the list of tickets and use the "Allocate" button to assign them to the chosen user.

**View Ticket Log:**

• Click on the "Ticket Information" button to access the ticket log. The log details are displayed in a "Ticket Details" popup.

**Add Client Feedback:**

• Click on the "Client Feedback" button to provide client feedback for the ticket. The system opens a "Client Feedback" popup where you can enter the input in a text box.

**Submit Client Feedback:**

•  Click the "Submit" button in the "Client Feedback" popup to save the provided feedback.

**Export to XLS:**

• Click the "Export to XLS" button to export information to an Excel file.

**Pull New Claims:**

• Click the "Pull Ticket" button to retrieve new claims for audit.

**Search and Filter:**

• Utilize the filter box to search and filter values in the grid according to specific criteria. You can apply various filter conditions to refine your search.

## Rebuttal process

**Description:**

The "Rebuttal Process" is a procedure within the arc.flow allows users, typically in a dispute or review scenario, to respond to or challenge decisions, feedback, or claims made by auditors or quality assurance personnel.

What are the steps involved in the rebuttal process:

**1.Entry users receive audit feedback from the auditor.**

**2.Entry user accepts or rejects audit feedback:**

• The record moves to the team leader bucket for review if accepted or rejected.

**3.The team leader reviews the feedback and accepts or rejects it:**

• If accepted, the record moves to the QC User queue.

• If rejected, the quality score remains the same, and the workflow ends.

**4.Audit user reviews the feedback and accepts or rejects the rebut:**

•  If accepted, the record moves to the Audit Supervisor queue.

• If rejected, the workflow ends.

**5.The Audit Supervisor reviews the dispute and accepts or rejects it:**

• If received, a new quality score is generated, and the workflow ends.

• If rejected, the Audit Supervisor sends justification to both the Entry Supervisor and the training team.

**6.The entry Supervisor reviews the justification and accepts or rejects it:**

• The original quality score is retained if accepted, and the workflow ends.

• If rejected, the record moves to the Training team for their input.

**7.The Training team reviews the input and accepts or rejects it:**

• The original quality score is retained if accepted, and the workflow ends.

• The record is sent to the Audit Supervisor queue for review if rejected.

**8.The Audit Supervisor reviews the Team Leader's review and accepts or rejects it:**

• If accepted, a new quality score is generated by sending the record back to the Audit user bucket, and the workflow ends.

• The record is sent to the Quality Manager queue for review if rejected.

**9.Quality Manager reviews the dispute and accepts or rejects it:**

• If accepted, a new quality score is generated by sending the record back to the Audit user bucket, and the workflow ends.

• The original quality score is retained if rejected, and the workflow ends.

### How do I dispute audit feedback as a production user?

**How to access?**

To rebut audit feedback, the user must click on.Inbox

![multitouch](/img/arflow/inbox.png)

![auditdispute](/img/arflow/auditdispute.png)

• After viewing the audit feedback, select "Accept" or “Review” the feedback.

• Click the appropriate action button.

• The system will record your acceptance of the feedback, and the record's status should change accordingly.

• The system should move the record to the team leader's queue for review.

### How do I dispute audit feedback as a team leader?

**How to access?**

To rebut audit feedback, the user must click on .quality

![auditdispute](/img/arflow/auditdispute1.png)

![auditdispute](/img/arflow/auditdispute2.png)

**For "Feedback Accepted" Category:**

• Under "Feedback Accepted," the team leader will see records where the entry user has accepted the audit feedback.

**Team leaders have two options:**

• Accept: The original score will be retained if the team leader selects this option.

• Rebut: If the team leader selects this option, the record will be moved to the Audit user's inbox for further action.

**For "Rebuttal by Entry User" Category:**

• Under "Rebuttal by Entry User," the team leader will see records where the entry user has raised a rebuttal against the audit feedback.

**Team leaders have two options:**

• Accept Rebuttal: If the team leader selects this option, the record will be moved to the Audit user's inbox for further action.

• Reject Rebuttal: If the team leader selects this option, the workflow will be closed, and the original score will be retained.

### How do I check rebuttal records as an audit user?

**How to access?**

To rebut audit feedback, the user must click on .audit inbox.

![auditinbox3](/img/arflow/auditinbox3.png)

![auditdispute](/img/arflow/auditdispute3.png)

**Accept Rebuttal:**

• If the auditor selects this option, it indicates their acceptance of the rebuttal made by the entry supervisor.

• The record will be moved to the Audit supervisor's queue for further approval or action.

**Review Rebuttal:**

• If the auditor selects this option, it indicates their decision to review the rebuttal made by the entry supervisor.

• The record will also be moved to the Audit supervisor's queue for further assessment and approval.

**In both cases, the records are forwarded to the Audit supervisor for additional review, approval, or action, depending on the auditor's choice.**

### How do I check rebuttal records as an audit Supervisor?

**How to access?**

To rebut audit feedback, the user must click on .quality.

![rebuttal](/img/arflow/rebuttalrecords1.png)

![rebuttal](/img/arflow/rebuttalrecords2.png)

**Accept Rebuttal:**

• If Quality GL chooses to accept the rebuttal, it indicates their agreement with the rebuttal made.

• The record will be moved to the auditor's queue (audit inbox) for re-audit by an auditor.

**Reject Rebuttal:**

• If Quality GL decides to reject the rebuttal, it indicates their disagreement with the rebuttal made.

• The record will be moved to the Entry team leader's queue for further review by the Entry team leader.

**In summary, Quality GL can either accept the rebuttal and send the record for re-audit or reject the rebuttal, forwarding the record to the Entry team leader for additional review.**

### How do I check rebuttal records reviewed by the audit Supervisor?
**How to access?**

To rebut audit feedback, the user must click on .quality

![auditinbox3](/img/arflow/rebuttalrecords1.png)

![auditinbox3](/img/arflow/rebuttalrecords3.png)

**Accept QA Lead Review:**

• If the Entry team leader chooses to accept the QA Lead's review, it indicates their agreement with the review conducted by the QA Lead.

• The workflow will be closed with the original quality score; no further action is required.

**Reject QA Lead Review:**

• If the Entry team leader rejects the QA Lead's review, it indicates their disagreement with the review conducted by the QA Lead.

• The rebuttal record will be moved to the Training User for further review or action.

**In summary, Entry team leaders can either accept the QA Lead's review and close the workflow with the original quality score or reject the QA Lead's review, forwarding the rebuttal record to the Training User for additional assessment or action.**

### How do I accept rebuttal records review as Quality Manager?

**How to access?**

To rebut audit feedback, the user must click on .quality

![auditinbox3](/img/arflow/rebuttalrecords1.png)

![auditinbox3](/img/arflow/rebuttalrecords3.png)

**Accept QA Lead Review:**

• If the Entry team leader chooses to accept the QA Lead's review, it indicates their agreement with the review conducted by the QA Lead.

• The workflow will be closed with the original quality score; no further action is required.

**Reject QA Lead Review:**

• If the Entry team leader rejects the QA Lead's review, it indicates their disagreement with the review conducted by the QA Lead.

• The rebuttal record will be moved to the Training User for further review or action.

**In summary, Entry team leaders can either accept the QA Lead's review and close the workflow with the original quality score or reject the QA Lead's review, forwarding the rebuttal record to the Training User for additional assessment or action.**

### How do I accept rebuttal records review as Quality Manager?

**How to access?**

To rebut audit feedback, the user must click on .quality

![auditinbox3](/img/arflow/rebuttalrecords1.png)

![auditinbox3](/img/arflow/rebuttalrecords5.png)

**Accept Rebuttal:**

If the Quality Manager chooses to accept the rebuttal, it indicates their agreement with the rebuttal made.

• The record will be moved to the auditor's queue (audit inbox) for re-audit by an auditor.

**Reject Rebuttal:**

• If the Quality Manager decides to reject the rebuttal, it indicates their disagreement with the rebuttal made.

• The workflow ends with the original quality score; no further action is required.

**In summary, the Quality Manager can either accept the rebuttal and send the record for re-audit by an auditor or reject the rebuttal, closing the workflow with the original quality score.**

### How do I view rebuttal records review as a training user?

**How to access?**

To rebut audit feedback, the user must click on .quality

![auditinbox3](/img/arflow/rebuttalrecords1.png)

![auditinbox3](/img/arflow/rebuttalrecords6.png)

• When Training team user Rebuttal records are displayed under the "Training Team Rebuttal Review" menu, the Training user can update their justification or comments regarding the rebuttal record using the text box provided on the screen.

• After updating their justification, the Training user can submit it. Upon successful submission, the rebuttal record will be moved to the Entry Supervisor's queue for further review and action.

## Reports

**Reports in arc.flow play a crucial role in providing insights, data, and summaries related to the various processes and activities within the system.
Following is the list of reports modules in arc.flow,**

• Production reports

• Work allocation

•  Status Report

• TAT Report

• Dashboard

### Production reports

#### Voice vs non-voice

**Description:**

The "Voice vs. Non-Voice Report" is a specialized type of report within an arc.flow provides an overview of production counts, categorizing them into "Voice" and "Non-Voice" contributions. This report allows teams to view data based on production date, Client Partner (Entry user) Name, and User Type, distinguishing between AR (Accounts Receivable) and Non-Voice users.

**How to access?**

To access the Report, the user must click on .reports> voice vs non-voice.
 
**Step-by-step process:**

![Report](/img/arflow/report1.png)

**To generate a report, follow these steps:**

• Select the start date and end date using the calendar picker.

• Click the "Submit" button to create the report.

• You can download the report in "XLS" format.

• Search for values using the filter box in the grid to refine the report data.

#### Completed call-type report

**Description:**

The "Completed Report" allows users to identify how production users have handled claims, categorizing them as "callable," "non-callable," "review," "coding," and other relevant categories. This report offers insights into the handling and outcomes of completed claims.

**How to access?**

To access the Report, the user must click on it.reports> Other reports> Completed call type report. 

**Step-by-step process:**

![Report](/img/arflow/report2.png)

• Select the report name from the dropdown. Choose "Completed Call Type Report."

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report.

• You should be able to generate the report in "XLS" format.

• You can search for specific values using the filter box in the grid.


#### Production with target report.

**Description:**

The "Production with Target Report allows users to generate reports on production data while comparing it to the targets set for each associate. This report provides insights into the performance of individual associates about their assigned production targets.

**How to access?**

To access the Report, the user must click on .reports> Production with Target.

**Step-by-step process:**

![Report](/img/arflow/report3.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report.

• Enter the recipient's email address in the "Mail to" field.

• Click the "Send Mail" button to send the report to the selected user.

• The generated report should be displayed in grid format.

• You can click the "View" button to view the production details.

• You can also search for specific values using the filter box in the grid.

#### Issue code-wise production/Audit.

**Description:**

The "Issue Code Wise Production/Audit Report" lets users view and analyze the production and audit counts categorized by specific issue codes. This report provides valuable insights into the volume and handling of issues based on their codes.

**How to access?**

The user must click on .reports> Issue code-wise production/audit to access the Report.

**Step-by-step process:**

![Report](/img/arflow/report4.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report.

• The generated report should be displayed in the form of a grid.

• You can click on the "View" button to view production details.

• You can also search for specific values using the filter box in the grid.

#### Process completed report.

**Description:**

The "Process Completed Report" allows users to identify and analyze claims or tasks completed in the production process. This report provides insights into the status of completed production claims.

**How to access?**

To access the Report, the user must click on .reports> Other reports> Process completed reports.

**Step-by-step process:**

![Report](/img/arflow/report5.png)

• Select the report name from the dropdown, specifically "Process Completed Call Type Report."

• Pick the start date and end date using the calendar picker.

• Click on the "Submit" button to generate the report.

• You should be able to generate the report in "XLS" format.

• Search for specific values by using the filter box in the grid.

#### My Process completed report.

**Description:**

The "Process Completed Report” allows logged-in users to view the details of claims or tasks they have personally processed, offering a comprehensive overview of their completed work.

**How to access?**

To access the Report, the user must click on .reports> My Process is completed.

**Step-by-step process:**

![Report](/img/arflow/report6.png)

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

• Ensure that you have the option to generate the report in "XLS" format.

• Search for specific values in the grid by using the filter box.

### Work allocation

#### Allocation for User

**Description:**

The "Allocation for User Report" is a functionality within arc.flow allows users to generate a report detailing the claims or tasks allocated to specific users. This report offers transparency and insights into how work items are distributed among team members.

**How to access?**

To access the Report, the user must click on .reports> Allocation for users.

**Step-by-step process:**

![Report](/img/arflow/report2.1.png)

• Select the start date and end date using the calendar picker.

• Click the "Submit" button to generate the report. The generated report should be displayed in the form of a grid.

• You should have the option to generate the report in various formats such as "PDF," "XLS," and "CSV."

• Search for values using the filter box in the grid to refine the report data.

#### Non-Allocated

**Description:**

The "Non-Allocated Claims Report" in arc.flow allows users to identify and review claims that have not yet been allocated for production. This report provides transparency and control over the allocation process, helping to ensure that all claims are appropriately assigned.

**How to access?**

To access the Report, the user must click on .reports> non-allocated.

**Step-by-step process:**

![Report](/img/arflow/report2.2.png)

• Choose the start date and end date using the calendar picker.

• Click the "Submit" button to generate the report.

• You should be able to generate the report in "XLS" format.

• Search for values using the filter box in the grid to refine the report data.

#### Rework Claims

**Description:**

The "Rework Claims Report" feature within the arc. flow empowers users to generate a report specifically focused on reworked claims. This report provides a comprehensive overview of reworked claims, including their information and status.

**How to access?**

To access the Report, the user must click on .reports> Rework Claims.

**Step-by-step process:**

![Report](/img/arflow/report2.3.png)

• Select the desired start date and end date using the calendar picker.

• Click the "Submit" button to generate the report. The generated report will be displayed in a grid format.

• You should be able to generate the report in "XLS" format.

• Search for values using the filter box in the grid to refine the report data.

#### Allocation status report

**Description:**

The "Allocation Status Report" enables users to view comprehensive details of claims at both the completed and allocated levels. This report offers a consolidated view of claims' allocation and completion status.

**How to access?**

To access the Report, the user must click on .reports> Allocation status.

**Step-by-step process:**

![Report](/img/arflow/report2.4.png)

• Select the desired start date and end date using the calendar picker.

• Click the "Submit" button to generate the report. The generated report will be displayed in a grid format.

• You should be able to generate the report in "XLS" format.

• Search for values using the filter box in the grid to refine the report data.

#### Inventory status report

**Description:**

The "Inventory Status Report" enables users to view comprehensive details of claims received from the customer, with the details about the call type and assignment category by location.

**How to access?**

To access the Report, the user must click on .reports> Inventory status report

**Step-by-step process:**

![Report](/img/arflow/Inventorystatusreport.png)

• Select the desired start date and end date using the calendar picker.

• Click the "Submit" button to generate the report. The generated report will be displayed in a grid format.

• You should be able to generate the report in "XLS" format and also group using the filter area based on the required information.

• Search for values using the filter box in the grid to refine the report data.


### Quality Report

This section will allow users to generate reports related to quality information.

**Type of Reports:**

• Audit allocated report.

• Audit parameter report

• Audit report

• Eligible Audit count report

• QC report

#### Audit allocated report.

**Description:**

The "Audit Allocated Report" is a report in arc.flow allows users to view and analyze the status of claim-level audits that have been allocated. This report provides insights into the allocation and progress of audits at the claim level.

**How to access?**

The user must click on .reports>Audit allocated report to access the Report.

**Step-by-step process:**

![Report](/img/arflow/report3.1.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report. The generated report should be displayed in the form of a grid.

• You can search for specific values using the filter box in the grid.

#### Audit Parameter report.

**Description:**

The "Audit Parameter report" enables users, particularly auditors to generate and manage audit parameter information. This information is typically updated by auditors in the audit inbox for each associate and is used to set criteria and guidelines for conducting audits.

**How to access?**

The user must click on .reports>Audit Parameter report to access the Report.


**Step-by-step process:**

![Report](/img/arflow/report3.2.png)

• Utilize the calendar picker to choose both the start and end dates.

• Initiate the report generation by clicking the "Submit" button. The resulting report will be presented in grid format.

• Employ the filter box within the grid to search for specific values.


#### Audit report.

**Description:**

The "Audit Report" is a report that empowers users to generate detailed audit reports. These reports provide valuable insights into the results of audits conducted in the arc.flow.

**How to access?**

The user must click on .reports>Audit report to access the Report.

**Step-by-step process:**

![Report](/img/arflow/report3.3.png)

• Select the report type "Associate wise" or "QA wise.”

• Choose the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report. The generated report should be displayed in the form of a grid.

• You can choose to generate the report in different formats, such as "PDF," "XLS," or "CSV."

• Search for specific values using the filter box in the grid.

#### Eligible Audit Count report.

**Description:**

The "Eligible Audit Count Report" is a report in arc.flow that allows users to view the count of claims eligible for audits. This report provides insights into the claim processor (CP) wise eligible audit claim counts and their allocated status.

**How to access?**

To access the Report, the user must click on .reports>Eligible Audit count.

**Step-by-step process:**

![Report](/img/arflow/report3.4.png)

• Select the start date and end date in the calendar picker.

• Choose the desired sub-client group from the available options.

• Click on the "Submit" button to generate the report.

• You can generate the report in "XLS" format.

• Search for specific values using the filter box in the grid.

#### QC Report.

**Description:**

The "QC Report" is a report that empowers users to generate reports containing details of tasks or processes that have undergone quality control checks. This report offers insights into the outcomes of quality control assessments.

**How to access?**

The user must click on .reports>QC Report to access the Report.

**Step-by-step process:**

![Report](/img/arflow/report3.5.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report.

• Choose the "XLS" format to generate the report.

• Search for specific values using the filter box in the grid.

• The generated report will be displayed with the specified data in an XLS format.

### Status Report

#### Invoice history

**Description:**

The "Invoice History report" allows users to generate and access detailed information about claims, specifically to view the status and history of claims at a granular level.

**How to access?**

To access the Report, the user must click on .reports> Invoice history.


**Step-by-step process:**

![Report](/img/arflow/report4.1.png)

• Enter the claim number in the provided field.

• Click the "Submit" button to submit the claim number.

• The system will display the relevant claim-related information in the grid upon submission.

#### Import Status

**Description:**

The "Import Status report” allows users to generate and access detailed information about file uploads. This feature provides insights into file information, such as who performed the upload, when it was imported, and the import status.

**How to access?**

To access the Report, the user must click on .reports> Import status.

**Step-by-step process:**

![Report](/img/arflow/report4.2.png)

• Select the start date and end date from the calendar picker.

• Click the "Submit" button to generate the report.

• The generated report will be displayed in the form of a grid.

• You should be able to generate the report in "XLS" format.

• You can search for specific values using the filter box in the grid.

#### Claim Status Report

**Description:**

The "Claim Status Report” provides an overview of the overall count for each claim status category, including "Completed," "Pending," and "Allocated." This report offers a consolidated view of the status of all claims in the system.

**How to access?**

To access the Report, the user must click on .reports> Claim Status.

**Step-by-step process:**

![Report](/img/arflow/report4.3.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report. The generated report will be displayed in the form of a grid.

• You should have the option to generate the report in different formats, such as "PDF," "XLS," and "CSV."

• You can search for specific values using the filter box in the grid.

#### Import Report

**Description:**

The "Import Report Screen" is a feature within arc.flow allows users to generate and access detailed client-wise information about uploaded claims. This report provides insights into "Purge Claims" and "Duplicate Claims."

**How to access?**

The user must click on .reports> Import report to access the import report.

**Step-by-step process:**

![Report](/img/arflow/report4.4.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report. The generated report will be displayed in a grid format.

• You should have the option to generate the report in different formats, such as "PDF," "XLS," and "CSV."

• You can search for specific values using the filter box in the grid.

### TAT Report

#### Average TAT Completed

**Description:**

The "Average TAT Completed Report" allows users to view and analyze the average Turnaround Time (TAT) for completed claims at the claim level. This report offers insights into the efficiency and speed of claim processing.

**How to access?**

To access the report, the user must click on .reports> Average TAT Completed.

**Step-by-step process:**

![Report](/img/arflow/report5.1.png)

• Select the report type as either "Date Wise" or "Client Wise."

• Choose the start date and end date from the calendar picker.

• Click on the "Submit" button to generate the report. The generated report will be displayed in a grid format.

• You should have the option to generate the report in different formats, such as "PDF," "XLS," and "CSV."

• You can search for specific values using the filter box in the grid.

#### TAT Report

**Description:**

The "TAT Report" allows users to view and analyze the average Turnaround Time (TAT) for completed claims at the claim level. This report offers insights into the efficiency and speed of claim processing.

**How to access?**

The user must click on .reports> TAT Report to access the TAT report.

**Step-by-step process:**

![Report](/img/arflow/report5.2.png)

• Select the report type as either "Date Wise" or "Client Wise."

• Choose the start date and end date from the calendar picker.

• Click on the "Submit" button to generate the report. The generated report will be displayed in a grid format.

• You should have the option to generate the report in different formats, such as "PDF," "XLS," and "CSV."

• You can search for specific values using the filter box in the grid.

### Dashboard

#### Production

**Description:**

The "Production dashboard" allows supervisors/Users to view the production achieved % against the target, audited count, errors and accuracy%.

**How to access?**

The user must click on .reports > Production reports

**Step-by-step process:**

![Report](/img/arflow/productiondashboard.png)

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

• Supervisors/CPs can view the production count, Achieved % against the target, Audited count, Errors and Accuracy %.

• Supervisor can filter this report by the flag and do the follow up with the team to meet their targets

• Production user can send this report to their supervisors by mail.

#### Quality

**Description:**

The "Quality report" presents data categorized by Associate, Auditor, and sub-client. Through this report, the team can gain insights into accuracy levels by assessing DPU and DPO.

**How to access?**

The user must click on .reports > Quality

**Step-by-step process:**

![Report](/img/arflow/qualityreport1.png)

![Report](/img/arflow/qualityreport2.png)

• Select type "Associate wise" or "QA wise" or "sub client wise"

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

#### TAT

**Description:**

To access the "TAT report" based on Sub-client, Date, and Issue code, this report will provide information on the average TAT (Turnaround Time) in days and the number of claims processed within and outside of the TAT.

**How to access?**

The user must click on .reports > TAT reports

**Step-by-step process:**

![Report](/img/arflow/TATreport.png)

• Select type "Client wise"or "Date wise" or "Issue code"

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

#### Volume dashboard

**Description:**

The "Volume dashboard" enables users to monitor the current statuses of incoming claims, claims in production, and pending claims.

**How to access?**

The user must click on .reports > work allocation

**Step-by-step process:**

![Report](/img/arflow/volume dashboard.png)

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

#### Issue code

**Description:**

The "Issue code " enables users to view issue code wise contibution.

**How to access?**

The user must click on .reports > Production reports

**Step-by-step process:**

![Report](/img/arflow/issuecodereport.png) 

![Report](/img/arflow/issuelogreport.png)

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

#### Multitouch

**Description:**

The "multitouch report" assists in examining the average number of touches by month, payer, and sub-client, facilitating the analysis of these interactions to enhance customer satisfaction.

**How to access?**

To access the Report, the user must click on .reports > Dashboard > Multitouch

**Step-by-step process:**

![Report](/img/arflow/multitouchreport.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report.

#### import status

**Description:**

The import status report is utilized to observe the counts of purged and duplicate claims for each practice and date.

**How to access?**

To access the Report, the user must click on .reports > status

**Step-by-step process:**

![Report](/img/arflow/importstatusreport.png)

• Select the start date and end date in the calendar picker.

• Click on the "Submit" button to generate the report.

### Rebuttal report

#### Production CP rebuttal summary

**Description:**

The "Production CP Rebuttal Summary" lets users view summary information related to CP (Claim Processor) rebuttals. This summary provides insights into the CP-wise rebuttal information, including claim acceptance.

**How to access?**

The user must click on .reports > Production CP rebuttal summary to access the Report.

**Step-by-step process:**

![Report](/img/arflow/report7.1.png)

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

• Ensure that you have the option to generate the report in "XLS" format.

• Search for specific values in the grid by using the filter box.

####	QA rebuttal summary

**Description:**

The "QA Wise Rebuttal Summary Report” lets users view and analyze rebuttal information categorized by Quality Assurance (QA) personnel. This report provides insights into the QA-wise rebuttal status (Accepted or Rejected) and includes an acceptance score for claims. 

**How to access?**

To access the Report, the user must click on .reports > QA  rebuttal summary.

**Step-by-step process:**

![Report](/img/arflow/report7.2.png)

• Choose a start date and an end date using the calendar picker.

• Click on the "Submit" button to generate the report.

• Ensure that you have the option to generate the report in "XLS" format.

• Search for specific values in the grid by using the filter box.

## Frequently Asked Questions

**1. How to give access to a new user?**

**To provide access to a new user, follow these steps:**

• Go to .setup > user master.

• Find the user you want to grant access to.

• Map the required profile to the user.

**2. Once a user's profile is mapped, do they start production immediately?**

**No, the user needs to perform an additional step:**

• The user must map the required user group before processing claims.

**3. How can I set a target for the process?**

**To set a target for the process, please note the following:**

• The Finance team can configure targets.

• Once configured, the targets will be reflected in .flow.

**4. Can I set multiple priority levels for users?**

**Yes, you can set multiple priority levels for users by following these steps:**

• Go to .setup > Priority setup.

**5. Can we set up a live audit for audit sampling?**

**Yes, you can set up a live audit for audit sampling by:**

• Going to .setup > audit configure.

**6. Can I reallocate follow-up claims to a higher priority?**

**Yes, you can re-allocate follow-up claims by:**

• Going to .setup > Follow-up reallocate claims.

**7. Can I edit completed claims in the inbox?**

• No, you cannot edit completed claims in the inbox. However, you can modify them in .completed

**8. How can I set follow-up claims review days?**

**To set follow-up claims review days, follow these steps:**

• Go to .setup > Issue code master to set up the review days.

**9. How do I move claims to the Issuelog?**

**To move claims to the Issuelog, users submitting claims in the inbox should:**

• Choose the "Move to" option and select "Issuelog." This action will redirect the claim to the Issuelog tile for Supervisor review.

**10. Where can auditors audit the claims?**

**Auditors can audit claims by accessing the following:**

The .audit inbox tile. This is where auditors can review and audit claims.













































 

























