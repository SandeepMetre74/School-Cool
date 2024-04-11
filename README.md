# School Cool

This is a School Management System application built using MERN stack.Please follow the instructions to set it up

*Features*

- User Authentication: This feature supports the registration, login, and role- based access control for different user types, including administrators, teachers, students, and parents.

- Student Management: This feature allows for the creation, modification, and deletion of student records, including personal information, enrolment status, and academic history.

- Staff Management: This feature enables the administration to manage staff information, including personal. details, employment status, and teaching assignments.

- Course Scheduling: This feature facilitates the creation and management of course schedules, including class timings, room assignments, and instructor allocation.

- Attendance Tracking: This feature allows teachers to record and track student attendance for each class, while administrators and parents can monitor overall attendance trends.

- Grade Management: This feature enables teachers to input and manage student grades, as well as generate report cards and progress reports for parents.

- Parent Portal: This feature provides parents with access to their children's academic information, including attendance, grades, and teacher feedback.

- Communication Tools: This feature offers messaging functionality for direct communication between teachers, students, and parents, as well as group messaging for announcements and notifications.

- Resource Management: This feature allows administrators to manage school resources, such as classrooms, labs, and equipment, and track their usage and availability.

- Dashboard and Reporting: This feature provides users with personalized dashboards and generates various reports to help monitor performance and make data-driven decisions.

*1.Student*

- Can view his/her Attendance detail for each subject

- Can visualize his/her Attendance in a pie chart categorized by subject

- Can view his/her details in profile

- Can view announcements by school admin

- Can view his/her marks on all subjects in all exams

- Can visualise his/her marks as line chart and bar chart

*2.Teacher*

- Has the authority to Update Attendance

- Can view and edit his/her profile

- Can view announcements by school admin

- Has the authority to update marks for students , for the grades and subjects they teach

*3.Parent*

- Has all the features as that of student

*4.Admin*

- Has the authority to approve student and teacher profiles after registration

- Can broadcast the announcements and delete if irrelavent

- Can add subjects to any grade if required

- Has the authority to assign teacher for particular grade and subject , based on teacher's subjects entered while registering.

- For academic purpose Admin userName: admin1 Password: schoolcool

[Working Demo](https://654c5984b5dcf726a4942752--gentle-snickerdoodle-a87926.netlify.app/)

### Instructions

1. Clone the repo and run `npm install`

2.Front end is available in the app folder

3.From the app folder run `npm run dev`

4.Backend is available in the server folder

5.Add environmental variables for JWT secret key and mongodb URL

6.From the server folder run backend using `npm start`

---