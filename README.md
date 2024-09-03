# Soft-Skill-Enhancement-AI-Application

1 Introduction 
1.1 Purpose 
The purpose of Soft Skill Enhancement AI Application is to outline the business requirements for developing an English 
Training App specifically designed for new recruits in a company. This app aims to enhance their vocabulary, speech, and 
pronunciation skills through interactive lessons, practice tests, and detailed test reports. The learning path will be 
customized to meet the needs of the HR department for employee development. 
1.2  Scope 
The app will include the following features: 
 Vocabulary Lessons: Interactive lessons to build and expand vocabulary. 
 Speech Lessons: Modules to improve speaking skills. 
 Pronunciation Lessons: Exercises to enhance pronunciation. 
 Practice Tests: Regular tests to assess learning. 
 Test Reports: Detailed reports on test performance. 
 Learning Path: Personalized learning paths based on test results. 
1.3 Goals 
 To improvoise communication skills of employees. 
 Enhance their vocabulary, speech, and pronunciation skills through interactive lessons, practice tests, and 
detailed test reports.  
 The learning path will be customized to meet the needs of the behavioual training department for employee 
development. 
1.4 Objectives 
 Improve Communication Skills: Enhance the vocabulary, speech, and pronunciation skills of graduate engineers. 
 Interactive Learning: Provide an engaging and interactive learning experience. 
 Performance Tracking: Offer detailed test reports and learning paths to track progress. 
 HR Integration: Enable HR to monitor and support employee development. 
4 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
2 Stakeholders 
2.1 Primary stackholders 
 HR Department: To monitor and support employee development. 
 Graduate Engineers: Primary users of the app. 
2.2 Secondry stackholders 
 Training Department: To provide content and support. 
 Development Team: To build and maintain the app. 
5 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
3 Functional Requirements 
3.1 User Management  
 User Roles: Admin, HR Manager, Recruiter, Interviewer, Candidate. 
 User Authentication: Secure login with role-based access control. 
 User Profiles: Detailed profiles for all users. 
3.2  Vocabulary Lessons 
 Interactive Modules: Lessons with interactive elements like quizzes and flashcards. 
 Difficulty Levels: Beginner, Intermediate, and Advanced levels. 
 Progress Tracking: Track vocabulary learned over time. 
3.3  Speech Lessons 
 Audio Lessons: Recorded lessons to improve speaking skills. 
 Speech Recognition: Feature to practice and get feedback on speech. 
 Interactive Dialogues: Simulated conversations to practice real-life scenarios. 
3.4 Pronunciation Lessons 
 Phonetic Guides: Lessons on phonetics and pronunciation rules. 
 Practice Exercises: Interactive exercises to practice pronunciation. 
 Feedback Mechanism: Real-time feedback on pronunciation accuracy. 
3.5  Practice Tests 
 Regular Assessments: Scheduled tests to evaluate progress. 
 Variety of Tests: Multiple types of tests (e.g., multiple choice, fill-in-the-blank). 
 Instant Results: Immediate feedback on test performance. 
3.6  Test Reports 
 Detailed Analysis: Reports on strengths and weaknesses. 
 Progress Over Time: Track performance over multiple tests. 
 Recommendations: Personalized recommendations for improvement. 
3.7 Learning Path 
 Customized Path: Learning path tailored to individual needs based on test results. 
 Milestones: Set milestones for achieving specific goals. 
 Resource Suggestions: Recommend additional resources for further learning. 
6 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
4 Workflows 
4.1 Workflow Requirement: Role-Based Login (Admin/User) 
Overview 
This document outlines the detailed workflow requirements for implementing a role-based login system for the English 
Training App. The system will have two types of users: Admin and User . Each role will have specific access permissions 
and functionalities. 
Workflow Steps 
1. Login Screen 
Screen Elements: 
 Username/Email Textbox 
o Label: "Username or Email" 
o Placeholder: "Enter your username or email" 
o Validation: 
 Required field 
 Must be a valid email format if email is used 
 Password Textbox 
