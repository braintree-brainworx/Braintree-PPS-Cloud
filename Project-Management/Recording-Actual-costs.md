---
layout: NewLayout
title: Braintree Projects and Professional Services for Business Central
description: Support and documentation for Braintree's Projects and Professional Services extension to Microsoft Dynamics 365 Business Central
---

# Recording Actual Costs
After creating the work breakdown structure (WBS), assigning resources and setting a baseline, you are ready to start work on the project.

From the project card, change the status from Planning to Open:

![alt text](proj_images/image-36.png)

Costs can be assigned to a project by:
- [Capturing time sheets for resources](#resource-time-sheets)
- [Capturing purchases against the project](#purchase-requisitions-orders-and-invoices)
- [Capturing project journals to issue inventory to projects, or to assign general expenses to projects](#project-journals)

# Resource Time Sheets
If you want to track the cost of work performed on a project by your own resources, you can use the standard time sheet functionality in Business Central. This allows you to:

- have individual users record the time they spent working on project tasks
- have line managers review and approve the resources' time sheets
- post the costs to the project after review

![alt text](TimeSheetProcess.drawio.png)

Refer to Microsoft documentation on how to set up, capture and post time sheets.

## Purchase Requisitions, Orders and Invoices
Purchases for inventory items or general expenses can be linked to projects, using a requisition or order. The purchase document must be validated to verify that sufficient budget is available. Once the document is validated and approved, the cost will reflect on the project as committed budget. Thereafter, the process follows the standard Business Central process, where the requisition is converted to the order, the order is received, and then invoiced.

 ![alt-text](Purchases.drawio.png)

## Create a Purchase Requisition
From the project card, select Purchases -> Purchase Requisitions:

![alt text](image-10.png)

Click New to create a new purchase requisition. An empty purchase quote will be opened.
Select a vendor, and complete the remaining details. Note that the Project number is populated, and budget status is set to 'Not Checked'.

Capture the items being purchased for the project. These could be items or GL Accounts. 
Scroll to the right of the Lines subpage, until the Project fields are visible:

![alt text](image-11.png)

Click in the Project Task No. column, and select a task number.

Note that the budget status is set to 'Not Checked', and the Budget Available is zero.

After capturing all the lines for the requisition, click on 'Validate Budget':

![alt text](image-12.png)

The system checks the amount requested on each line, against available budget for the task and type (ie item or GL account). If budget is available for the line, the status changes to 'Reserved'. If there is not enough budget, the status changes to 'Insufficient'. 

# Project Journals
Project journals allow you to assign resource costs, material costs or general ledger expenses to a project task.

Search for and open 'Project Journal'.  On the journal page, capture the costs as follows:

|Column | Description |
|---|---|
