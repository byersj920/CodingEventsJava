-----What is this app?-----
This app is designed to help organize, and keep track of upcoming events! It keeps track of events you enter by storing them in an external database.

-----What does the app do now...?-----
Currently, this app can do the following things:
1) User can enter a new event into the database.
2) User can create a new type of category that an event can be classified as.
3) Display all events currently registered in the database.
4) Filter the event list by what type of event it is.

-----Future Plans-----
In addition to keeping track of events, this app should also be able to keep track of who is attending the event. This can be done in a couple ways.

Person Class:
  The first thing we could do is create a database that keeps track of the people registered for an event. The person class would allow users to submit
  data into a view, then pass it into the class and send it off to an "attendees" table. The Person class would contain fields for:
  -firstName
  -lastName
  -email
  -chosenEvents
   The chosen event(s) field would have a @ManyToMany relationship with the Event class, as many people can register for many different events.
