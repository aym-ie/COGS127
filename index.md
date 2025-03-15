# COGS 127 Case Study

Alice Ma, Kelly La, Jessica Ouyang, Amy Yee

## Background
In a medical setting, the medical receptionists are the first point of contact for patients in person and over the phone. In general, they are responsible for organizing the medical office's operations. 

Our two stakeholders, both medical receptionists, ensure the smooth running of the medical office by communicating with clients/patients, managing schedules, making appointments, addressing patient inquiries, and more.

In a typical workday, medical receptionists rely on multiple digital tools to streamline workflow. However, inefficiencies in these systems often lead to frustration and delays in patient care. By exploring their experiences and challenges, this project aims to identify opportunities to improve workflow efficiency and enhance the overall patient care experience.

## User Research Method
We are conducting **two stakeholder interviews**. We conducted the first interview before Milestone 1 and conducted the second interview before Milestone 2.

**Stakeholder 1:** The person I have contacted is the head intern of the research department. He leads interns in the research department, organizing shifts, coordinating tasks, and training interns. He also does work with papers that his department is working on as well as a large project that the clinic is involved in.

**Stakeholder 2:** The person I have contacted for this project is someone working at NEMS front desk in San Francisco. She has been working there for around 30 years. She works front desk on the pediatrician floor and is responsible for taking calls, making appointments, and organizing schedules for her co-workers.

<br>

#### Pre-Interview and Set-Up Questions
We met up with our stakeholders in person and conducted an interview for 1-1.5 hours. To start off our interview, we told the stakeholders that the goal of the interview was to learn more about how they interact with applications at work, in hopes of gaining insight about challenges/frustrations that they face. We also made sure to inform them that being a stakeholder involved providing feedback and testing for future milestones.

**Photograph consent:** We will not be asking to take photos/videos due to the information being confidential to protect the patient's privacy and security.

**Audio consent:** Additionally, do we have your permission to record audio of your interview responses for us to analyze later?

[Stakeholder 1 Interview Response](interview-responses/stakeholder1-interview-response.md)


[Stakeholder 2 Interview Response](interview-responses/stakeholder2-interview-response.md)


<br>

### User Research Findings
#### Stakeholder 1
**Pain Points**
- eCW is frustrating; software seems old, and can only interact with one window at a time; requires too many clicks to complete simple navigation
- To go back to a previous window, eCW requires you to exit out, which could cause a break in workflow and information loss
- Cannot cross-reference different windows (violating “recognition rather than recall”)

**Wishes and Desires**
- Stakeholder 1 wishes that eCW has a more efficient “order of things”

**Opportunities/Gaps**
- Explore electronic medical record systems and identify how to enhance user workflow

<br>

#### Stakeholder 2
**Pain Points**
- EPIC restricts 2 people from viewing the same patient file, resulting in delayed patient care. 
- Schedules and availability on Excel Sheet need to be manually updated for each day
- Frustrated with repetitive actions
- Need to keep track with last minute schedule changed manually
- Stakeholder needs to ask patient the same pre check-in questions every time they come in (even if the patient is visiting frequently), which feels repetitive for the stakeholder 


**Wishes and Desires**
- Stakeholder 2 wishes there was an auditory way to notify others when someone wants to view the file they are on

**Opportunities/Gaps**
- Explore electronic medical record systems and identify how to reduce restrictions to create a more efficient user workflow


<br>

## Problem Statement
Through our stakeholder interviews, we found that medical administrators in clinics struggled with record management systems that lack automation and required switching between multiple programs to complete a task. As a result, our stakeholders experienced frustration with having to swap between multiple windows, causing delays in updating critical records.



<br>

## Personas
**Persona 1**
![Persona 1](images/Persona-1)

**Persona 2**
![Persona 2](images/Persona-2)


## Competitive Audits
### NexGen Health
![NexGen Health Logo](images/netgen-health-logo.png)


