File Structure


The project directory typically contains the following files:


main.cpp: The main entry point of the application. 

Bus.h and Bus.cpp: Bus class definition and implementation.

Reservation.h and Reservation.cpp: Reservation class definition and implementation.

data/: A directory containing data files for buses and reservations.

utils.h: A file contains required utility function


Classes and Methods

Bus Class

This class manages bus details and includes the following methods:

void addBus(): Adds a new bus.

void displayBuses(): Displays all buses.

void removeBus(): Removes a bus by ID.

Reservation Class

This class manages reservations and includes the following methods:

void bookTicket(): Books a new ticket.

void viewReservations(): Displays all reservations.

void cancelReservation(): Cancels a reservation by ID.

File Handling

Data persistence is achieved using file handling concepts. The bus and reservation data are stored in separate files within the data/ directory.



How to Use

Add a Bus: Select the option to add a bus and enter the required details.

View Buses: Select the option to view all available buses.

Remove a Bus: Select the option to remove a bus and provide the bus ID.

Book a Ticket: Select the option to book a ticket and enter the required details.

View Reservations: Select the option to view all reservations.

Cancel a Reservation: Select the option to cancel a reservation and provide the reservation ID.
