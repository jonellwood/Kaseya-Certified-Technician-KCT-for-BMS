# Kaseya-Certified-Technician-KCT-for-BMS
Notes from KASEYA CERTIFIED TECHNICIAN (KCT) FOR BMS Class

# BMS: Business Management System

Kaseya BMS has been designed and engineered keeping the upcoming needs of MSPs in mind. BMS provides an easy-to-use interface enabling you to get up to speed quickly and be more productive in less time – without compromising with the level of depth and customization required to meet the various business objectives of different teams.

As a technician, you will learn how to easily create, manage and resolve all your service requests and tickets. You will also learn how to work efficiently and seamlessly across tools, and access the right information when and where they need it.

## Overview

### Logging In

Once you receive the Welcome Email from BMS, you will click on the link found within the body of the email which will take you to the Login Page. 

You will enter the credentials here and click **Log in**. The **Forgot password**? link will prompt you to enter your Email along with your Company Name before allowing you to reset your password.

! If you are authenticating using the **Log In with IT Complete** button, the “K” icon at the top right corner is replaced by the Application Launcher waffle icon.

### Customizing My Profile

The BMS profile page is where you can enter and update your personal information. To edit your profile, click on your name in the top-right corner of the screen to bring up the Settings menu, and click **My Settings**. 

Here, you will enter your personal and contact information and update your password. You can also set any preferences and see active integrations like QuickBooks, Xero, and more. Make sure to upload a profile picture as well and enable Multi-Factor Authentication (MFA) for your account!

My Settings > Profile in BMS.

My Profile section showing *Personal Information, Contact Information, Change Password, Preferences*, and *Integrations* tabs

Under the *Preferences* tab, you can choose your default landing page as well as the default tickets listing click behavior. Options for this behavior include “Open In Same Window”, “Open In New Tab”, and “Open In New Window”.

Additionally, you have an option to select which Service Desk Experience you'd like: "Legacy View" vs. "New View".

### Enabling Multi-Factor Authentication (MFA)

You can enable Multi-Factor Authentication (MFA) using an Authentication Application - most OTP-compliant (one-time password) applications can be used, such as Passly, Google Authenticator, Authy, and more.

**Enabling MFA on your BMS Account**

Under the Personal Information tab on your profile, you will be able to control MFA Settings for your BMS account. It all begins with the click of a button!

1. Click the **Enable MFA** button to enable/disable Multi-Factor Authentication on your BMS account.
2. Upon clicking the **Enable MFA** button you will be presented with this pop-up.
3. Grab your smartphone and open the Authenticator of your choice in order to scan the code/image displayed in your BMS instance so that you can be provided with the MFA Code.
4. Once scanned, you will be able to obtain the code.
5. Simply enter it in the **Verify MFA Code** text-box and click the **Enable** button.

! If the MFA Code is not correct, BMS will warn you with a message similar to this: *"There was an error with your verification code or the code has expired. Please try again."*

### Navigating BMS

Selecting a module ("location") in the Global Navigation Bar displays an associated menu of folders on the left-hand side - we call this menu the Local Navigation Bar.

Additionally, you can expand or collapse the **Local Navigation Bar** by clicking the *'hamburger'* button. You will see the module you are currently, in turn, a darker color in the **Global Navigation Bar**, indicating that it is active.

Your Security Role dictates what Modules/Folders you will see when you log into BMS - this is controlled by your BMS Administrator.

! Remember that BMS is a customizable platform, and your Admin has customized your BMS access based on the functionality you need. Because of this, you may not have access to all of the functionality described in this program and what you see in your platform may differ slightly from the images shown.

### Wrap-up

Since you are now familiar with the login process and what is configurable under My Profile, we will move on to the Home Module.

## Managing Tickets

### Using the Home Dashboard

The Home module is a great starting point for day-to-day use and provides easy access to folders like My Tickets, My Tasks, My Service Calls, etc.

The Dashboard is the landing page that allows you to stay up-to-date at a glance. In this module, you will also be able to navigate to your timesheets, access the Dispatch Calendar, and much more!

Home > Dashboard.

- **MY TO DO LIST**: To-Do List helps keep you organized. When completed, they will be crossed off and moved to the ***Already Done*** tab. Enter the desired text, then click the calendar and set the date, or simply enter the word *"tomorrow"*. Press the **Enter** to add the entry.

- **MY NOTES**: A quick summary of thoughts or ideas that you don't want to forget during the day. Click on the text editor to add your notes, and click anywhere on the screen when done.

- **NEWS**: Company-wide news can be presented here by the Administrator of the organization. Click the ***"Read more ..."*** link to display the News item.

Feel free to collapse them and/or reorder them as you wish. You can drag and drop them in the preferred order.

### Accessing My Assigned Tickets

**Service Desk Experience Views**

