# Cinema-Seat-Reservation-System

Features:

1.Show Available Seats: Displays the current seating arrangement, showing which seats are available and which are reserved.

2.Reserve a Seat: Users can select a seat by entering the row and column. If the seat is available, the user can reserve it by entering their name.

3.Exit the Application: Users can exit the program from the main menu.


Functionality:

1.The seating arrangement is represented as a 2D array (cinemaPlace), with each element representing a seat.

2.Pre-reserved seats are already filled with names (e.g., "Subhan", "Rovsan", and "Ali").

3.The program ensures that users can only reserve available seats, and prevents the reservation of already reserved seats.


How to Use:

A.Show Available Seats: Choose option 1 from the menu to display the current seating arrangement.

B.Reserve a Seat: Choose option 2, then enter the row and column number for the seat you want to reserve. If the seat is available, enter your name to reserve it.

C.Exit: Choose option 3 to exit the program.




Sample Output:
Welcome to Ingress Cinema
1. Show Available seats
2. Reserve a seat
3. Exit

Choice your option(1-3): 1

Current Seating Arrangement
[Empty(0,0)] [Subhan(1,0)] [Empty(0,2)] 
[Empty(1,0)] [Empty(1,1)] [Empty(1,2)] 
[Empty(2,0)] [Empty(2,1)] [Ali(2,2)] 

1. Show Available seats
2. Reserve a seat
3. Exit

Choice your option(1-3): 2

Reserve the row number of the seat: 0
Reserve the column number of the seat: 2
Enter your name: John
Seat successfully reserved!

