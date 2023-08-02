# StatueOfUnityDotNet

Database:

1 The database is named "RegisteredUserDB" and contains two tables: "TicketBooking" and "RegisteredUser."
2 The "TicketBooking" table stores information about each ticket booking, such as TicketID, Name, Mobile, Email, number of tickets, and TotalAmount.
3 The "RegisteredUser" table stores the email addresses of registered users.
4 The code interacts with the database using SqlConnection, SqlCommand, and SQL queries to retrieve data and store new entries.


XAML (MainWindow.xaml):

1. The XAML code defines the user interface (UI) for the WPF application's main window.
2. It includes text blocks and text boxes to input user details like name, mobile number, email, and number of tickets.
3. The "Register" and "Book Tickets" buttons allow users to register and book tickets, respectively.
4. The ResultTextBlock displays messages to the user, including registration status and the total amount.
5. The "ResultTextBlock" will be replaced with the new window where all the information shown.
