# User Stories

## 1) As a student I would like one platform to view timetables, exams and plan my week so I don't have to open and log in to multiple websites, saving me time.
### Acceptance Criteria: Given the student is logged into the platform, when they open the dashboard, then they can view their timetable, exams, and weekly plan in one place.
### Test Case:
### Precondition: User is a registered student with an existing timetable, an upcoming exam and at least one entry plan
### Input: Student login credentials that are valid
### Action: 
1.	Login to the system
2.	Navigate to the main dashboard
### Expected Results: 
•	Timetable displays current week’s classes
•	Upcoming Exams section lists scheduled exams
•	Weekly Planner section displays the student’s personal weekly plan 
•	All these elements are visible on the main page without needing to navigate to different pages

## 2) As a module organiser I would like my announcements to be visible to as many students as possible, so vital information is not overlooked.
### Acceptance Criteria: Given the module organiser creates an announcement, when the announcement is published, then it is visible to all students enrolled in the module.

## 3) As a lecturer, I would like my students to be notified of any changes to the occurrences of my lectures to ensure maximum engagement with my teaching.
### Acceptance Criteria: Given the lecturer updates or changes a lecture occurrence, when the change is saved, then all students enrolled in the lecture are notified of the update.

## 4) As a student, I would like to schedule a study time so, I can manage my time effectively.
### Acceptance Criteria: Given the student enters study time details, when they submit the form, the system validates the required fields and prevents invalid or overlapping time entries.

## 5) As a student, I want to add my coursework deadlines to my planner, so I can keep track of all my assignments in one place.
### Acceptance Criteria: Given the student has added coursework deadlines, when they view their planner, then all coursework deadlines are visible and organised by date.

## 6) As a student, I want to get notified about a deadline 2 weeks before it's due, so I don't forget to complete it on time.
### Acceptance Criteria: Given the notification is generated, when it is delivered to a student, then it is sent out reliably without duplicaiton or failure. 
### Test Case:
### Precondition: A coursework deadline is set for 14 days from current date on the system
### Input: Automated system trigger for the 14-day reminder
Action:
1.	Trigger the notification 
2.	Check the student’s notification inbox and email
3.	Check system logs for send status 
### Expected Result:
•	Student receives exactly one notification
•	Notification timestamp matches the scheduled trigger time
•	Check to ensure the student receives only once and no duplicate notifications recorded on the system


## 7) As a teacher, I want to update lecture timetables in case there is a change of schedule.
### Acceptance Criteria: Given timetable updates occur, when the system processes the change, then the data is saved securely without corruption or loss. 
 




