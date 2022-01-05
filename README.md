# Project Description:

The project is a small implementation of a widely used transaction-based processing system - the Airline Reservation System. It incorporates various functionalities like airline schedules, fare tariffs, passenger reservations, and ticket records, etc. We process different types of requests/transactions by implementing various database operations like insertions, selections, group by, join, order by, aggregate functions (eg: count), etc.

# Application:

![image](https://github.com/PrateekKumar1709/Airlines-Management-System/blob/main/AMS.png)

# Entity Sets:

Airport, Airplane, Airlines, Seat, Fare, Flight_Trip, Traveller, User, Stop

# Relationship Sets :

Access, Owns, Has, Costs, Travels, Reserved, Depart, Arrive, Has, Books, Associated With

# Business Rules:
● Airlines own airplanes.
● Airplanes have seats.
● Travelers have their seats reserved.
● Travelers travel on flight trips.
● Flight trips have associated fares.
● Users book flight trips.
● Flight trips may have stops.
● Every airline company owns at least one airplane.
● Every airplane is owned by exactly one airline.
● Every airplane has seats.
● Every user has booked at least one trip.
● Every traveler has exactly one seat reserved.
● A traveler cannot travel without a flight trip.
● Every flight trip has a fare associated with it.
● Fare exists only if there is a flight trip.
● Each stop in the flight trip will have a departure and an arrival time.