o Label: "Password" 
o Placeholder: "Enter your password" 
o Input Type: Password (to hide the characters) 
o Validation: 
 Required field 
 Minimum 8 characters 
 Remember Me Checkbox 
o Label: "Remember Me" 
o Function: Keeps the user logged in for a specified period 
 Login Button 
o Label: "Login" 
o Action: Submits the login form 
 Forgot Password Link 
o Label: "Forgot Password?" 
o Action: Redirects to the password recovery screen 
 Sign Up Link 
o Label: "Sign Up" 
o Action: Redirects to the registration screen for new users 
Workflow: 
1. User enters their username/email and password. 
2. User can optionally check the "Remember Me" checkbox. 
3. User clicks the "Login" button. 
4. The system validates the input fields. 
5. If validation passes, the system authenticates the user against the database. 
7 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
6. If authentication is successful, the user is redirected to the dashboard. 
7. If authentication fails, an error message is displayed. 
2. Password Recovery Screen 
Screen Elements: 
 Email Textbox 
o Label: "Email" 
o Placeholder: "Enter your registered email" 
o Validation: 
 Required field 
 Must be a valid email format 
 Submit Button 
o Label: "Submit" 
o Action: Sends a password recovery email 
 Back to Login Link 
o Label: "Back to Login" 
o Action: Redirects back to the login screen 
Workflow: 
1. User enters their registered email address. 
2. User clicks the "Submit" button. 
3. The system validates the email address. 
4. If validation passes, the system sends a password recovery email. 
5. User receives an email with a link to reset their password. 
6. User clicks the link and is redirected to the password reset screen. 
3. Password Reset Screen 
Screen Elements: 
 New Password Textbox 
o Label: "New Password" 
o Placeholder: "Enter your new password" 
o Input Type: Password 
o Validation: 
 Required field 
 Minimum 8 characters 
 Confirm Password Textbox 
o Label: "Confirm Password" 
o Placeholder: "Re-enter your new password" 
o Input Type: Password 
o Validation: 
 Required field 
 Must match the new password 
 Reset Password Button 
o Label: "Reset Password" 
o Action: Submits the password reset form 
8 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
Workflow: 
1. User enters a new password. 
2. User re-enters the new password in the confirm password textbox. 
3. User clicks the "Reset Password" button. 
4. The system validates the input fields. 
5. If validation passes, the system updates the user's password in the database. 
6. User is redirected to the login screen with a success message. 
4. Registration Screen (Sign Up) 
Screen Elements: 
 Full Name Textbox 
o Label: "Full Name" 
o Placeholder: "Enter your full name" 
o Validation: Required field 
 Email Textbox 
o Label: "Email" 
o Placeholder: "Enter your email" 
o Validation: 
 Required field 
 Must be a valid email format 
 Password Textbox 
o Label: "Password" 
o Placeholder: "Enter your password" 
o Input Type: Password 
o Validation: 
 Required field 
 Minimum 8 characters 
 Confirm Password Textbox 
o Label: "Confirm Password" 
o Placeholder: "Re-enter your password" 
o Input Type: Password 
o Validation: 
 Required field 
 Must match the password 
 Sign Up Button 
o Label: "Sign Up" 
o Action: Submits the registration form 
 Back to Login Link 
o Label: "Back to Login" 
o Action: Redirects back to the login screen 
Workflow: 
1. User enters their full name, email, password, and confirm password. 
2. User clicks the "Sign Up" button. 
3. The system validates the input fields. 
9 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
4. If validation passes, the system creates a new user account in the database. 
5. User is redirected to the login screen with a success message 
4.2 Workflow Requirement:User Dashboard  
Overview 
This document outlines the detailed workflow requirements for the User Dashboard of the English Training App. The 
User Dashboard provides access to vocabulary lessons, speech lessons, pronunciation lessons, practice tests, and test 
reports. 
4.2.1. User Dashboard Main Screen 
Description 
The main screen of the User Dashboard serves as the central hub where users can navigate to different    
sections of the app. 
Elements 
 Navigation Menu: Links to different sections (Vocabulary Lessons, Speech Lessons, Pronunciation 
Lessons, Practice Tests, Test Reports). 
 Welcome Message: A personalized welcome message for the user. 
 Quick Access Buttons: Buttons for quick access to recently accessed lessons or tests. 
