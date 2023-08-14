API Documentation
User Registration
Method: POST
Endpoint: /api/register
Description: Allows users to register by providing their name, email, and password.
Request Body:json

User Login:-
Method: POST
Endpoint: /api/login
Description: Allows users to log in by providing their email and password.
Request Body:json
Response:
json

Get All Flights:-
Method: GET
Endpoint: /api/flights
Description: Returns a list of all available flights.
Response:
json
Get Flight Details:-
Method: GET
Endpoint: /api/flights/:id
Description: Returns details of a specific flight identified by its ID.
Response:
json

Add New Flight:-
Method: POST
Endpoint: /api/flights
Description: Allows users to add new flights to the system.
Request Body:
json
Response:
json

Update Flight Details:-
Method: PUT / PATCH
Endpoint: /api/flights/:id
Description: Allows users to update the details of a specific flight identified by its ID.
Request Body:
json

Delete Flight
Method: DELETE
Endpoint: /api/flights/:id
Description: Allows users to delete a specific flight identified by its ID.
Response: No content (202 status code)
Book a Flight
Method: POST
Endpoint: /api/booking
Description: Allows users to book flights.
Request Body:
json

Response:
json

Get Dashboard (List of Bookings):-
Method: GET
Endpoint: /api/dashboard
Description: Lists all the bookings with user and flight details.
Response:
json

Update Booking:-
Method: PUT / PATCH
Endpoint: /api/dashboard/:id
Description: Allows the user to edit/update a booking.
Request Body:
json

Response: No content (204 status code)
Delete Booking
Method: DELETE
Endpoint: /api/dashboard/:id
Description: Allows the user to delete a booking.
Response: No content (202 status code)