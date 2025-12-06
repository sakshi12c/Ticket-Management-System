A simple web-based ticket booking and management system that allows users to book tickets, view booking history, and manage their reservations.
OVERVIEW
This is a lightweight ticket management application built with HTML, CSS, and JavaScript. It provides a clean interface for booking tickets with essential travel information and maintains a history of all bookings.
FEATURES
Ticket Booking: Book tickets with passenger details including name, seat number, travel date, and locations
Automatic Ticket ID Generation: Each booking receives a unique ticket ID
Booking History: View all booked tickets in a organized table format
Delete Tickets: Remove tickets from the booking history
Responsive Design: Clean and user-friendly interface with semi-transparent overlay design
FILE STRUCTURE
project/
index.html      Main HTML structure
script.js       JavaScript functionality
styles.css      Styling and layout
tkt.jpg        Background image (not included)
TECHNOLOGIES USED
HTML5
CSS3
JavaScript (Vanilla)
INSTALLATION AND SETUP

Clone or download all project files to a single directory
Ensure you have a background image named tkt.jpg in the same directory (optional)
Open index.html in any modern web browser

No additional dependencies or installations required.
USAGE
Booking a Ticket

Fill in all required fields:
Name
Seat Number
Travel Date
From Location
To Location
Click Book Ticket button
A confirmation alert will display with your unique ticket ID

Viewing Ticket History

Click the View History button below the booking form
All booked tickets will be displayed in a table format

Deleting a Ticket

Navigate to the ticket history section
Click the Delete button next to the ticket you want to remove
A confirmation alert will appear

HOW IT WORKS
Ticket ID Generation
Each ticket is assigned a random ID in the format TXXXX where XXXX is a random number between 0 and 9999.
Data Storage
Currently, all ticket data is stored in the browser's memory during the session. Refreshing the page will clear all booking history. For persistent storage, consider implementing:
Local Storage
Session Storage
Backend database integration
CUSTOMIZATION
Changing Colors
Edit styles.css to modify:
Submit button color: input type submit background-color
View History button color: view-history-btn background-color
Delete button color: delete-btn background-color
Background Image
Replace tkt.jpg with your preferred image or modify the background-image property in the body selector in styles.css.
KNOWN LIMITATIONS
No data persistence (booking history is lost on page refresh)
No validation for duplicate seat numbers on the same date
Ticket IDs are randomly generated and may theoretically duplicate
No backend integration
FUTURE ENHANCEMENTS
Add data persistence using LocalStorage or a backend database
Implement seat availability checking
Add print ticket functionality
Include search and filter options for ticket history
Add edit ticket functionality
Implement user authentication
Add booking confirmation via email
BROWSER COMPATIBILITY
This application works on all modern browsers including:
Chrome
Firefox
Safari
Edge
Opera
LICENSE
This project is open source and available for educational and personal use.
SUPPORT
For issues or questions, please refer to the source code comments or contact the development team.