The "My Tickets" folder manages tickets assigned to yourself as the primary assignee. If you assign the ticket to another employee, the ticket no longer displays on this grid. Ticket assignments to queues are ignored by this folder. You can search for all tickets assigned to the queues you are a member of using the Queue search parameter.

Remember the two options you saw at your Profile > Preferences tab? This is what the two Views would look like depending on what you choose there:


- **LEGACY VIEW**: The Service Desk > My Tickets folder showing the legacy view which is the default one unless you selected "New View" in your Profile > Preferences tab.
- **NEW VIEW**: This user experience for ticketing provides this new design where you will experience faster navigation with a sleek new interface!

! You will also see your tickets under the Service Desk Module which we will cover next.

### My Tickets

The Service Desk module is the central place to manage all the support tickets between you and your clients.

The "My Tickets" folder here is mirrored in the Home module you just learned about - same tickets and information. You can search for tickets based on different criteria such as *Ticket Number, Title, Status, Source, Ticket Owner, etc.*

Service Desk > My Tickets shown using the Legacy View

#### My Tickets - Buttons

- **New (N)**: Creates a new ticket.

- **Search (S)**: Searches for the specified criteria.

- **Clear Search (C)**: Clears the search form.

- **Export**: Exports the current page of tickets or all pages to an Excel spreadsheet.

- **Batch Actions**: Enables you to perform actions on multiple tickets at the same time.

! Batch Actions are driven by security; so this button will *only* be visible if you have the rights via your Security Role.

### Viewing all Tickets

The "Tickets" folder manages *all* tickets created for customer issues. An issue may be a question, a problem, a request for service, or a suggestion for a future enhancement.

Tickets are assigned to Employees (technicians) and Queues (groups of employees) to work on the support issue. The ticket helps track the progress of the issue towards resolution

**Tickets creation is initiated by:**

1. Phone: The client calls and you create the ticket manually.

2. Email: An email to support is converted into a ticket automatically.

3. Client Portal: The customer creates the ticket manually.

4. VSA Alerts: Alerts from the Kaseya VSA can create tickets in BMS.

! We will cover more details on the Service Desk Module in an upcoming Course.

### Creating Views

As you saw under "Service Desk > Tickets", this is the folder that holds *all* tickets in your BMS instance. If you ever find yourself in need of a simplified breakdown of information, you can select specific columns and save it as a View.

#### Creating a View

1. **Views**: Click the last button under the *Views* section to add/remove columns.
2. **Column Chooser**: You will be presented with available and displayed columns. On the right-hand side, you have a list of columns to add. Drag/drop or use the arrows to add/remove columns as needed. Click **Save (S)** when finished. **Note**: You can also have search criteria as well. Primarily people use Views to select all Open tickets and then the column chooser is secondary - you can also change the selection of tickets.
3. **Saving your View**: The grid will update reflecting any changes you made, whether it is a new column or one your removed. To save the View simply click the 'gear' icon and select **Save As**.
4. **Naming your View**: Give your View a name, and decide whether or not you'd want this to be public and/or set as your default view. Click **Save (S)** when finished.
5. **Managing your View**: Now that you've saved your View, it will be available to you from the Views drop-down menu. You can edit, delete, or share your View as needed!
6. **Using your View**: Additionally, on the Local Navigation Bar, you will be able to access the recently saved View without having to browse to the folder where you created the View in.

! *All* screens in BMS have the capabilities to create Views. When using the *New View* for Service Desk, a "System Default" view will be used as default if no view was previously selected by the user.

### Creating Templates

The "My Templates" folder enables you to maintain your own set of ticket templates. To make ticket creation easier, when you create a ticket, you can select one of your ticket templates to pre-populate selected fields for you. 

Ticket templates can include adding questions in the description field of the ticket. These questions can then prompt ticket editors to ask these standard questions when contacting customers.

Home > My Templates.

! Your ticket templates can be shared with other team members. If you don't share a ticket template, it can only be viewed by yourself and BMS Administrators.

#### Creating a Template

1. **Templates**: Click **New (N)** to select one of three types of ticket template:
	- "Ticket Template" - Defines custom templates for tickets. You select this type of template using the From Template field when adding a new ticket.
	- "Ticket Note Template" - Defines custom templates for notes in tickets. You select this type of template using the From Template field when adding a note to a ticket.
	- "Ticket Time Entry Template"  - Defines custom templates for time log entries in tickets. You select this type of template using the From Template field when adding a time log entry to a ticket.

2. **Ticket Template**: In this form, you will get to enter the desired information with "Ticket Template Name" being the only required field. When finished, go ahead and click **Save (S)** to save your ticket template.

3. **Ticket Note Template**: This form is different from the "Ticket Template" form. Here, you will be able to double click on the fields found in your right-hand side in order to get them added to the "Details" editor. When finished, go ahead and click **Save (S)** to save your "Ticket Note Template".

