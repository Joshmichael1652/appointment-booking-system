# Appointment Booking System

A beginner-friendly appointment booking website built with HTML, CSS, and JavaScript.

## Features
- Book an appointment by entering a name, phone number, service, date, and time.
- Display all saved appointments.
- Prevent duplicate bookings for the same date and time.
- Cancel an appointment.
- Save appointments in browser LocalStorage.
- Responsive layout for desktop and mobile screens.

## Project files
- `index.html` — page structure and form.
- `style.css` — layout, colors, and responsive design.
- `script.js` — form validation, booking logic, rendering, cancellation, and LocalStorage.

## How to run
1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html` to open it in a browser.
4. Fill in the form and confirm an appointment.

No installation or server is required for this demo.

## How the logic works
1. When the page loads, JavaScript reads saved appointment data from LocalStorage.
2. The customer submits the form.
3. JavaScript checks that all fields are filled and the date is not in the past.
4. JavaScript checks whether the selected date and time are already booked.
5. If available, the appointment is added to an array.
6. The array is saved in LocalStorage and the appointment table is refreshed.
7. When a booking is cancelled, it is removed from the array and LocalStorage is updated.

## Important limitations
This is a front-end school project. LocalStorage saves data only in the same browser on the same device. It does not synchronize bookings between different customers or devices. A real business system should use a secure backend and database, and should protect customer information.

## Suggested GitHub repository description
A simple appointment booking system for small businesses, built using HTML, CSS, and JavaScript.