**Description:** A cloud-based healthcare suite that focuses on practice management, including scheduling and patient records. Relevant to your efficiency concerns.

**Strengths:**
- Comprehensive electronic health records system with built-in scheduling
- Strong customize for different clinic sizes
- Mobile accessibility for patient portals

**Weaknesses:**
- Cluttered UI that is unintuitive to use
- Heavy training required for new users
- Limited automation for appointment scheduling and confirmation

<br>

### Oracle Health
![Oracle Health Logo](images/oracle-cerner-logo.png)


**Description:** Another major healthcare platform offering scheduling, patient records, and communication tools. Addresses similar workflow challenges mentioned in your statement.

**Strengths:**
- Widely used at the enterprise level as a electronic health record
- Utilizes AI-powered analytics to show patient insights

**Weaknesses:**
- Complex UI which complicate simple tasks for receptionist
- Reportedly there have been lags in performance

<br>

### Athena Health
![Athena Health Logo](images/athena-health-logo.png)


**Description:** A cloud-based healthcare suite that focuses on practice management, including scheduling and patient records. Relevant to your efficiency concerns.

**Strengths:**
- Cloud based system with user friendly design
- Automated reminders for appointments
- Virtual visit capabilities

**Weaknesses:**
- Limited customization for different practice needs
- Scaling challenges for larger medical groups

<br>

### Calendly
![Calendly Logo](images/calendly-logo.png)


**Description:** A software company that develops a business communication platform used for teams to schedule, prepare and follow up on external meetings.

**Strengths:**
- High ease of use with minimal training required
- Automated scheduling system
- Ideal for multi-party scheduling coordination

**Weaknesses:**
- Not an electronic health records system
- Limited app scope (not directly related to medical field)


<br>

## UX Flows
### Flow 1: Checking-In
Currently, our stakeholder has to help patients check-in, which requires asking patients the same questions every time they come in. The stakeholder feels that this is repetitive, so our goal for this flow is to redesign the flow of checking in patients to reduce load for stakeholders. This flow lays out a self-service pre-check-in feature for patients to enter their personal information, which aims to minimize repetitiveness and load for receptionists.

![Flow 1 UX Flow](images/flow-1-ux-flow)


### Flow 2: Updating Patient Records
Currently, our stakeholders have to constantly switch between different websites and windows in order to update patient records. Our goal for this flow is to make it easier to update patient records without constantly switching between websites and windows. To accomplish this, this flow will allow users to update patient records within a single, integrated system, minimizing the need to switch between multiple websites and windows

![Flow 2 UX Flow](images/flow-2-ux-flow)



<br>

## UI Sketches
### Flow 1: Checking-In
![Flow 1 UI Sketch](images/flow-1-ui-sketch.png)


### Flow 2: Updating Patient Records
![Flow 2 UI Sketch](images/flow-2-ui-sketch.png)


<br>

## Low-Fidelity Wireframe Prototype
### Flow 1: Checking-In
![Flow 1 Low Fidelity Flow](images/flow-1-lofi.png)

