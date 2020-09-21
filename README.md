

# EventExpo
## Description
EventExpo app allows users to reserve tickets for all kind of events which include sports, harvesting, kayaking, painting and many more. EventExpo gives an opportunity for user to host events. The major advantage of using EventExpo app is to handle all the events together at one place where user can switch to differnet pages inside the app rather than opening a different app for each type of event resulting(results in) a good user expereince by using EventExpo App. SignUp the EventExpo and let the events add wings to your daily life. 

## Team members:
1. Annie Samarpitha Chandolu
2. Vineetha Yenugula
3. Alekhya Jaddu
4. Bhanu Prakash Thota

## Activities:
### User
#### Login:
This is the welcome page of the app. Users have to login to access the events.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/welcome%20page.jpg?raw=true" width="200" height="400" />

#### Registration:
If the user is using our app for the first time, then they have to sign-up with their email id and have a unique user id.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/annie%20layouts_signUp.jpg?raw=true" width="200" height="400" />

#### Home Page:
Once the user logs in, where the user can find the list of events where he can get the event details. And can add the events to the cart.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/user-home-page.jpg?raw=true" width="200" height="400" />

#### Share Event:
Users can share events with their friends through text messages, WhatsApp, etc.

#### Cart:
The users can review their order in the cart page.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/cartpage.jpg?raw=true" width="200" height="400" />

#### Payment (Booking confirmation):
Users can finish their orders by paying. They can pay through either debit/credit card or electronic cheque or PayPal.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/annie_layouts_payment.jpg?raw=true" width="200" height="400" />

#### Booking History:
Users can view their bookings or previous order on the order history page.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/Order_History.jpg?raw=true" width="200" height="400" />

#### Profile update:
Users can update their profile with their most recent details on our profile page. They can also reset their password on this page.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/annie_layouts_profile_edit.jpg?raw=true" width="200" height="400" />

#### About App:
Users can view the basic information about our app on the about page.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/About.jpg?raw=true" width="200" height="400" />

### Admin

#### Admin Login:
Username and password are admin credentials these are unique, and these credentials are given by the developers. 
In the admin login page, the admin needs to fill the required fields like username and password.
Click login.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/AdminLogin.jpg?raw=true" width="200" height="400" />

#### Admin Home page:
In the Admin home page, we have options like 
•	Adding a new event, 
•	Maintaining the events, 
•	Check for the particular bookings of the registered users
•	Logout.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/annie_layouts_admin_home.jpg?raw=true" width="200" height="400" />

#### Add Event- Admin:
In this page, the admin can add an event by giving fields like event name, event date, time and price.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/AddEvent.jpg?raw=true" width="200" height="400" />

#### Event maintained Page (Admin):
In this page admin can edit the events which are previously added to the database like changing the event name, event date, time and price or he can delete the event.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/Admin-maintain-events.jpg?raw=true" width="200" height="400" />

#### Check for registered users to the events:
Admin can see the details of customer event bookings.

<img src="https://github.com/annie0sc/event_expo/blob/master/expo_images/admin-registereduserevents.jpg?raw=true" width="200" height="400" />

#### Logout:
Admin can logout from the application.

## Data persistence: 
For live data, we are storing the data into the Realtime database of firebase, from where we can retrieve the data throughout the application. 
 
## Future enhancements:
Limiting to a certain number of seats:\
We are planning to add a feature where we can acknowledge users regarding the number of seats are available.

Wishlist:\
This is where the user can sort his interesting events and add them to the wish list immediately.

Sync with Calendar:\
Here we are planning to add a new feature to sync our application with the calendar.



## EventExpo Admin Flow:

![admin](https://github.com/annie0sc/event_expo/blob/master/expo_images/Admin_workflow.jpg?raw=true)

We have provided an admin hyperlink in the user login page where admin can login and manage the events.After login, the admin can able to see the Home page with differnet events to organise like sports that includes cricket, soccer as of now, harvesting, kayaking and painting.
EventExpo app under admin login in Homepage has two buttons Maintain Events and User Registration Detials.
Under Maintian Events admin can organize the events or edit or delete as per the daily shcedule.
Under User Registration Detials, Admin can able to see the user booking detials and events booked by users. Admin has the right to edit the User Detials or cancel the request if any illegal bookings/activities done.
Every page has the save button, where admin can save his changes after editing detials or organizing the events.

## EventExpo User Flow:

![user1](https://github.com/annie0sc/event_expo/blob/master/expo_images/User_page_flow.jpg?raw=true)

![user2](https://github.com/annie0sc/event_expo/blob/master/expo_images/user_Flow.jpg?raw=true)

User uses the login page to access the EventExpo App, We have provided the functionlity for user to signup if User is not a registered with EventExpo.And, also if user 
forgets password by providing the user id/email-id he can change or create a new password.
After successfull login, User enters into Home Screen where he can search or find a particular event that User is interested in and make a booking or reserve the ticket for particular time or date.
Upon selecting a event, EventExpo shows the in detial description of the selected event and after reading user can continue next for booking.
In booking page, EventExpo requests for the user details such as User's address,Email and phonenumber. Then User can check for a payment which EventExpo listed out
like through Paypal,Credit or Electronic check.After successful payment, User's event will be booked.
User can see the booked events in the settings provided in EventExpo app under the Order Histroy.
If user wish logout after successful order, we have provided the logout option in seetings.

