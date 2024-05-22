# Gym-Trainer-Database
The Flex Trainer Management System is developed in C# using Windows Forms and SQL Server for backend database management. It is designed to assist gym owners, trainers, and members by providing a large, user-friendly database that simplifies the process of record-keeping and fitness goal management. This application caters to the needs of different users by offering distinct interfaces for members, trainers, gym owners, and admins.

Features
Member Functionality
Create and View Diet Plans: Tailor diet plans to individual goals, including nutritional details and allergen information.
Access Exercise Library: Create and customize exercises based on personal preferences.
Workout Plans: View and create personalized workout plans.
Meal Logging: Log and track meals, with the ability to view historical data.
Training Session Booking: Book training sessions with available trainers.
Trainer Functionality
Exercise Library Access: Create and manage exercises.
Workout Plan Management: Create, view, and customize workout plans for clients.
Diet Plan Management: View and create diet plans for clients, track meals.
Booking Management: Approve or disapprove booking sessions with members.
Owner Functionality
Member Reports: Generate detailed reports for performance analysis.
Trainer Reports: Assess trainer performance and progress.
Account Management: Add or remove trainers and members as needed.
Admin Functionality
Gym Performance Monitoring: Access detailed analytics and reports.
Gym Requests: Approve or revoke gym registration requests.
Database Schema
Tables
BookingSessions
BookingID
Date
Time
Duration
Price
Status
TrainerID
MemberID
DietPlan
PlanID
PlanName
User_ID
Breakfast
Lunch
Dinner
Exercise
ExerciseID
ExerciseName
Sets
Reps
Goal
Type
Exercise_Machine
EM_ID
MachineID
ExerciseID
Feedback
FeedbackID
Review
Rating
BookingID
GymPerformance
PerformanceID
MembershipGrowth
FinancialPerformance
ClassAttendanceRates
CustomerSatisfaction
GYM_ID
GymRequests
ReqID
Name
Location
Status
Gyms
GymID
Name
Location
OwnerID
Machine
MachineID
Name
Last_Used
Meals
MealID
MealName
Carbohydrates
Fats
Proteins
PortionSize
Allergens
RegistrationRequests
RequestID
TrainerID
AdminID
USER_GYM
UserID
GymID
JoiningDate
USERS
UserID
FName
LName
Gender
Address
Phone_No
CNIC
Username
Password
Type
Workouts
WorkoutID
Workout_Name
User_ID
Exercise_1
Exercise_2
Exercise_3
Audit
ID
Action
Time

Sure, here's a comprehensive README for your Flex Trainer management system project, integrating all the provided details:

Flex Trainer Management System
Welcome to the Flex Trainer Management System, a comprehensive application designed to streamline and automate the management of gyms and health membership systems. This application helps gym owners keep detailed records of registered members, guides users through personalized workout and diet plans, and facilitates various administrative tasks through an intuitive user interface.

Overview
The Flex Trainer Management System is developed in C# using Windows Forms and SQL Server for backend database management. It is designed to assist gym owners, trainers, and members by providing a large, user-friendly database that simplifies the process of record-keeping and fitness goal management. This application caters to the needs of different users by offering distinct interfaces for members, trainers, gym owners, and admins.

Features
Member Functionality
Create and View Diet Plans: Tailor diet plans to individual goals, including nutritional details and allergen information.
Access Exercise Library: Create and customize exercises based on personal preferences.
Workout Plans: View and create personalized workout plans.
Meal Logging: Log and track meals, with the ability to view historical data.
Training Session Booking: Book training sessions with available trainers.
Trainer Functionality
Exercise Library Access: Create and manage exercises.
Workout Plan Management: Create, view, and customize workout plans for clients.
Diet Plan Management: View and create diet plans for clients, track meals.
Booking Management: Approve or disapprove booking sessions with members.
Owner Functionality
Member Reports: Generate detailed reports for performance analysis.
Trainer Reports: Assess trainer performance and progress.
Account Management: Add or remove trainers and members as needed.
Admin Functionality
Gym Performance Monitoring: Access detailed analytics and reports.
Gym Requests: Approve or revoke gym registration requests.
Database Schema
Tables
BookingSessions
BookingID
Date
Time
Duration
Price
Status
TrainerID
MemberID
DietPlan
PlanID
PlanName
User_ID
Breakfast
Lunch
Dinner
Exercise
ExerciseID
ExerciseName
Sets
Reps
Goal
Type
Exercise_Machine
EM_ID
MachineID
ExerciseID
Feedback
FeedbackID
Review
Rating
BookingID
GymPerformance
PerformanceID
MembershipGrowth
FinancialPerformance
ClassAttendanceRates
CustomerSatisfaction
GYM_ID
GymRequests
ReqID
Name
Location
Status
Gyms
GymID
Name
Location
OwnerID
Machine
MachineID
Name
Last_Used
Meals
MealID
MealName
Carbohydrates
Fats
Proteins
PortionSize
Allergens
RegistrationRequests
RequestID
TrainerID
AdminID
USER_GYM
UserID
GymID
JoiningDate
USERS
UserID
FName
LName
Gender
Address
Phone_No
CNIC
Username
Password
Type
Workouts
WorkoutID
Workout_Name
User_ID
Exercise_1
Exercise_2
Exercise_3
Audit
ID
Action
Time
Reports
The following are some of the critical reports that the Flex Trainer Management System can generate:

Details of Members Trained by a Specific Trainer: Information on members trained by a specific trainer at a specific gym.
Diet Plan Details: Members following a specific diet plan at a gym.
Diet Plan Followers: Members across all gyms of a specific trainer following a specific diet plan.
Machine Usage Count: Members using specific machines on a given day at a specific gym.
Low-Calorie Breakfast Plans: Diet plans with meals under 500 calories for breakfast.
Low-Carb Diet Plans: Diet plans with total carbohydrate intake below 300 grams.
Workouts Without Specific Machines: Workout plans that do not require specific machines.
Allergen-Free Diet Plans: Diet plans without peanuts as allergens.
New Membership Data: New memberships in the last three months.
Membership Comparison: Comparison of total members across multiple gyms over the past six months.
Technology Stack
Programming Language: C#
Database: SQL Server
Framework: .NET Framework
GUI: Windows Forms (WinForms)
Installation and Setup
Prerequisites
Windows Operating System
.NET Framework
SQL Server
Contributions to improve the Flex Trainer Management System, fix bugs, or add new features are welcome. Please fork the repository, make your changes, and submit a pull request. Your contributions will help make this application even more effective and user-friendly.