Workflow 
1. User logs in and is redirected to the User Dashboard main screen. 
2. User sees a personalized welcome message. 
3. User can use the navigation menu to access different sections or use quick access buttons for recently 
accessed content. 
4.2.2 Vocabulary Lessons Section 
Description 
This section provides access to vocabulary lessons designed to build and expand the user's vocabulary. 
Elements 
 Lesson List: Display list of available vocabulary lessons. 
 Start Lesson Button: To begin a selected lesson. 
 Search Bar: To search for specific lessons. 
 Filter Options: To filter lessons by difficulty level (Beginner, Intermediate, Advanced). 
Workflow 
1. User navigates to the Vocabulary Lessons section from the dashboard. 
2. User can browse the list of available lessons. 
3. User can use the search bar to find specific lessons or filter options to narrow down the list. 
4. User clicks the "Start Lesson" button to begin a selected lesson. 
10 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
5. User completes the lesson and returns to the Vocabulary Lessons section. 
4.2.3 Speech Lessons Section 
Description: 
This section provides access to speech lessons designed to improve the user's speaking skills. 
Elements: 
 Lesson List: Display list of available speech lessons. 
 Start Lesson Button: To begin a selected lesson. 
 Search Bar: To search for specific lessons. 
 Filter Options: To filter lessons by difficulty level (Beginner, Intermediate, Advanced). 
Workflow 
1. User navigates to the Speech Lessons section from the dashboard. 
2. User can browse the list of available lessons. 
3. User can use the search bar to find specific lessons or filter options to narrow down the list. 
4. User clicks the "Start Lesson" button to begin a selected lesson. 
5. User completes the lesson and returns to the Speech Lessons section. 
4.2.4 Pronunciation Lessons Section 
Description: 
This section provides access to pronunciation lessons designed to enhance the user's pronunciation skills. 
Elements 
 Lesson List: Display list of available pronunciation lessons. 
 Start Lesson Button: To begin a selected lesson. 
 Search Bar: To search for specific lessons. 
 Filter Options: To filter lessons by difficulty level (Beginner, Intermediate, Advanced). 
 Lesson List: Display list of available pronunciation lessons. 
 Start Lesson Button: To begin a selected lesson. 
 Search Bar: To search for specific lessons. 
 Filter Options: To filter lessons by difficulty level (Beginner, Intermediate, Advanced). 
Workflow 
 User navigates to the Pronunciation Lessons section from the dashboard. 
 User can browse the list of available lessons. 
 User can use the search bar to find specific lessons or filter options to narrow down the list. 
 User clicks the "Start Lesson" button to begin a selected lesson. 
 User completes the lesson and returns to the Pronunciation Lessons section. 
11 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
4.2.5 Practice Tests Section 
Description: 
This section provides access to practice tests designed to assess the user's progress. 
Elements 
 Test List: Display list of available practice tests. 
 Start Test Button: To begin a selected test. 
 Search Bar: To search for specific tests. 
 Filter Options: To filter tests by type (Vocabulary, Speech, Pronunciation). 
Workflow 
 User navigates to the Practice Tests section from the dashboard. 
 User can browse the list of available tests. 
 User can use the search bar to find specific tests or filter options to narrow down the list. 
 User clicks the "Start Test" button to begin a selected test. 
 User completes the test and returns to the Practice Tests section. 
4.2.6 Test Reports Section 
Description: 
This section provides access to detailed reports on the user's test performance. 
Elements: 
 Report List: Display list of available test reports. 
 View Report Button: To view a detailed report of a selected test. 
 Search Bar: To search for specific reports. 
 Filter Options: To filter reports by date or test type. 
Workflow: 
 User navigates to the Test Reports section from the dashboard. 
 User can browse the list of available reports. 
 User can use the search bar to find specific reports or filter options to narrow down the list. 
 User clicks the "View Report" button to view a detailed report of a selected test. 
 User reviews the report and returns to the Test Reports section 
