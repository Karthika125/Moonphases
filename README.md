# Moon Phase Tracker

## Overview
The Moon Phase Tracker is a web application that allows users to track the lunar cycle and plan celestial observations. It provides an interactive interface to view the current moon phase and forecast the moon phases for the next seven days.

## Features
- Displays the current moon phase based on the selected date.
- Allows users to select a date and view the corresponding moon phase.
- Provides a 7-day forecast of moon phases.
- Responsive design for mobile and desktop users.

## Project Structure
```
moon-phase-tracker
├── public
│   └── phases.html        # Main HTML file for the application
├── vercel.json            # Vercel configuration file
└── README.md              # Project documentation
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   cd moon-phase-tracker
   ```

2. Install dependencies (if any):
   ```
   npm install
   ```

3. Open the `public/phases.html` file in your browser to view the application.

## Usage
- Open the application in a web browser.
- Use the date picker to select a date and view the corresponding moon phase.
- Click on "Today" to reset to the current date.
- Click on "View Next 7 Days" to see the moon phase forecast for the upcoming week.

## Deployment
This project is configured for deployment on Vercel. To deploy:
1. Ensure you have a Vercel account.
2. Install the Vercel CLI:
   ```
   npm install -g vercel
   ```
3. Run the following command in the project directory:
   ```
   vercel
   ```

Follow the prompts to complete the deployment process.