4. **Ticket Time Entry Template**: The last template type form is "Ticket Time Entry Template". Here you will be able to add details using a similar form to the "Ticket Note Template" type. When finished, go ahead and click **Save (S)** to save your template.

! When working with Templates, the **Share With Team** option means that the template will be shared with other BMS Users in the system. The **Share With Account** option means that the template will be shared with the Client Portal.

### Wrap-up

Since you are now familiar with some of the subfolders in the Home and Service Desk Modules, we will move on to the CRM Module (*we will go into more details on Service Desk tickets in Module 4*).

## Managing Accounts and Contacts

### Introduction

The CRM Module allows you to manage the business relationship and interactions you have with customers, prospects, vendors, etc., and store all the data about these relationships.

These interactions can be sales-related - calls, emails, meetings, and demonstrations, as well as support-related.

**The CRM module provides:**

- Immediate access to Accounts and Contacts.

- Sharing of important data between departments.

- Management insight into Sales Process and Account Management activities.

### Viewing Accounts

The "Accounts" folder allows you to maintain your account profiles for every organization you do business with. This includes clients, prospects, vendors, competitors, former clients, business partners, and miscellaneous organizations.

Here you also have the Search Form where you can look up accounts by their code, name, type, and much more!

CRM > Accounts

! Although you still see the **New (N) button**, your BMS Administrator may have disabled this feature from your Security Role - where you can only *view* accounts but not manage them.

#### Viewing Accounts

1. **Opening an Account**: Click on the Account record - whether it is by clicking on its name or the **Edit** icon.
2. **Viewing an Account**: Once you open the account you will be able to see relevant information such as *Locations, Contacts, Assigned Resources, Email Domains, Departments, Tax Settings,* and much more! You can browse the different tabs for further information.
3. **Accounts**: When finished, simply click on the Module/Folder of your choice to exit out of the account or go back to "Accounts Management".

### Creating & Managing Contacts

The "Contacts" folder is used to maintain contacts for each account. These are the individuals that the sales team works with to sell products and services, people that your project team is delivering a completed project to, or people that are calling you for support and who you are opening tickets for.

CRM > Contacts

#### Viewing a Contact

You can view a Contact by performing the same action from the previous lesson - click on the Contact record or its "Edit" button.

You will see different fields and settings at the Contact level. For example, you can specify whether or not you'd want this individual to be the point of contact, and/or receive invoices. Additionally, you can browse to the available tabs: *Phones, Emails, Client Portal Access, Notes, Activities*, and *Custom Fields*.

! To deactivate a Contact simply click on the **Deactivate** button next to "Status". To update "Bill By Contact" simply click on the **Disabled** or **Enable** buttons. You will be able to track changes to the Contact by reviewing the "Contact History" tab.

#### Creating a Contact

1. **Contacts**: Click the **New (N)** button to get started.
2. **New Contact Form**: You will be presented with a form; fill it out with the required fields and add anything additional you'd like to have listed for the Contact.
3. **Adding Phone(s) & Email(s)**: Before you attempt to save the Contact record, you'll have to specify at least one phone number and one email address under the *Phones* and *Emails* tabs.
4. **Saving your Contact**: Click **Save (S)** when finished. You also have the option to save the current record and open up a new form to add another one.
5. **Creating a Contact**: Upon saving your Contact you will notice two additional tabs that will display: *Notes* and *Activities* - feel free to navigate to the different tabs and add information as needed. Always save your changes by clicking **Save (S)**.

### Wrap-up

Since you are now familiar with the CRM Module, we will move on to the Service Desk Module next!

## Service Desk & Admin

### Viewing and Managing Asset Data

#### Hardware Assets

Back to the Service Desk Module, the Asset Management folder is a centralized place to store all your clients' hardware and software assets.

Your first sub-folder here is "Hardware Assets" which registers hardware owned by the client and located at the client location. Within this sub-folder, you will be able to create, search and export hardware assets.

Service Desk > Assets Management > Hardware Assets.

! Keep in mind that the View you created in the previous lesson will not carry over to other folders/sub-folders. If you wanted to use a View here you'd need to create it and save it in the screen you're in.

##### Creating Hardware Assets

1. **Creating a New Hardware Asset**: Click the **New (N)** button to open the New Hardware Asset form.
2. **Asset Info**: The first tab - *Asset Info*, is where you will enter unique information regarding the asset. You have several fields/drop-downs, of which four out of those are *required*.
3. **Additional Info**: In the *Additional Info* tab, you will find several other fields, including the "Vendor" drop-down. This drop-down gets populated by CRM Accounts that were created as "Vendors".
4. **Asset Details and more...**: You will be presented with several other tabs when creating a Hardware Asset. 

	- The Asset Details tab allows you to enter from Manufacturer to the Max Memory Slots found on the hardware.
	- The Asset Disk Volumes will display any disk-related information regarding the hardware.
	- The Network Details tab is useful for entering: IP Address, Subnet Mask, Default Gateway, Mac Address, etc.
	- The Motherboard Info and Chassis Info tabs allow you to keep track of information regarding these two.
	- The last tab, Custom Fields will display any associated Custom Fields your BMS Administrator may have created for the Hardware Assets folder.


