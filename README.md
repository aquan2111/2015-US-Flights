# 2015-US-Flights

The dataset for my project comes from https://www.kaggle.com/datasets/usdot/flight-delays?select=flights.csv.

This data was gathered by the U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics, in which the on-time performance of domestic flights operated by large air carriers in 2015 was tracked.

In particular, for this analysis, departure delays and cancellations will be observed.

The dataset contains around 6 million rows of observation data. The following attributes are recorded in each row.

| Attribute | Description | Type |
| --------- | ----------- | ---- |
| YEAR | The year of the flight (all 2015) | Integer |
| MONTH | The month of the flight | Integer |
| DAY | The day of the flight | Integer |
| DAY_OF_WEEK | The day of the flight as Monday represents 1, Tuesday represents 2, etc. until Sunday represents 7 | Integer |
| AIRLINE | The airline identifier | String |
| FLIGHT_NUMBER | The flight identifier | Integer |
| TAIL_NUMBER | The aircraft identifier | Integer |
| ORIGIN_AIRPORT | The starting airport | String |
| DESTINATION_AIRPORT | The destination airport | String |
| SCHEDULED_DEPARTURE | The planned departure time | Integer |
| DEPARTURE_TIME | The actual departure time | Integer |
| DEPATURE_DELAY | The total delay on departure | Integer |
| TAXI_OUT | The time between departure from the origin airport gate and wheels off | Integer |
| WHEELS_OFF | The time that the aircraft's wheels leave the ground | Integer |
| SCHEDULED_TIME | Planned time amount needed for the flight trip | Integer |
| ELAPSED_TIME | AIR_TIME + TAXI_IN + TAXI_OUT | Integer |
| AIR_TIME | The time duration between WHEELS_OFF and WHEELS_ON time | Integer |
| DISTANCE | The distance between two airports | Integer |
| WHEELS_ON | The time point that the aircraft's wheels touch on the ground | Integer |
| TAXI_IN | The time duration elapsed between wheels-on and gate arrival at the destination airport | Integer |
| SCHEDULED_ARRIVAL | Planned arrival time | Integer |
| ARRIVAL_TIME | WHEELS_ON + TAXI_IN | Integer |
| ARRIVAL_DELAY | ARRIVAL_TIME - SCHEDULED_ARRIVAL | Integer |
| DIVERTED | Aircraft landed on airport that out of schedule | Boolean |
| CANCELLED | Flight Cancelled (1 = cancelled) | Boolean |
| CANCELLATION_REASON | Reason for Cancellation of flight: A - Airline/Carrier; B - Weather; C - National Air System; D - Security | Character |
| AIR_SYSTEM_DELAY | Delay caused by air system | Integer |
| SECURITY_DELAY | Delay caused by security | Integer |
| AIRLINE_DELAY | Delay caused by the airline | Integer |
| LATE_AIRCRAFT_DELAY | Delay caused by aircraft | Integer |
| WEATHER_DELAY | Delay caused by weather | Integer |