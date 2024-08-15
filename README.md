# Railway_Ticket_Booking

**Overview :**
This C++ program simulates a basic railway ticket management system that allows users (both staff members and passengers) to book, view, and cancel railway tickets. The system provides options for users to select their starting and ending destinations, choose the type of ticket, and manage their bookings. The program also applies staff concessions to ticket prices.


**Features :**

    User Role Selection:
      The program allows the user to select whether they are a staff member or a regular user.
      Staff members receive a 50% discount on ticket prices.
      
    Railway Details:
      Display available routes with ticket prices for different classes (AC, Sleeper, First Class).
      Allows users to select the number of tickets they wish to purchase.  
      
    Personal Details Input:
      Users input their personal details, including name, starting destination, ending destination, and ticket type.
      This information is stored in a linked list, with each node representing a ticket.

    Ticket Cancellation:
      Users can cancel tickets by specifying the passenger number.
      The linked list is updated accordingly.

    Display Tickets:
      The program can display all the tickets booked by a user, including details like name, starting destination, ending destination, ticket type, and total rate.
      Staff members see the discounted rate for their tickets.

    Final Changes:
      Users have the option to purchase additional tickets before viewing their final booking details.