#### Software Assets

Your second sub-folder here is "Software Assets" which registers software owned by the client and located at a client location.

Service Desk > Assets Management > Software Assets

##### Creating Software Assets
1. **Creating a New Software Asset**: Click the **New (N)** button to open the New Software Asset form.
2. **Software Asset**: Unlike Hardware Assets, here you will be presented with one tab only - *Software Asset*. There are four required fields, fill them out and any further information you'd like logged. When finished, go ahead and click **Save (S)**.
3. **Additional Tabs**: Upon saving the Software Asset, three additional tabs will appear on the screen.
4. **Software License**: The *Software License* tab allows you to add software license information regarding your asset.
5. **Custom Fields**: The *Custom Fields* tab will display any associated Custom Fields your BMS Administrator may have created for the Software Assets folder.
6. **Attachments**: The last tab, *Attachments* allows you to upload attachments to associate with the Software Asset. You can always delete attachments you no longer want here.

! Both, Hardware and Software Assets can be added using these sub-folders, or by adding a charge to a ticket or project and delivering it.

### Creating a New Ticket

Click **New (N)** under "My Tickets" or "Tickets" sub-folders to create a new ticket.

You can create a new ticket from the global navigation bar blue New Ticket button, "My Tickets" folder, or "Tickets" folder, both located in the Service Desk Module.

#### Creating a Ticket

1. **Customer Info**: On the left-hand side of your ticket screen, under "Customer Info" you'll need to select an Account. Once the Account is selected you can then select a Contact (*both covered in a previous module*). Once a Contact is selected, the fields will auto-populate for the contact. The "Source" field can be defaulted if set up by the BMS Administrator or can be changed by you using the drop-down menu.

2. **Ticket Properties**: Under "Ticket Properties" you'll need to select a Type (*only required* field in this section) and fill out the rest if applicable. **Note**: If you select a "Work Type" for the ticket, ***all*** time entries will have this Work Type attached. If you want to have multiple work types on a ticket do not fill in this field.

3. **Ticket Details**: On the right-hand side of your ticket screen, you have the ability to select a Ticket Template (covered in a previous module). You will need to give the ticket a *Title* (brief summary of issue), *Priority, Status*, and *Details* on why the ticket is being opened. The "Details" section can be filled out manually or populated using a Template.

4. **Further Details**: The last section of your ticket screen will let you specify the Ticket Assignee and/or the Queue the ticket will be assigned to. You will also be able to set the Open Date. You also have the option to specify a Secondary Assignee and CC other Contacts. This section will also let you select an affected Hardware/Software Asset (covered earlier in this module) and attach files. **Note**: You have the choice to assign the ticket to either the Queue or a specific technician. You do *not* have to assign it to both.

5. **Saving your Ticket**: Click on **Save (S)** when finished.

### Working Tickets

You will be able to see/open/edit the recently created ticket under the "My Tickets" (if you are the assignee) folder, or you can search for it under "Tickets".

Click on the ticket entry to open it up!

Service Desk > My Tickets using the Legacy View. 

#### Reviewing the New Ticket

When the ticket opens, this will be the screen presented to you. You will have several buttons at the top to **Edit (E)** your ticket, **Assign**, and/or **Resolve** it. The **More** drop-down offers you options to **Print**, see **Audits**, **Merge** into another ticket, and/or **Absorb** other tickets.

Moving down the screen, you will have six tabs: *Ticket View, Time Logs, Expenses, RMM Integration, Custom Fields*, and *Attachments*. And at the bottom of the screen you will have other tabs: *Activities, Expenses & Charges, Service Calls & To-Dos* and *Related Tickets*. Tabs presented can be different based upon your security access configured by the BMS Administrator.

#### Processing Tickets

1. **Adding Time to Tickets**: You add time to tickets in the *Time Logs* tab or in the *Activities* tab > **Add Time** button

	- Time log entries can be created with or without using a timer.
	- Time entered on tickets automatically updates the user's timesheet.
	- If linked to an active contract, time entered on a ticket can: Create billable events for Time & Materials contracts, deduct prepaid hours for Retainer by Hours contracts, deduct prepaid amounts for Retainer by Amount contracts, and track but not bill time for Recurring Services contracts.

2. **Adding Expenses to Tickets**: You add expenses to tickets in the Expenses and/or Expenses & Charges tabs. Expenses entered on tickets will automatically update an existing expense sheet not already submitted or will create a new one based upon the name and date you provide. Alternatively, users can enter an expense on an expense-sheet and link it to a ticket. These can include:

	- Expenses billed to customers.
	- Expenses reimbursed by your company to the employee.

