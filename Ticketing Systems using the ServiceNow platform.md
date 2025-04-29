# ServiceNow Labs: Task Walkthrough

## Objective / Synopsis
This documentation provides a detailed walkthrough of ServiceNow lab exercises, demonstrating hands-on skills in resolving incidents, navigating the Next Experience UI, creating filters and managing lists, and submitting new problem records. The guide outlines each task performed and provides context for how core ServiceNow functionality is applied in real-world support scenarios.


## Task 1 - Resolve an Incident
- Type "Incidents" in the search bar and select the "Incidents" module.

  ![image](https://github.com/user-attachments/assets/125597f5-099e-4cdb-b7c4-06643a6be232)
  
- Click on the incident number you want to resolve to open the incident record.
  
  ![image](https://github.com/user-attachments/assets/2ea1ff3b-7a5c-4f06-af21-bbc95c13155d)

- I selected 'Need access to the common drive.' To resolve the incident, set the "State" field to "Resolved", fill in the resolution notes, and click on "Update".

#### Work Summary
  - Confirmed request details with user, 'shbelay'.
  - Verified which shared drive was needed ([Z:/Folder]).
  - Checked current permissions — user was not a member of the required access group.
  - Added user to [BelayLabGroup] to grant [read and write] access.
  - Asked user to log off and back on (or refresh drive mappings) to see the update.
  - User confirmed access is working.

  ![image](https://github.com/user-attachments/assets/f2bce8f7-66c1-4404-81c3-0ee909fefcd8)
  ![image](https://github.com/user-attachments/assets/7131c6d3-15be-466d-885c-357b917a46f0)


## Task 2 - Next Experience, Navigation, and Access Task
- Navigate to the User Menu and select Impersonate user

  ![image](https://github.com/user-attachments/assets/17aab1b4-84d9-45e9-bb22-375f1c69ba52)

- Locate and select Platform User (platform.user) and select the Impersonate user button

  ![image](https://github.com/user-attachments/assets/666c349f-d43f-4ecb-830d-f23ae11c49bd)

- Now, I am using the Service Now platform as the selected user

  ![image](https://github.com/user-attachments/assets/af7bb12e-48e2-4415-ac67-42ebcda5c437)

- Navigate to All  / Self-Service / Knowledge

  ![image](https://github.com/user-attachments/assets/cfea3a21-09f2-42f4-b77c-d43150d68f74)

- Search for 'Password Reset' and select the title, 'Password reset instructions'

  ![image](https://github.com/user-attachments/assets/463be0a8-e72e-446f-bdc1-abd5361c671b)

- Favorite the article for the user to easily be found in their knowledge base and inform the user of the instructions of how to reset their password

  ![image](https://github.com/user-attachments/assets/ae67a1e6-b1c9-4d05-8e7c-cfb769c5352a)
  ![image](https://github.com/user-attachments/assets/3f37c116-da8d-4e60-b271-fcca0b19cc5d)

- Once completed with task, click 'End impersonation'

  ![image](https://github.com/user-attachments/assets/acd25907-1eaa-43da-b00e-7ab91af2c2d0)


## Task 3 - Lists and Filters Task
- Navigate to the All menu and select Incident > All

  ![image](https://github.com/user-attachments/assets/af45cfc9-5fbd-40a8-bb0c-2a2df390dda5)
  ![image](https://github.com/user-attachments/assets/a1a3ff4b-75f8-4fcd-9b35-66e47eb3e8ee)

- Select Show/hide filter (funnel) icon
- Set the field, operator(filter/condition), and value choice lists to the following:
- State | is not | Closed AND
- Assignment Group | is not empty AND
- Assigned to | is not empty
- Select Run.

  ![image](https://github.com/user-attachments/assets/928cef38-8663-43d7-83d8-012422855668)

- Select the Personalize List (gear) icon to move columns (State, priority, Category and Caller) to the right side by clicking on the ">" button and click ok.

  ![image](https://github.com/user-attachments/assets/4c035c58-d7c3-4395-8143-d7d47e65ad4b)
  ![image](https://github.com/user-attachments/assets/1455d410-e7ed-426d-aa62-76bf11b0eed1)


- Select the State column of all 1-Critical incidents and use the List Editor to change the State to In Progress. Select the green check mark to save the list changes.

  ![image](https://github.com/user-attachments/assets/bfbfce78-72a4-4186-988e-950c23c212d4)
  ![image](https://github.com/user-attachments/assets/2ad7b551-02d0-4b37-8b72-affdc9dd8294)

- Change the View SelfService to Prioirty and Locate INC0000053 and set the Category to Software. Double click on 'Inquiry / Help' and click green check mark to change category.

  ![image](https://github.com/user-attachments/assets/7b8d6e7c-a42f-4d9f-92d9-04c088b91285)
  ![image](https://github.com/user-attachments/assets/97142720-350f-400d-8dca-0985a7d98fe9)

## Task 4: Forms Task
- Navigate to All > Problem > Create New

  ![image](https://github.com/user-attachments/assets/91c14962-ead8-48a4-8930-2c284cdbaceb)

- Fill out the form:
  - Category: Network
  - Service: IT Services
  - Impact: 2 - Medium
  - Urgency: 2 - Medium
  - Assignment group: Network
  - Problem statement: Unable to connect to network server.
  - Description: The department network server seems to be going down multiple times a week and I currently can’t connect to it. We would like a more permanent solution.

  ![image](https://github.com/user-attachments/assets/1c33190d-45f2-4f3b-9a59-029058a475c6)

- Select the Form Context Menu to Save the record.

![image](https://github.com/user-attachments/assets/e57ea7ab-e287-403f-963f-344cf4a2fb9d)

- Select the Form Context Menu and select Create Favorite

![image](https://github.com/user-attachments/assets/b51ad33c-ed9f-44ef-8291-4626e1ba18a0)

- Select Go to Activity Stream to navigate to the section of the form where you can keep track of any Work Notes on the problem.

  ![image](https://github.com/user-attachments/assets/f138c199-22d0-4be4-a0d8-09f7fb043bb7)
  ![image](https://github.com/user-attachments/assets/7d715780-f2c0-42af-921a-e7d320e2ec97)

