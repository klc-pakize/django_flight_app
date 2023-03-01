# Description
<p> In this project, it is aimed to create an application users can create, update, delete or read reservations. Nested serializers are used to create objects on two different tables at the same time. Also, we used class-based views and overridden some methods to create custom functionalities.✈️</p>


# Models 

- Flight
- Reservation
- Passenger

![Model](https://github.com/klc-pakize/django_flight_app/blob/master/FlightReservationERD.png)

# Flight

    - Client_User
        - views upcoming flight

    - Staff_User
        - views all flight with reservation
        - CRUD flight

# Reservation

    - Client_User
        - CRUD reservation (their own reservation)

    -Staff_User
        - CRUD reservation (all reservation)

# Live Project
- <a href="https://pakizekilic.pythonanywhere.com">Live of the project</a>
- <a href="https://pakizekilic.pythonanywhere.com/swagger/">For the swagger of the project</a>

