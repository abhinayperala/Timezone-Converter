# Timezone Converter App

This React app allows users to convert between different timezones and schedule meetings with ease.

## Features

- Select Timezone: Users can select their desired timezone from a dropdown menu.
- Date Picker: Users can choose a specific date using a date picker.
- Dark Mode: Toggle between dark and light modes for better readability.
- Share Time: Share the current date and time in the selected timezone with others.
- Schedule Meetings: Generate a Google Calendar event link to schedule a meeting.

## Usage

1. Clone the repository to your local machine.
2. Install dependencies using `npm install`.
3. Start the development server using `npm start`.
4. Access the app in your web browser at `http://localhost:3000`.

## Components

### TimezoneSlider

The `TimezoneSlider` component displays a slider for selecting a specific time within a timezone. It also shows the current date in the selected timezone.

### DraggableSliderBox

The `DraggableSliderBox` component provides drag-and-drop functionality for reordering timezones.

### App

The `App` component is the main component of the app. It contains the state management for timezones, date selection, and dark mode. It also renders the UI components and handles user interactions.

## Libraries Used

- React: JavaScript library for building user interfaces.
- moment-timezone: Library for parsing, validating, manipulating, and formatting dates and times with timezone support.
- react-datepicker: Flexible and reusable date-picker component for React.
- react-dnd: Drag and drop library for React.
- react-dnd-html5-backend: HTML5 backend for react-dnd.

## File Structure

- `App.js`: Main component of the app, containing state management and rendering logic.
- `style.css`: CSS styles for the app.
- `README.md`: Documentation file explaining the app and its features.

