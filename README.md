This code sets up a comprehensive railway reservation system with functionalities for booking and canceling tickets, as well as user management. 
The interface is user-friendly and handles data storage and retrieval using MySQL.

Database Initialization:
Connection to a MySQL database is established.
A database named RAILWAY_RESERVATION_SYSTEM is created.
A table named TRAIN3 is created to store train details.

Main Window:
The main window (w1) is initialized for user login.
User inputs for username and password are captured.

Login:
The login1 function validates the user's credentials against the database.
If successful, the login2 function is called to open the booking and cancellation options.

Booking:
The book_ticket function opens a new window for booking tickets.
The user can search for trains based on the source, destination, and date.
The book1 function allows users to enter the number of passengers and their details.
Passenger details are captured and inserted into the database.
The ticket function handles the payment and ticket generation.

Cancellation:
The cancel_booking function opens a new window for ticket cancellation.
The cancel function validates the ticket number and updates the database accordingly.

Signup:
The signup1 function opens a new window for user registration.
The signup2 function validates and inserts new user data into the database.
