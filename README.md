# mobile-app-final-docs
Final documentation for mobile application project
My Four Pack Abs – Mobile Application Documentation

1. Purpose of the Site

“My Four Pack Abs” is a mobile web application designed to help men aged 40 and older build consistent fitness habits without extreme programs. The app provides simple workouts, nutrition guidance, progress tracking, and habit-building tools to support long-term health and visible results.

The application demonstrates mobile development concepts using jQuery Mobile, including navigation, lists, forms, panels, and HTML5 Web Storage.

⸻

2. Site Map (Application Structure)

The application consists of the following pages:
	•	Home Page
	•	Workouts Page
	•	Workout Detail Page
	•	Nutrition Basics Page
	•	Nutrition Detail Page
	•	Progress Tracker Page
	•	Progress Tip Page
	•	Favorites Page
	•	Check-In Form Page

⸻

3. Page Descriptions and Button Functions

Home Page
	•	Menu Button (Panel)
Action: Opens side navigation panel
Result: Allows quick navigation to all sections
	•	Workouts Link
Action: User selects workouts
Result: Navigates to Workouts Page
	•	Nutrition Basics Link
Action: User selects nutrition
Result: Navigates to Nutrition Page
	•	Progress Tracker Link
Action: User selects progress tracking
Result: Navigates to Progress Page
	•	Favorite Items Link
Action: User selects favorites
Result: Navigates to Favorites Page
	•	Check-In Form Link
Action: User selects check-in
Result: Navigates to Check-In Form

⸻

Workouts Page
	•	Filter Search Box
Action: User types workout name
Result: Filters workout list dynamically
	•	Workout Links
Action: User selects a workout
Result: Opens Workout Detail Page
	•	Back Button
Action: User clicks back
Result: Returns to Home Page

⸻

Workout Detail Page
	•	Back Button
Action: User clicks back
Result: Returns to Workouts Page

⸻

Nutrition Basics Page
	•	Nutrition Item Links
Action: User selects an item
Result: Opens Nutrition Detail Page
	•	Back Button
Action: User clicks back
Result: Returns to Home Page

⸻

Nutrition Detail Page
	•	Back Button
Action: User clicks back
Result: Returns to Nutrition Page

⸻

Progress Tracker Page
	•	Weekly Check-In Link
Action: User selects check-in
Result: Opens Check-In Form
	•	Consistency Tip Link
Action: User selects tip
Result: Opens Progress Tip Page
	•	Favorites Link
Action: User selects favorites
Result: Opens Favorites Page

⸻

Progress Tip Page
	•	Back Button
Action: User clicks back
Result: Returns to Progress Page

⸻

Favorites Page
	•	Panel Button
Action: Opens side panel
Result: Displays additional options
	•	Add Favorite Button
Action: User enters item and submits
Result: Saves item to localStorage and displays it
	•	Clear Favorites Button (Panel)
Action: User clicks button
Result: Deletes all saved favorites
	•	Favorites List
Action: Displays stored items
Result: Updates dynamically from localStorage

⸻

Check-In Form Page
	•	Save to Web Storage Button
Action: User submits form
Result: Saves user data to localStorage
	•	Reset Form Button
Action: Clears form inputs
Result: Resets fields
	•	Clear Saved Check-In Button
Action: User clicks button
Result: Removes saved check-in data
	•	Empty localStorage Button
Action: User clicks button
Result: Clears all stored data

⸻

4. Use of Web Storage

The application uses HTML5 localStorage to:
	•	Save user check-in data (name, workouts, goals, etc.)
	•	Store favorite items selected by the user
	•	Persist data between sessions

⸻

5. Sample / Production Site URL

The live version of this project is available at:

https://wilson539.github.io/mobile-app-final-docs/