3. **Adding Notes to Tickets**: You add notes to tickets in the *Activities* tab via the **Add Note** or **Add Time** buttons. When you add notes to a ticket you can:

	- Change the status of a ticket.
	- Notify others of the note you're adding.
	- Include an attachment with the note.

4. **Adding Charges to Tickets**: You add charges to tickets in the *Expenses & Charges* tab. Charges use the product listing that can be found in the Inventory module. You can add charges to tickets that optionally:

	- Are billable or not billable.
	- Different pricing levels can be applied to bill your customers different rates (*configured by your BMS Administrator).
	- Reference an existing PO.

	**Note**: Once a Charge is added to the ticket you can then edit the charge. You can:

		- **Order (O)** - Create a PO to order and track the item through the inventory process.
		- **Deliver (D)** - Remove from inventory and/or create the product as a Hardware or Software Asset for that client.

5. **Adding Service Calls to Tickets**: You add service calls to tickets in the *Service Calls & To-Dos* tab.

	- Service calls are first scheduled, then marked as complete after the service call has occurred. 
	- You can also manage service calls using the Service Desk > Service Calls folder and within project tasks.

6. **Adding To-Dos to Tickets**: You add to-dos to tickets in the *Service Calls & To-Dos* tab. To-dos can be assigned to yourself or any other employee. To-dos provide each user with his or her own system-wide checklist (all Module Dashboards) of reminder tasks to perform, with due dates and completion status.

7. **Adding Related Tickets**: When you merge or absorb tickets you will see those tickets in the *Related Tickets* tab. You can manually link tickets together by clicking on the **Add Related Ticket** button and selecting the correct ticket. **Note**: Only tickets that are for the same Account can be related to one another. When you add a related ticket, links are created in both tickets. Clicking a related ticket opens the related ticket in a new window or tab, enabling you to work on both tickets in tandem.


### Recurring Master Tickets

The "Recurring Master Tickets" folder creates a series of 'child' tickets for a recurring support issue based upon a pre-defined timeline. For example, a maintenance service call might be required monthly for a hardware asset.

- You can link a Recurring Master Ticket to a Contract. When you do, each child ticket will be linked to that contract. If you do not link a contract to the Recurring Master Ticket all time entered on the 'child' tickets will not adhere to any contract and could be billable.

- You can create a series of Service Calls, with each service call date/time will be linked to its own child ticket.

- You can select any created child ticket from the *Tickets* tab of the recurring master ticket.

- Once the Recurring Master Ticket is saved the first time, defaults on the *Defaults* tab *cannot* be changed.

- You can create additional child tickets by extending the recurring time period on the *Recurrence* tab - this is the only recurrence setting you can change.

#### Creating a Recurring Master Ticket

1. **Creating a New Recurring Master Ticket**: Click the **New (N)** button to get started.

2. **Defaults Tab**: On the main tab - *Defaults*, you will give your Recurring Master Ticket a Title (this will be on the child tickets as the ticket title), associate it with an Account, Location, designate the Assignee or Queue as well as other required fields. When finished here, select the second tab - *Recurrence*. **Note**: The fields required on a Recurring Master Ticket are the same as a regular Service Desk Ticket.

3. **Recurrence Tab**:  The Recurrence tab lets you specify how many tickets to create in the series and the interval between them. You can create all tickets now (*not recommended*) or create tickets incrementally. When selecting "Incrementally", you will specify how many hours/days you want the ticket to create prior to the Due Date. The Due Date is a combination of the "Due Time" specified in the *Defaults* tab and the "Date" you are having the ticket created. **Note**: A recurrence can *only* be modified if it's incremental.

4. **Service Calls Tab**: The *Service Calls* tab lets you create service calls, one for each ticket in the series - this is *optional*.

5. **Custom Fields Tab**: The *Custom Fields* tab will list any custom fields your BMS Administrator might've listed for the Service Desk Module.

6. **Saving the Recurring Master Ticket**: When finished, click Save (S) to save your Recurring Master Ticket. You will see banners alerting you of the status of the ticket.

7. **Viewing the Recurring Master Ticket**: Upon saving it, you will see three new tabs show up: *Tickets, Attachments*, and *Logs*.

	- *Tickets*: This tab will list a series of child tickets once they have been created. If you selected "Incrementally" (*recommended*) you will see the child tickets after they create, if you selected "Create all tickets" now you will see them in this screen right away. You can click each ticket to view or work that individual ticket.

	- *Attachments*: You can upload a new file to attach to your Recurring Master Ticket.

	- *Logs*: This tab will list all logs associated with the creation of this Recurring Master Ticket.

#### Viewing the Recurring Master Ticket

The recently created Recurring Master Ticket  will show in the Recurring Master Ticket folder in Service Desk. The individual tickets created will show in the Tickets folder or My Tickets - depending on who they are assigned to.

