# CIS 3500: Nara Extension Starter

## Overview
This assignment involves enhancing a Chrome extension developed by one of the Top 3 winners of the MCIT hackathon. The project provides hands-on experience in web development, API integration, and collaborative coding.

**Original project:** [Nara](https://github.com/luyiZhang818/Nara-Chrome-Extension)

## Project Description
Nara is a Chrome extension that helps users manage their tasks and reminders efficiently. Your task is to enhance this extension by implementing new features.

## Enhancement Options
Choose one of the following enhancements to implement:

1. **Speech Bubble Encouragement**:
   - Identify the task completion event listener in the JavaScript code
   - Create a function to generate random encouraging messages from an array
   - Design a speech bubble element using HTML/CSS
   - Implement a function to position the bubble near the deer mascot
   - Add animation for the bubble to appear and disappear after a few seconds
   - Update the task completion handler to trigger the speech bubble

2. **Daily Gratitude Log**:
   - Add a text input area to the main UI with a character limit
   - Create a "Save Gratitude" button with event listener
   - Implement Chrome storage API calls to save entries with timestamps
   - Design a new "Gratitude Log" page with HTML/CSS
   - Add navigation to access the gratitude log from the main interface
   - Implement a function to retrieve and display past entries chronologically
   - Add options to filter or search through past gratitude entries

3. **Mood Selection Prompt**:
   - Design a set of mood icons/emojis using CSS or SVG
   - Create a mood selection dropdown or button group in the UI
   - Implement event listeners for mood selection
   - Use Chrome storage API to save mood data with timestamps
   - Create a function to prompt for mood input if not provided that day
   - Add a simple visualization (calendar or chart) to track mood over time
   - Implement a function to correlate moods with task completion (optional)

4. **Rotating Weekly Challenge**:
   - Create an array of predefined weekly challenges
   - Implement a function to select a new challenge each week
   - Design UI elements to display the current challenge
   - Add checkboxes for each day of the week
   - Use Chrome storage API to persist challenge progress
   - Implement a notification system to remind users of the challenge
   - Create a function to reset progress and select a new challenge weekly

5. **Inspirational Quote Overlay**:
   - Create an array of inspirational quotes or integrate with a quotes API
   - Design a subtle, non-intrusive overlay using CSS
   - Implement a function to randomly select quotes
   - Add the overlay to the new tab page initialization
   - Include options to customize the quote display (position, font, etc.)
   - Add subtle animations for the quote appearance
   - Implement a refresh button to get a new quote manually

6. **Implement a History Feature**:
   - Modify the task creation and completion functions to log events
   - Design a history page with HTML/CSS for displaying past activities
   - Use Chrome storage API to store and retrieve the history data
   - Implement filtering options (by date, completion status, etc.)
   - Add a function to generate statistics from historical data
   - Create a visual timeline or calendar view of task history
   - Include an option to export history data

7. **Custom Feature**:
   - Draft a detailed proposal including:
     - Feature description and user benefits
     - Technical implementation plan
     - UI/UX mockups or wireframes
     - List of required technologies or APIs
     - Estimated development timeline
   - Submit to instructor/TA for approval before implementation

## Getting Started

### Step 1: Team Organization
- Assign a team member as the **Product Manager (PM)** for Nara.
- Ensure this PM is different from the one assigned to the Lunch Lotto project.

### Step 2: Repository Setup
The PM should fork the repository:
1. Navigate to the `nara-extension-starter` repository on GitHub.
2. Click the **Fork** button to create a copy under their account.

### Step 3: Cloning the Repository
Once the PM has forked the repository, team members should clone it locally:
```sh
git clone https://github.com/<PM-username>/nara-extension-starter.git
```

### Step 4: Development Workflow
1. Open the project in a text editor (e.g., **Visual Studio Code** recommended).
2. Make changes to the codebase.
3. Use the following commands to commit and push your changes:

```sh
git add .
git commit -m "feat: [feature name] added"
git push
```

4. As team members contribute, collaborate using **Pull Requests (PRs)** on GitHub.
5. Regularly sync your local repository with the latest changes:

```sh
git pull
```

6. Resolve merge conflicts as needed and ensure smooth integration.

## Submission
- Submit the final version of your project as per course guidelines.
- Include a brief write-up of your implemented features and any challenges faced.

---
Happy coding, and good luck with Nara! 🦌