[Link to Prototype](https://www.figma.com/proto/aRmk24vQ6H81aRd88dIVVg/cogs-127-case-study?page-id=35%3A400&node-id=228-1714&viewport=-108%2C356%2C0.07&t=gyHjJPVw2ThfdaxC-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=228%3A1714&show-proto-sidebar=1){:target="_blank"}

### Flow 2: Updating Patient Records
![Flow 2 Low Fidelity Flow](images/flow-2-lofi.png)

[Link to Prototype](https://www.figma.com/proto/aRmk24vQ6H81aRd88dIVVg/cogs-127-case-study?page-id=35%3A400&node-id=228-2682&viewport=-108%2C356%2C0.07&t=gyHjJPVw2ThfdaxC-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=228%3A2682&show-proto-sidebar=1){:target="_blank"}

### Low Fidelity Design Decisions
We decided to do two different prototype flows to show the two main problems our stakeholders had. Each of the flows will help with different issues. Flow 1 alleviates the frustration of repetitively asking the same questions to help patients check in by providing a self-check-in option. Patients will be able to carefully read the questions at their own pace and edit any information on their profiles. This low-fidelity prototype follows the UX flow of milestone 3 but combines the UI sketch flows for flow 1 of milestone 3. We chose these specific UI designs to maximize clarity and visibility so that users can easily see their information without it being too cluttered and confusing. We kept the homepage simple and straightforward and used concise panels for the homepage and the view appointments page so that patients can view more information at a glance. The check-in questionnaire should have enough information to be self-explanatory, and the confirmation page is clear and does not require scrolling.

Flow 2 differs by addressing a different stakeholder issue. Rather than focusing on the repetitive check-in process, flow 2 aims to assist stakeholders by simplifying their workflow. Currently, our stakeholders need to switch between different programs and windows to update patient records, so flow 2 aims to streamline this process and limit the amount of switching between programs. Our low-fidelity prototype for flow 2 matches our UX flow for milestone 3. The prototype mostly matches our UI sketches, with only a few screens differing. Screen four, spine x-rays, has been changed to make the contact names and information more visible. This flow adds a built-in communication system so that our stakeholders will be able to retrieve and update patient files and results without needing to switch to a different program. The user will be able to contact other departments on the same website as well as add the newly acquired files without having to manually download and upload the files. This will streamline the process and reduce the amount of program switches in a workflow.


<br>

## User Testing Results
### Methods
For our user test, we interviewed two stakeholders. One stakeholder is a head intern at a neurosurgery clinic, and the other is an ER intern. We found them through contacting mutual friends.

Our interview questions include two tasks, one per flow. After each task, we asked the participants a series of follow-up questions about the prototype, so that we can understand what they liked/disliked about it, as well as identify any areas of frustration and confusion.

**Tasks:**

**1. Check-In (Flow 1)**
- Scenario: A patient comes in for their appointment and needs to check in. You inform the patient to complete a self-service online check-in. Complete the check-in process from the patient’s perspective.

**2. Update Record (Flow 2)**
- Scenario: You need to update a patient’s medical record. Find the first patient, and update their x-ray records by contacting the company through email. View the email and update the x-ray records.

<br>

[Stakeholder 1 Feedback](/interview-responses/stakeholder1-feedback.md)


[Stakeholder 2 Feedback](/interview-responses/stakeholder2-feedback.md)


### Findings
**Flow 1: Check-In**

Our first user thought that the check-in flow satisfies the general requirements of typical check-in at a clinic. He liked how the flow's design was very bare and simple because it makes it easier for patients to check in. FOr this flow, he thought that the steps were clear and did not get confused by any of the steps.

Our second user thought that this check-in process was straightforward and efficient since it only required a Login and a few questions. They thought the button was easy to distinguish which made navigation easy. Something they didn’t like was how some aspects were too similar when they are not related which could cause confusion. Overall, Flow 1 was found to be more intuitive than Flow 2 since they didn’t need to think twice about what to do on each page.


**Flow 2: Updating Patient Record**

Our first user thinks that this flow would be very efficient for use in the office because everything was accessible from a singular interface, without the need to browse through many different websites to update a patient’s records. While he didn’t struggle with using this prototype, he brought feasibility into question because it seems difficult for such a currently complex process to be boiled down to one interface; however, if it is possible, he thinks that it would be amazing. One thing he was confused about was the email feature and the types of files that can be received through it.

Our second user this flow made updating medical records efficient since there were no unnecessary complexities. They liked that they can send messages within the interface instead of reaching externally. Something they didn’t like was how some buttons were not obvious. A worry they have is distinguishing patients with similar name/age and suggest clearly patient identifiers. Another worry would be the incoming message notification as it could be hard to keep track of messages.

**Overall**

Our first user found both flows equally intuitive but thought that the second flow would be more useful for his current workflow, as his position requires him to upload patient medical files and communicate with other companies.

Our second user found the first flow more intuitive since the second one had less intuitive icons. This user also thought that the first workflow would save a lot of time since they usually input all of that information by themself. The user thought that this flow would save time for them and the patients.

<br>

## Point of View Statement
During user testing, we discovered that users liked both prototypes. Our users liked the simplicity of flow 1 because of the lack of unnecessary information. While the prototype for flow 1 would reduce the workload for our users, this prototype is meant to be used by patients rather than our stakeholders. They found it confusing on how it would be implemented in real life. For flow 2, our users liked that it simplified the process by using a single interface, but our stakeholders were concerned about the feasibility of combining multiple processes into one. We believe flow 2 should be further developed based on our stakeholders frequent tasks.

<br>

## High Fidelity Prototype
Since flow 1, checking in, is meant to be used by patients rather than medical professionals, we decided to focus on our second flow, updating patient records, for the high fidelity prototype.

![High Fidelity Prototype Flow](/images/flow-2-high-fidelity.png)

[Link to Flow 2 High-Fidelity Prototype](https://www.figma.com/proto/aRmk24vQ6H81aRd88dIVVg/cogs-127-case-study?page-id=89%3A520&node-id=136-1119&viewport=-319%2C137%2C0.09&t=suo0pSn3dL4YdwDX-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=136%3A1119){:target="_blank"}


### High Fidelity Design Decisions

Our high-fidelity prototype implements our original flow 2 from Milestone 3, matching the low-fidelity prototype from Milestone 4. We made some UI changes to the pages so that all the information can be easily skimmed through. We made some changes to our patient profile page, formatting the information cards so that more information can be looked through with a single glance. On our patient list page, there was previously a concern about finding a patient who might have the same as someone else, so we added an account number to distinguish different patients. On the patient documents page, the contacts and document list are side-by-side so the user can easily find the department for the file they need. Instead of just the email popup when viewing emails, we formatted the page to be more like an email inbox so that users can view past emails as well. Emails regarding specific patients can be found under the patient profile page, making it easy for our users to assign a file to the patient’s documents.

We decided to make the high-fidelity prototype for our second flow because our first flow was more focused on the patients rather than our stakeholders. Our first flow indirectly helps our stakeholders by lessening their workload but since the program is meant to be used by the patients and not the medical workers, we decided to focus our high fidelity on our flow 2, which will be used by the stakeholders directly. This was the main idea of our point of view statement, so we decided to improve the UI and functionality of flow 2 to make it easier for our stakeholders to use.

Through our user testing in Milestone 5, we learned that some of our buttons and features were not as obvious as we thought they would be, so we added features and hover effects to increase visibility. Another main concern was distinguishing different patients with the same names and birthdates, so we added unique account IDs. The last concern was about keeping track of notifications, which is why we added the inbox feature rather than just an overlay or singular email page. These changes are part of what we wanted to improve in our plan for next steps.

<br>

### Alternate Versions
**Alternate Version 1**
![Alternate Version 1 Original](/images/alt-1-original.png)
*Original*

![Alternate Version 1 Alternative](/images/alt-1-new.png)
*Alternative*


In our alternate screen, we decided to modify the top navigation bar so that the user can keep track of incoming notifications. To reduce the cognitive load on our users, the improved top bar can help with keeping track of email notifications, with the top as the most recent. In our current design, the only way to keep track of recent emails is through individual patient pages, which might be difficult if the user forgets which patient or the ID they were recently looking at. Our alternative screen makes it easier for the user by allowing the user to reference recent notifications and the patient the notification is about.

<br>

**Alternate Version 2**
![Alternate Version 2 Original](/images/alt-2-original.png)
*Original*

![Alternate Version 2 Alternative](/images/alt-2-new.png)
*Alternative*


In this alternative screen, we redesigned the way our user moves a file into patient documents. In the original version (left), the patient docs are organized in a list of folders that each have a “move here” button. In the alternative version (right), we decided to minimize the repetitiveness of the button and rearranged the folders into a grid view with a singular “move to [folder name]” button at the bottom. The alternative design highlights which folder has been selected by filling the folder blue and specifying the selected folder in the “move” button’s text label. From user testing next week, we hope that we can learn which method of interaction and organization the users prefer (grid vs. list) and whether they prefer multiple or one “move” button.


## Refining the High Fidelity Prototype


### User Feedback for High Fidelity Prototype

For our informal user testing, we asked our two users to go through the original flow from milestone 6, and asked them to give us overall feedback. Then, we showed them our two alternative screens, and asked them to tell us their thoughts about the different versions.

[Feedback from User 1](/interview-responses/user-1-high-fidelity.md)

[Feedback from User 2](/interview-responses/user-2-high-fidelity.md)
<br>

### Final Design
Using the feedback from our user testing, we made some changes to our prototype to improve workflow and make it easier for users to understand the components that were found to be initially confusing. There were also additions to reduce cognitive load and we included a way to customize your view preference between grid and list views.

![Flow 2 High Fidelity Updated Prototype](/images/flow-2-high-fidelity-updated.png)
[Link to Flow 2 High-Fidelity Prototype](https://www.figma.com/proto/aRmk24vQ6H81aRd88dIVVg/cogs-127-case-study?page-id=89%3A520&node-id=136-1119&viewport=-319%2C137%2C0.09&t=suo0pSn3dL4YdwDX-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=136%3A1119){:target="_blank"}
<br>

### Design Decisions for the Improvements
**Scrollable:** Based on our feedback, users think the prototype should be scrollable because it will give users a better idea of how the actual website functions. We decided to make it scrollable because it will be a better representation of the real website. The main features we made when making the prototype scrollable was to make the header sticky. This will allow users to easily navigate throughout the website.

**Inbox:** Both of the feedback we received favored alternative option for viewing the message inbox. For our final design, we will be including an inbox icon on the top right corner because it will be easier to find and see when there is a new message. Users can preview their new messages without switching to a new page. We think this will improve the user's experience because they can view their new messages anywhere on the website since it will be in the header.

**List & grid view:** Another improvement we will be making is creating a list & grid view because based on our feedback, our users prefer viewing files in grid view. By providing both options, people can customize their experience to their own preferences. So between our original and alternative 2 screens, we decided to combine both of them and allow the user to toggle between them.

**Search bar:** We will change the design of the search bar to make it more obvious that users can just click onto the search bar and type. We will do this by making the search icon and the text “Search” next to each other. This change is based on feedback we received from Dave because he had a little confusion on how the search bar worked.

<br>

### Before and After
![Screen 1 Changes](/images/flow-2-screen-1-before-after.png)

Based on our feedback, we discovered that users generally preferred to view documents/folders in a grid view rather than a list view. To address this issue, we decided to add a toggle for switching between grid/list view, with grid view as the default option. This way, we are addressing the fact that a majority of our users prefer the grid view without fully taking away the option to view folders in a list. And there was concern about keeping track of notifications, which is why we added the inbox feature rather than just an overlay or singular email page.

<br>

![Screen 2 Changes](/images/flow-2-screen-2-before-after.png)

Based on feedback, we found that there was concern about how the search bar functioned, whether it was a direct input field or a button that led to a text input field. Since we wanted to convey that users can type directly into it, we revised it to match the standardized search bar UI, so that it conveys the behavior of a typical search bar. Additionally, we received feedback about the appearance of the sort and list icons. Specifically, there was inconsistent padding and confusion about what the “list” icon does. To address this, we redesigned the sort icon and adjusted spacing, and also added a filter icon. Also, we used the list/grid view toggle from the patient docs screen to provide some clarity on the functionality.
