# flight_booking_typscript


**Design a online flight booking application that helps its users to book flight tickets online. The application allows users to login for booking flight tickets and viewing details of already completed bookings.**

 **1** **. **As a new user, one should be able to signup/Register to the application.

2. As a user, one should be able to login into the application with valid credentials.
3. As a logged in user,

a) one should be able to view all the flights available for booking between the given source and destination.

b) one should be able to view all the bookings done by her/him.

c) one should not be able to view all the bookings done by other.

d) one should be able to cancel any of the future bookings.

4. As a admin, one should be able to view all the bookings details.
5. As a admin, one should be able to view all cancel bookings of any user.
6. As a logged in user/admin, should be able to logout from the application.
7. The application should render Invalid Request Message for any invalid request URL.
8. Flight Operations Manager, should be able to signup/Register and login to the application.
9. Flight Operations Manager, should be able to view all the booking details.
10. Flight Operations Manager, should be able to update/add/delete flight details.
11. Flight Operations Manager, should be able to logout from the system.

**User:**

1. Registration page:

The page should include: **Name, address, mobile number, email, password.**

Then **Register** button.

2. Login page: It should include **user id and password.**

Then** login **button

3. Home page: It should display the small description about application.

Nav bar should contain the links as: **Home, ****Flights****, ****Status of booking,**** Logout.**

4. Onclick of “**Flights” ****(Please refer [image1](https://lms.indeadesignsystems.com/mod/resource/view.php?id=235 "image1"))**

the page should contain options like: **O****ne ****W****ay, Round trip, Multi-city, ****F****ROM, TO, Departure Date, Return Date, Traveller & class**

Then **SEARCH **button.

Onclick of **“FROM”, “TO”,** should display the dropdown list for top cities **(Please refer [example1](https://lms.indeadesignsystems.com/mod/resource/view.php?id=236 "example1"))**

Onclick of “**One Way”, **user should be able to enter the fields such as source(From), Destination(TO), Departure Date, Traveller & Class.

Onclick of** “Round Trip****”, **user should be able to enter the fields such as source(From), Destination(TO), Departure Date, Return Date, Traveller & Class.

Onclick of **“Departure Date”, “Return Date”,** should display the date and year picker calander  **(Please refere [example2](https://lms.indeadesignsystems.com/mod/resource/view.php?id=237 "example2"))**

Onclick of **“****Traveller & class”****,** should display the dropdown list

**(Please refere [example3](https://lms.indeadesignsystems.com/mod/resource/view.php?id=238 "example3"))**

Onclick of **“Multi-City”,** user should be able to enter the fields such as source(From), Destination(TO), Departure Date, Traveller & Class for many cities.  **(Please refer [image2](https://lms.indeadesignsystems.com/mod/resource/view.php?id=239 "image2")****)**

Onlick of **“+ADD CITY” from [image2](https://lms.indeadesignsystems.com/mod/resource/view.php?id=239 "image2"), **it should add one more row to enter details **(Please refer image****3****)**.

Onclick of **“SEARCH”**, one should be able to view all the flights available for booking between the given source and destination and should contain **Book Now** button to book the flight(**Please refer image****4).**

Add filters(Popular Filters, Price Range, Stops) to the left pane (**Please refer image****5)**

Onclick of **“Book Now”, **it should render to the following sample page

**(Please refer [image6](https://lms.indeadesignsystems.com/mod/resource/view.php?id=243 "image6")).**

Onclick of** “Baggage” **option from [image6](https://lms.indeadesignsystems.com/mod/resource/view.php?id=243 "image6"), it should display baggage weight

**(Please refer image 9).**

Onclick of** “Fare rules” **option from [image6](https://lms.indeadesignsystems.com/mod/resource/view.php?id=243 "image6"), it should display the rules

**(Please refer image 10).**

Onclick of **“Continue booking”,** should render to the **travellers** page (  **please refer [image7](https://lms.indeadesignsystems.com/mod/resource/view.php?id=244 "image7")** ).

Onclick of “ **Continue booking** ”, should render to the **Payment** page

Add payment details into the page and **Make**** Payment**

(  **please refer [image8](https://lms.indeadesignsystems.com/mod/resource/view.php?id=245 "image8")** ).

After payment **confirm the booking, **get the confirmation message of booking.

Onclick of “  **Status of booking** ”, it should display the status of booking to the user.

**Flight Operations Manager(FOM):**

1. Registration page:

The page should include: **Name, address, mobile number, ****Name of the flight, ****email, password.**

Then **Register** button.

2. Login page: It should include **FOM ****id and password.**

Then** login **button

3. Home page: It should display the details of flight.

Nav bar should contain the links as: **Home, ****Add flight details****,****Edit/Update flight details, delete flight details,** **Status of booking,**** Logout.**

Onclick of “ **Add ****Flight ****details”, ****allows to add flight details like From, TO, departure date/time, Traveller and Class, Duration of travelling, timing/date of Arrival, price, Number of stops, terminal of departure, terminal for arrival.**

**B****aggage rules: **checkin baggage, Cabin Baggage(please refer [image9](https://lms.indeadesignsystems.com/mod/resource/view.php?id=246 "image9"))

**Fare rules: **Add the rules(please refer [image10](https://lms.indeadesignsystems.com/mod/resource/view.php?id=247 "image10"))

Then clickon **Submit** button to add all the details to DB.

Onlick of  **“Edit/Update flight details”** , should display all available flights and you can edit the details, then, click on **Save **button.

Onclick of **“Delete flight details”,** select particular flight and clickon **Delete** option.

Onclick of **“Status of booking”,** should display the details of passengers, who has booked the flight.