### Using the Outbound Email Log

The Outbound Email sub-folder provides an audit of *all* outbound emails used to notify customers.

You have the ability to search this page. To review the logs for each record, go ahead and click on the desired one to open up the logs.

Admin > Logs > Outbound Email.

#### Log Entry

Once you've selected the entry this screen will open up. Here you will be able to view *Email Log Info*, review *Email Log History*, forward and resend the email to the original recipients.

### Wrap-up

Since you are now familiar with ticket creation, recurring master tickets and the outbound email logs; we will move on to covering the rest of the Home Module at this time.

## Managing Projects and Tasks

### Introduction

We've covered folders: *Dashboard, My Tickets*, and *My Templates*, now it's time to cover the remaining of the folders found in the Home Module.

### My Tasks

The "My Tasks" folder enables you to view and update any tasks assigned to you by project managers. You will be able to enter time and/or update other properties of tasks including the associated child tasks if any attached.

Time entered on tasks updates your timesheet *automatically*. These tasks will also show up in the *My Calendar* folder on your BMS Calendar ensuring you are aware of anything assigned to you.

Home > My Tasks

! This folder does not display tasks of Archived Projects.

#### Viewing/Editing a Task

1. **My Tasks**: Click on the task entry to open it.

2. **Basics Tab**: The *Basics* tab will display once you've opened the task. The only two fields you can edit here are: *Status* and *Percent Done*.

3. **Time Logs Tab**: The *Time Logs* tab allows you to enter time for your task, whether it's manually entered or by clicking the **Start Timer** button.

4. **Notes Tab**: The *Notes* tab allows you to enter notes for your task. Click **Save (S)** when finished.

5. **Custom Fields & Attachments**: The *Custom Fields* tab will list any custom fields your BMS Administrator might've listed for this folder. The *Attachments* tab will let you upload a new file to attach to your task.

6. **Saving the Changes**: When finished, clicked **Save (S)**.

### My Grouped Tasks

The "My Grouped Tasks" folder lists the Projects where you have tasks assigned. When you edit that project you will then see all tasks you are assigned in that project. 

Home > My Grouped Tasks.

When tasks are listed, edit a task and you will be presented with the same screen as shown above in *My Tasks*. Once a task is opened, you can update the necessary areas in the task as shown below.


### My Projects

The "My Projects" folder enables you to update the projects you are assigned to as project manager.

Home > My Projects

! Remember that you have the ability to search for Projects, export pages, and/or create Views to use within the "My Projects" folder.

#### Viewing/Editing a Project

1. **Viewing a Project***: Click on the Project you wish to open.

2. **Project Tasks***: This will *automatically* take you to the Project's Tasks tab where you'll be able to add, edit and/or import a task. Here you also have the ability to review the project itself in the *Project* tab. **Note**: The Gantt Chart, Batch Actions, and Actions buttons are controlled by your BMS Administrator. They may be visible but clicking on them will generate an error if you do not have access to these functions.

3. **Editing a Project**: The *Project* tab allows you to view more information on the Project. You will be able to make changes as needed. Familiarize yourself with the different tabs available to you, *Financials, Expenses, Charges*, etc. using the next interaction.

4. **Saving the Changes**: When finished, clicked **Save (S)**.

Details in the different tabs:

- **Financials**: The *Financials* tab summarizes the costs and pricing associated with a project. All labor time entries, expenses, and charges applied to a project are totaled in this tab and tracked by the Finance modulefor both billing and reporting purposes. **Note**: This tab is driven by security; so, it will only be visible if you have the rights via your Security Role.

- **Related Opportunities**: The *Related Opportunities* tab shows the links between a project and quotation and one or more opportunities. If a project was created by converting an opportunity into a service quotation, and then converting the service quotation into a project, these display as Converted From links.

- **Expenses**: The *Expenses* tab shows expenses entered on projects automatically update the user's expense sheets. Alternatively, users can enter an expense on a expense-sheet and link it to a project. **Note**: You can use pre-configured expense types to save time. You can also adjust the default amount for each expense. These can include:

	- Expenses billed to customers.
	- Expenses reimbursed by your company to the employee.

- **Charges**: The *Charges* tab allows you to add charges to projects that optionally:

	- Are billable or not billable.
	- Sells or provides at no charge - products to your client. 
	- Transfers the products to the client's hardware assets or software assets.

- **Receipts**: The *Receipts* tab lists all expense receipts for the project.

- **Custom Fields & Attachments**: The *Custom Fields* tab will display any custom fields your BMS Administrator may have set for this record. The Attachments tab lists all attachments, for both the project and for specific tasks. You can click Upload a new file to upload files to this record.

### Wrap-up

Since you are now familiar with some of the folders in the Home Module, we will move on to the second and last part of this curriculum which covers the second half of the folders found in Home.

## Managing Calendars, Time and Expense Sheets

### My Calendar

