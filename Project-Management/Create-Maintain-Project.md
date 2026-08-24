---
layout: NewLayout
title: Business Central for Project Management
description: Enhanced functionality for project management in Microsoft Dynamics 365 Business Central
---

- [Create a New Project](#create-a-new-project)
- [The Project Card](#the-project-card)

## Create a new Project

From the Role Centre, click on Projects:

![alt text](Screenshots/image.png)

From the projects list page, click on 'New'. The following dialog will appear:

![alt text](Screenshots/image-1.png)

Select a customer from the drop down.
Set the Project Category, Contract type and Scope. [Definitions](Projects-Overview#definitions)

Set a start date and duration.
Optionally enter number of phases, and number of tasks per phase that you would like to create. (You can add tasks or phases later).

Under Project Information, click on the ellipse next to the Project No. field. 

Example:

![alt text](Screenshots/image-2.png)

The system will populate the project number and generate a description. The project manager field defaults to the current user. You can edit these details if necessary.

Click on OK to complete the activity. Confirm the creation of the project by clicking Yes on the following dialog:

![alt text](Screenshots/image-3.png)

The project will be created and the project card will open.

# The Project Card

The Project card consists of several sections. Areas that form part of the standard BC Projects module are not discussed in detail - more information is available on the Microsoft Learn site.

- [**General tab**](#general-tab): displays key information about the project
- **Project Tasks Lines:** displays the work breakdown structure (list of tasks)
- **Project Planning Lines:** displays costing and billing details for a selected task.
- **Project Accounting tab:** contains parameters used for managing the WBS structure
- **Posting:** defines settings that control how transactions are posted in the standard Business Central projects module.
- **Invoicing and Shipping:** contains details related to shipping of goods and invoicing for the project.
- **Duration:** defines the start and end date of the project.
- **Foreign Trade:** defines details related to projects managed or billed in foreign currency.
- **WIP and Recognition** contains information relating to the management of Work in Progress.

## General Tab
The General tab contains two additional fields:

- Job Category:
- Contract Type 

See [Definitions](Projects-Overview#definitions) for details.

## Project task lines
This subpage contains the work breakdown structure of the project. See [The Work Breakdown Structure](Work-Breakdown-Structure) for more details.

## Project Planning lines
This subpage contains the planning lines, which contain planned cost and planned billing, for a selected task. 
See [Understanding Planning Lines](Understanding-planning-lines) for more details