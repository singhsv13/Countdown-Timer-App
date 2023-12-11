# Countdown Timer App

This is a simple Countdown Timer app built using React and Tailwind CSS.

## Project Overview

The Countdown Timer app is a web application that allows users to set a countdown timer based on the desired number of minutes. It includes features such as starting the timer, resetting it, and pausing the countdown.

## Approach
1. Project Setup:

   - Set up a new React project using Create React App or your preferred method.
   - Install Tailwind CSS in the project. You can follow the official Tailwind CSS documentation for installation  instructions.

2. Component Structure:

   - Create a functional component named CountdownTimer.
   - Initialize state variables (minutes, seconds, isActive) using the useState hook to manage the countdown state.

3. Timer Logic:

   - Use the useEffect hook to handle the timer logic. Set up an interval that decreases the minutes and seconds based on the countdown.
   - Clear the interval when the countdown reaches zero, and update the isActive state accordingly.

4. Event Handlers:

   - Implement event handlers (handleStart, handleReset, handlePause, handleInputChange) to manage user interactions with the timer and    
 input field.

5. Styling with Tailwind CSS:

   - Use Tailwind CSS utility classes for styling the components.
   - Apply a dark ocean-themed background to the main container.
   - Style the input field, buttons, and timer text for a visually appealing and responsive design.
   - Utilize Flexbox with Tailwind CSS classes to center the entire app on the screen.

## Table of Contents

   - [Installation](#installation)
   - [Usage](#usage)
   - [Dependencies](#dependencies)
   - [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   ```
## Navigate to the project directory:

```bash
cd countdown-timer-app
```

## Install dependencies:

```bash
npm install
```
## Usage

Start the development server:

```bash
npm start
Open your browser and go to http://localhost:5173 to view the app.
```

   - Enter the desired countdown minutes in the input field.

   - Click the "Play" button to start the countdown.

   - Click the "Reset" button to reset the timer.

   - Click the "Pause" button to pause the timer.

## Dependencies

```bash
React
Tailwind CSS
```

## License

This project is Free to use.