The "My Calendar" folder provides a calendar view of all your scheduled BMS events allowing you to filter by Event Type: *Appointments, To Dos, Tasks, Activities*, and *Service Calls*.

This folder allows you to search for events, export the calendar, download the Outlook extension and perform a calendar sync. You will also be able to add a new appointment by double clicking anywhere in the calendar. Optionally, you can always right click to bring up a menu allowing you to create not only appointments but To-Dos and Activities.

! The **Export Calendar** button will download an "icalendar" file for importing into other calendar software packages. 

The **Download Outlook Extension** is not recommended to be used as this has been replaced by the Calendar Sync button. You can sync your work calendar with BMS showing all events within BMS as well as your work calendar. 

#### Viewing a Task in the Calendar

1. **Viewing an Event**: Click on the event you wish to open. You can also hover over the even to view more details.

2. **Basics Tab**:  The *Basics* tab allows you to update the Status and Percent Done - the other fields are read-only.

3. **Time Logs Tab**: The *Time Logs* tab allows you to enter time for your task. This was covered in a previous Module - you can either enter it manually or start the timer.

4. **Notes Tab**: The *Notes* tab allows you to enter notes for your task. And the last two tabs which you're familiar with are *Custom Fields* and *Attachments*. Click **Save (S)** when finished.

! Viewing calendar events is different based upon the event you are viewing/editing, i.e. Tasks vs. Service Calls. When you edit/view a BMS entry in the calendar you will be presented with the same screens as you would see in a *Project Task* or a *Service Call* to update them accordingly.

### My Service Calls

The "My Service Calls" folder enables you to update service calls created to assist customers. Service calls are associated with *Tickets* or *Project Tasks*.

#### Viewing/Editing a Service Call

1. **Viewing a Service Call**: Click on the Service Call you wish to open.

2. **Service Call Tab**:  The *Service Call* tab allows you to update the Resource, mark the Service Call as 'Complete', update the Start/End Dates, as well as edit the Description. Here you will also have a link to the ticket or project this Service Call is related to. You can click on the ticket or project link which will open it up in a separate tab.

3. **Notification Tab**: The *Notification* tab allows you select multiple Resources, select an Email Template to use (*this is configured by BMS Administrators*) and specify other emails you'd want the notification to go out to.

4. **Saving the Changes**: When finished, clicked **Save (S)**.

### Dispatch Calendar

The "Dispatch Calendar" folder provides a calendar view of all employee scheduled BMS events. Event types can include *Appointments, Activities, Tasks, To-Dos*, and *Service Calls*.

Upon clicking this folder, a new tab will open up on your browser. You have several drop-down menus which will help you filter by Resource, Queue, or Event Type - click **Search (S)** once you have your search criteria in place. 

In this folder you will also be able to use any Views you've created, for example: the "Contact Name View" you created in a previous Module.

#### Using the Dispatch Calendar

The Dispatch Calendar will also let you double click or right click to create a new Appointment, To-Do, or Activity on your BMS account as seen in the previous Module. 

Additionally, you can drag and drop a specific ticket on to an employee's calendar date. Doing so opens the Service Call dialog where you can enter additional details for the Service Call, then click **Save (S)**. Once you do this, the new Service Call will display in the Dispatch Calendar, employee's My Service Calls page, and in the corresponding ticket.

### My Timesheet

The "My Timesheet" folder lets you maintain your timesheets which are are saved automatically after you add or change time entries. You can also create new ones by clicking **New (N)**.

#### Facts about Timesheets

- Timesheets include all the time entries you enter anywhere in the system. This includes time entries for tickets and tasks.

- A timesheet specifies a weekly date range when it is created, always starting on the same day of the week. Each user can only have one timesheet for each weekly date range.

- Timesheets are automatically created the first time a time entry is created within that timesheet's weekly date range. Or you can manually create a timesheet for a new weekly date range, before any entries have been created.

- If Preload Timesheets is "Yes" on the Time Sheet tab then scheduled events on ticket and tasks will preload any future timesheets you create. If "No", then only actual time entries display on timesheets.

- If you attempt to add a task that is Closed or on Hold, then 0 time is shown allotted - you cannot change this.

 
#### Editing a Timesheet

1. **Viewing your Timesheet**: Click on the timesheet you wish to open.

2. **Editing your Timesheet**: Once you open the timesheet you will be presented with a similar screen to this where you will be able to add time entries, add *Internal Notes* and review the *Approval History* if needed. 

3. **Adding Tasks & Tickets**: You can always add more tasks to the timesheet along with admin tasks, or even add tickets.

4. **Submitting your Timesheet**: When finished, clicked **Submit for Approval**. This action will change the timesheet's status from "Open" to "Submitted". **Note**: You will be notified about Approvals/Rejections in several ways: via Settings > My Messages inbox, with an Email Notification and the status of the timesheet will change from "Submitted" to "Approved" or "Rejected".

