## Team  
- Frontend Engineer - Cassandra Horton
- API Engineer - Cynthia Brueggemann
- Backend developer - Karla Braford
- Senior Developer - Sundannas Meadows  


## Shotgun!
"Shotgun!" is an application that will help coordinate carpooling rides for your group. The application will pair drivers and passengers who are traveling in the same direction. Passenger slots will be tracked based on a vehicle API that accounts for seats in various makes and models of cars, and a location API will assist drivers and passengers agree on a pickup or drop off location. While this sounds similar to Uber, we're not looking to charge passengers for this service. This service will function as teammates, classmate, busy parents try to work through the logistics of getting friends and family efficiently from one spot to the next.  

## Icon/Logo
![ShotgunLogo](https://github.com/user-attachments/assets/0a2bbd92-9fb1-4edc-9b0a-8239b17fa93a)  

## Data Sources
### Google Maps API
This API provides directions, routes, and estimated travel times. It ensures both drivers and passengers can plan their trips efficiently with real-time traffic and route optimization.
Usage: Calculate directions between the pickup and destination locations and suggest optimal routes.
Google Maps API Documentation

### Edmunds Vehicle API
The Edmunds API provides detailed vehicle specifications, including seating capacity, which helps Shotgun! manage the number of available seats dynamically.
Usage: Automatically retrieve the seating capacity of vehicles when users build their profile, ensuring accurate seat tracking without manual updates.