12 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
4.3 Workflow Requirement: Vocabulary Lessons Section 
Overview 
This section outlines the detailed workflow requirements for the Vocabulary Lessons Section of the English 
Training App. This section is designed to help users build and expand their vocabulary through structured 
lessons. 
4.3.1. Vocabulary Lessons Main Screen 
Description 
The main screen of the Vocabulary Lessons Section displays a list of available vocabulary lessons and provides 
options to search, filter, and start lessons. 
Elements 
 Lesson List: Displays a list of available vocabulary lessons. 
o Lesson Title: The title of the lesson. 
o Lesson Description: A brief description of the lesson. 
o Difficulty Level: Indicates the difficulty level (Beginner, Intermediate, Advanced). 
o Start Lesson Button: To begin a selected lesson. 
 Search Bar: To search for specific lessons by keywords. 
 Filter Options: To filter lessons by difficulty level. 
o Beginner Checkbox: To filter beginner-level lessons. 
o Intermediate Checkbox: To filter intermediate-level lessons. 
o Advanced Checkbox: To filter advanced-level lessons. 
Workflow 
 User navigates to the Vocabulary Lessons section from the dashboard. 
 User sees a list of available vocabulary lessons. 
 User can use the search bar to find specific lessons by entering keywords. 
 User can use filter options to narrow down the list by difficulty level. 
 User clicks the "Start Lesson" button to begin a selected lesson. 
 User is redirected to the Vocabulary Lesson Detail Screen. 
4.3.2 Vocabulary Lesson Detail Screen 
Description: 
The Vocabulary Lesson Detail Screen provides detailed information about the selected lesson and allows 
the user to start the lesson. 
Elements: 
 Lesson Title: The title of the lesson. 
 Lesson Description: A detailed description of the lesson. 
 Difficulty Level: Indicates the difficulty level (Beginner, Intermediate, Advanced). 
13 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
 Lesson Content: The content of the lesson, which may include text, images, audio, and interactive 
elements. 
 Start Lesson Button: To begin the lesson. 
Workflow 
 User is redirected to the Vocabulary Lesson Detail Screen after clicking the "Start Lesson" button on the 
main screen. 
 User reviews the detailed information about the lesson. 
 User clicks the "Start Lesson" button to begin the lesson. 
 User is redirected to the Vocabulary Lesson Content Screen. 
4.3.3 
Vocabulary Lesson Content Screen 
Description  
The Vocabulary Lesson Content Screen displays the actual content of the lesson and allows the user to 
interact with the material. 
Elements 
 Lesson Content: The content of the lesson, which may include text, images, audio, and interactive 
elements. 
 Next Button: To proceed to the next part of the lesson. 
 Previous Button: To go back to the previous part of the lesson. 
 Complete Lesson Button: To mark the lesson as complete. 
Workflow 
 User is redirected to the Vocabulary Lesson Content Screen after clicking the "Start Lesson" button on 
the detail screen. 
 User interacts with the lesson content, which may include reading text, viewing images, listening to 
audio, and completing interactive exercises. 
 User can navigate through the lesson using the "Next" and "Previous" buttons. 
 After completing the lesson, user clicks the "Complete Lesson" button. 
 User is redirected to the Vocabulary Lessons Main Screen with the lesson marked as complete. 
4.3.4. Lesson Completion Screen 
Description 
The Lesson Completion Screen provides feedback to the user upon completing a lesson and offers options to 
review the lesson or proceed to the next one. 
Elements 
 Completion Message: A message congratulating the user on completing the lesson. 
 Review Lesson Button: To review the completed lesson. 
 Next Lesson Button: To proceed to the next lesson. 
 Return to Lessons Button: To return to the Vocabulary Lessons Main Screen. 
14 
www.Hexaware.com 
© 2023 Hexaware Technologies Limited. All rights reserved 
Workflow: 
 User is redirected to the Lesson Completion Screen after clicking the "Complete Lesson" button on the 
content screen. 
 User sees a completion message and options to review the lesson, proceed to the next lesson, or return 
to the main screen. 
 User can choose to review the lesson, proceed to the next lesson, or return to the Vocabulary Lessons 
Main Screen
