# car_rental_application
**Rent a Ride**
As a customer to Rent a Ride you book a cab. We charge you as per the distance covered. We charge 8rs/km.
The moment you click the button to RIDE, we search for the nearby drivers who will accept your ride.
Suppose there are 15 drivers near your location, then we send the request to the first driver who is closest to you, then the second, and so on.
There are few conditions though, on the basis of which we can not send the request to the nearby driver.
**Condition 1:**  If the driver rating is lower than 4. (out of 5)
**Condition 2:** If you selected a specific car, and that car driver is not the closest one.
In case there is no driver present as per your request for the car, we will ask you to select some other car.
Let’s see an example
Driver Car Model Rating DistanceFromCustomer
A Sedan 4 500m
B HatchBack 4.3 1km
C 5 Seater 4.8 200m
D Sedan 4.1 700m
E HatchBack 4.7 430mRent a Ride
As a customer to Rent a Ride you book a cab. We charge you as per the
distance covered. We charge 8rs/km.
The moment you click the button to RIDE, we search for the nearby
drivers who will accept your ride.
Suppose there are 15 drivers near your location, then we send the request
to the first driver who is closest to you, then the second, and so on.
There are few conditions though, on the basis of which we can not send the
request to the nearby driver.
Condition 1:
If the driver rating is lower than 4. (out of 5)
Condition 2:
If you selected a specific car, and that car driver is not the closest one.
In case there is no driver present as per your request for the car, we will
ask you to select some other car.
Let’s see an example
Driver Car Model Rating DistanceFromCustomer
**driver  car_model   rating   distance_from_Customer**
_**A Sedan 4 500m
B HatchBack 4.3 1km
C 5 Seater 4.8 200m
D Sedan 4.1 700m
E HatchBack 4.7 430m**_
The customer booked a cab asking for a sedan. The total distance that willoccur is 43km.
The driver with the closest distance is C but it is not a Sedan, therefore we will look for Sedan. Driver A(500) and Driver D(700). Both have rating greater than 4.
Driver A gets the request first because he is the closest driver.
Driver A accepts the request. There is not mechanism now a driver can cancel the request. Unless he/she doesn’t fit in the criteria.
The customer booked a cab asking for a sedan. The total distance that will occur is 43km.
The driver with the closest distance is C but it is not a Sedan, therefore we will look for Sedan. Driver A(500) and Driver D(700). Both have rating greater than 4.
Driver A gets the request first because he is the closest driver.
Driver A accepts the request. There is not mechanism now a driver cancancel the request. Unless he/she doesn’t fit in the criteria.
