# StatueOfUnityDotNet
The code allows users to book event tickets through a WPF application. It checks if users are registered to provide a discount and enable registration through the "Register" button. The application stores booking details and registered users' email addresses in a SQL Server database. The XAML defines the UI, and the code handles user interactions and data operations.
## Database:

1.  The database is named "RegisteredUserDB" and contains two tables: "TicketBooking" and "RegisteredUser."
2.  The "TicketBooking" table stores information about each ticket booking, such as TicketID, Name, Mobile, Email, number of tickets, and TotalAmount.
3.  The "RegisteredUser" table stores the email addresses of registered users.
4. The code interacts with the database using SqlConnection, SqlCommand, and SQL queries to retrieve data and store new entries.


## XAML (MainWindow.xaml):

1. The XAML code defines the user interface (UI) for the WPF application's main window.
2. It includes text blocks and text boxes to input user details like name, mobile number, email, and number of tickets.
3. The "Register" and "Book Tickets" buttons allow users to register and book tickets, respectively.
4. The ResultTextBlock displays messages to the user, including registration status and the total amount.
5. The "ResultTextBlock" will be replaced with the new window where all the information is shown.

 
## Code (MainWindow.xaml.cs):

1. The code handles the logic for a WPF application that allows users to book tickets for an event.
2. It uses SQL Server to interact with the database and stores data related to registered users and ticket bookings.
3. The application checks if a user is registered based on their email address to provide a discount.
4. If the user is not registered, they can click the "Register" button to become a registered user and avail of the discount.
5. The "Book Tickets" button records the user's ticket booking details and calculates the total amount with or without a discount.
6. Appropriate messages are displayed to the user based on their registration status and the total amount.