5. **Approver's View**: This is what the Approver's view looks like. They can approve or reject your time-sheets.


### My Expense Reports

The "My Expense Reports" folder allows you to maintain all your expenses, no matter where they are entered in the system - this includes expenses for tickets and tasks. You can also enter expenses without linking them to tickets or tasks, such as for your own company's expenses.

! You can enter expense entries for any date on any expense report. You are *required* to enter a date in the header of the expense report but the date does not restrict you.

#### Adding Expenses in BMS

1. **Adding a New Expense**: Click on **New (N)** to get started.

2. **Name & Date**: Give your expense a name and pick a date. Click **Save (S)** when finished.

3. **Expense Entries Tab**: After clicking **Save (S)** you will be presented with this screen. To add expenses simply click **+Add** under the *Expense Entries* tab.

4. **Adding Expense Entries**: When adding an expense, you will be able to select the Expense Type from the drop-down menu (*these are defined by your BMS Administrator*). You will need to fill out the required fields, add notes if needed, and select the expense association: *Project, Ticket*, or *Internal Expense*.

5. **Adding a Receipt**: The *Receipts* tab will allow you to upload a picture of your receipt. Save your changes.

6. **Reviewing the Expense**: As soon as you save your expense, you will see it reflected in the *Expense Entries* tab - feel free to add more if needed. The Receipts tab will also show the attachment you uploaded. You can add notes and review the history of the expense under *Approval History*.

7. **Saving your Expense**: Save your Expense by clicking **Save (S)**. You also have the ability to print the expense sheet for your records.

8. **Submitting your Expense**: The last step in this process will be to submit your Expense. Submitted expense reports can be *manually* approved or *auto-approved*:

	- If your company uses approval routes, submitted expense reports display in the "My Approval" folder of the appropriate persons for review.
	- If your company does not use approval routes, the submitted expense report is auto-approved - you will be able to review this in the *Approval History* tab we covered in Step 6.

	**Note**: A *Submitted* or *Approved* expense report *cannot* be edited. A Rejected expense report can be subsequently Re-Submitted and Approved. You are notified about approvals/rejections in several ways:
	- A message displays in the Settings > My Messages inbox. 
	- You may also receive an email message.
	- The status of the expense report will show "Approved" or "Rejected".


### Collaborations

The "Collaborations" folder maintains discussion threads about a project, shared with all project team members - Project team members include the project manager and any employees assigned to be members of a task. You can create new thread topic at any time.

#### Adding a Thread to Collaborations

1. **Collaborations**: Click on any of the assigned entries to open it.

2. **New Thread**: Click on the **New Thread** button to get the conversation started.

3. **Add New Thread**: Fill out the Subject field, and select the type of thread this will be, example: *Question, Reply, Information* or *News*. Then add to the Content area and click **Save (S)** when finished.

4. **Viewing the Question**: You will be taken back to the previous screen where your question will be posted.

5. **Editing the Thread**: You can click on the thread which will allow you to *comment, edit* or *delete* the question you just posted. Here's where the **Reply** button will be found.


### Downloads

The last folder in the Home Module is "Downloads". This folder provides connector tools you can use to integrate and synchronize data between BMS and external applications. Click any of the Download buttons to download these tools to your local machine.

### My Approvals

Let's pick up where we left off, shall we?

The "My Approvals" folder allows you to approve or reject timesheets and expense reports submitted by employees on two separate tabs. If you are not an approver, or submitted timesheets and expense reports are auto approved, the "My Approvals" folder does not display in your Home module.

### Wrap-up

Congratulations! You've completed the BMS-KCT curriculum. 

---------------------------------------

Q: In your Profile, which tab allows you to select your Default Landing Page?
A: Preferences

Q: Where can you enable MFA for your BMS account?
A: Settings > My Profile

Q: Select all that apply: You can access which of the following via your Home Module.
A: My Tickets, My Tasks, My Calendar

Q: True or False: You can only create Views in BMS for the "Tickets" & "My Tickets" folders.
A: False

Q: Which BMS Module allows you to view Accounts and manage Contacts?
A: CRM

Q: True or False: For Contacts, you must to specify at least one phone number and one email address.
A: True

Q: True or False: Both Hardware and Software Assets can be added via "Service Desk > Assets Management", or by adding a charge to a ticket or project and delivering it.
A: True

Q: What can be added to tickets in BMS?
A: All of the above

Q: Select all that apply: Select some of the tabs you may have access to when viewing a Project.
A: Financials, Related Opportunities, Receipts

Q: True or False: You can view "Appointments", "To Dos", "Tasks", "Activities" but not "Service Calls" on your calendar.
A: False

Q: Which BMS folder allows you to maintain discussion threads about a project?
A: Collaborations

Q: True or False: Timesheets include the time entries you enter anywhere in the system, except for time entries for Tickets and Tasks.
A: False
