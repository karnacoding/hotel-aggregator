# hotel-aggregator

This project is about hotel booking and management system. The two endusers are hotelManager and Guests.

# User Roles:

1. Hotel Manager:

   Functionalities: 1. Create Hotels 2. Create RoomTypes 3. Manage hotels, roomTypes 4. Manage Booking

2. Guest
   Functionalities: 1. Hotel Search s/m :
   a. Search Hotels
   b. Get Hotel Details
   c. Get Room Details 2. Hotel Booking s/m:
   a. Create Booking
   b. Update guest info
   c. Attaching guest with booking
   d. Make Payments
   e. List all Bookings
   f. Manage all Bookings

# User Booking Flow:

1. Search Hotels in a particular city, dateRange, noOfRooms
2. Browse the list of hotels meeting the search criteria
3. Choose a Hotel & Room Type
4. Core Booking flow:
   1. check if the rooms are available for this request
   2. If available, then reserve the requested rooms for a particular time period
   3. Allow users to add guests
   4. Proceed to payments
   5. Update the booking status to confirmed
