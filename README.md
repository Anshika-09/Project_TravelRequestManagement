# Project_TravelRequestManagement
Travel Request Management Application - power apps integrated with SharePoint List and Power automate

I recently wrapped up a detailed project develop an application where employees can raise a travel request for business purpose. The project is shown power apps integrated with SharePoint List and Power Automate to building an interactive application.

This application involves two processes-
1. Request submission
2. Request approval by approver

Key Features:

📁 SharePoint List : TravelRequests

Title (renamed to Employee Name)

SubmittedDate, Date of Travel, Status

Department, Position, Approver

Mode of Transportation, Destination

Status (Pending / Approved / Rejected)
 
📱 PowerApps Screens Overview :
Screen 1: Landing Screen
3 tiles: Submit Request, My Requests, Approve Requests

Screen 2: Travel Request Form
Create/edit travel request (linked to SharePoint)

Screen 3: My Requests
View own submitted requests via gallery
Filter/search by status
"View Request" button → opens request in View Mode

Screen 4: Approver Screen
Shows requests assigned to the logged-in approver
Can update Status field (approve/reject/Pending)
 
🔄 Power Automate Flows:
Flow 1: Email to Approver
Trigger: New item created in SharePoint
Sends email to selected approver, CC to submitter
Includes link back to PowerApps

Flow 2: Email to Submitter
Trigger: Item updated AND Status is changed to Approved/Rejected
Sends outcome email to submitter, CC approver

Role-based access to requests (Submitter vs Approver): 

by creating this Travel Request Management application, I contributed to enhancing operational efficiency, and improved overall business performance. This project showcase my expertise in leveraging advanced technology to create practical solutions that derive business success.
 
🔧 Tools & Technologies Used :

Microsoft PowerApps : Frontend form and screens for request submission and approval
SharePoint List : Backend data storage
Power Automate (Flow) : For sending automated email notifications
Outlook Connector : For sending emails
People Picker Control : For selecting the approver
Dropdowns : Used for Departments, Positions, Destinations, etc.
