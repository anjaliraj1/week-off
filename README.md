# Work Calendar Web Application

        This is a simple web-based application for managing work schedules, allowing users to track full or partial working days across a calendar. The application includes a toggle for marking half-working days and half-weekends. Each day of the week allows multiple selection options to mark the work schedule for that day.

# Features

  > Half-Day & Weekend Toggle: A checkbox that toggles the visibility of dropdown menus to select whether the workday is a full day, first half, or second half.

  > Calendar Table: Displays a work calendar where users can select their work schedules (full day or half day) for each day of the week.

  > Responsive Design: The layout is responsive and designed to work on all screen sizes with TailwindCSS.

  > Dropdown Menus: Dropdowns for each day allow users to select a work period (Full Day, 1st Half, 2nd Half) when the checkbox is checked.


# Technologies Used

  * HTML: For the structure of the page.

  * TailwindCSS: A utility-first CSS framework used for styling the components.

  * JavaScript: For the functionality of the toggle and dropdown visibility.



# How It Works

 1. The main functionality is controlled by a checkbox (half-day-toggle) which, when checked, reveals dropdowns for each day of the week where users can specify their working hours.

 2. The dropdown contains three options:
     * Full Day
     * 1st Half
     * 2nd Half

 3. JavaScript is used to toggle the visibility of these dropdowns based on the checkbox state.

 4. The layout is fully styled using TailwindCSS classes for a modern, responsive look.


# Future Improvements

 * Add form submission functionality to save the selected work schedule.

 * Implement user authentication to save personal schedules.

 * Enhance the UI with more custom features like color coding and tooltips.
