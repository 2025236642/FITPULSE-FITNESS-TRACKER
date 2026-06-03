FitPulse - Fitness Tracker
a. Project Title & Description
FitPulse is a comprehensive, client-side web-based fitness tracker designed to help users monitor their daily workouts, nutrition intake, and overall health progress. With a focus on interactive data visualization and a modern glassmorphism UI, FitPulse allows users to set personal goals, track their hydration, calculate their BMI, and view their fitness trends over time—all within a single-page application.

b. Features Included
Authentication & Security

User Registration and Login system.
Password validation and change password functionality.
Session management using browser storage.
Dashboard

Daily summary stat cards (Calorie Goal, Burned, Eaten, Steps) with progress bars.
Daily hydration tracker (interactive water glass toggle).
Daily motivational mindset quote.
Macronutrient breakdown (Doughnut chart).
Calorie Balance chart (Grouped bar chart comparing Calories Eaten vs. Burned over the last 7 days).
Workouts

Add, view, and delete workout logs (Running, Cycling, Weightlifting, Yoga, HIIT, Walking).
Track duration, calories burned, and steps per workout.
Workout Type Distribution chart (Doughnut chart showing the percentage breakdown of different workout types with a custom legend).
Nutrition

Log meals with detailed macronutrient breakdown (Calories, Protein, Carbs, Fats).
Categorize meals by type (Breakfast, Lunch, Dinner, Snack).
View and delete meal history.
Progress

Weight logging with a line chart trend visualization.
Automatic BMI Calculator (based on logged height and weight).
Lifetime stats tracking (Total Workouts, Total Calories Burned).
Weekly calories burned bar chart.
Achievement badges based on milestones.
Profile

Update personal information (Name, Email, Height, Age, Target Weight).
Customize daily fitness goals (Calorie goal, Step goal).
Secure password update functionality.
UI/UX

Fully responsive design (Mobile-friendly with a collapsible sidebar).
Dynamic page backgrounds.
Glassmorphism styling with smooth transitions.
c. Instructions to Test Login
Since the application uses localStorage for its database, a default admin account is automatically generated the first time the page loads. You can use these credentials to test the login:

Default Test Credentials:

Email: admin@test.com
Password: 1234
Alternatively, you can click "New user? Create Account" on the login page to register a brand-new account. (Note: Passwords must be a minimum of 4 characters).

d. Frameworks/Libraries Used
Bootstrap 5.3.0 - For responsive layout, grid system, and structural components.
Chart.js - For rendering interactive data visualizations (Doughnut, Bar, and Line charts).
Google Fonts (Outfit) - For clean, modern typography.
Vanilla JavaScript (ES6) - For application logic, DOM manipulation, and state management.
Web Storage API (localStorage & sessionStorage) - For simulating a backend database and managing user sessions.