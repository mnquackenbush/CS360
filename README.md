# CS360
Repository for SNHU Class CS-360 (Mobile App Development)

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The developed app is designed as an Event Tracker. Users are able to create an account (or log into an existing one), and add multiple events that they have coming up in their future.
They can then update those events (by changing the event's name or date/time) or delete the events from their account when they are no longer relevant. They also have the option
to enable SMS notifications to remind them of upcoming events.
The primary goal of the app was to reduce stress by allowing users to consolidate upcoming obligations in one place with simple features to navigate them.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app was built around three screens: the login screen, the events (main) screen, and a small settings screen (that currently only holds the SMS enable/disable toggle). Every element
included in these screens is labelled in easily comprehendible and user-friendly ways, so then any new user who had never seen the app before would have an easy time navigating through
the various features. For example, on the log in screen, any time a user attempts to log in or create an account with invalid inputs, the app directs the user's attention to the faulty
input field and provides an error message explaining what caused the problem. This allows a smooth user experience and prevents confusion if features of the app don't work the way that
users might expect.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

My primary strategy in coding the app was breaking things down into small pieces that I could test as I worked, before moving on to the next requirement. For example, I made sure that the 
login screen was fully functional and working as expected before I did any coding involving the events screen. Along with this strategy, I made sure to break all of my code up into smaller 
classes at any point where one single class was becoming too crowded with lines of code. This helped consolidate things and keep things organized, for both myself and anyone who reads my 
code to have an easier time understanding it.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

As stated above, my process mostly involved testing each new block of code as I wrote it, so that I could ensure it was working as expected before moving on to the 
next requirement. Once a major functionality in the code (i.e. adding an event to the grid) was finished, I would then do a more comprehensive test of that functionality to 
ensure it worked through various combinations of inputs and actions.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

Most of my innovation came during the coding of the project itself. I personally struggle with front-end development, as I don't have a strong sense of "taste" when it comes to
designing UIs, but from a technical standpoint, that part of the project wasn't overwhelmingly complicated. The backend coding that I had to complete to make the app functional was much 
more challenging, even though it is the aspect of the process I prefer and am more comfortable with. This resulted in me doing a lot of referencing outside sources to help guide my 
development, as I encountered a lot of dead ends and wrong turns in my process, and often needed to do research to find the solutions that would help me implement the proper code.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I find working with data and databases to be something that particularly "clicks" for me, so that aspect of the app was something I felt I did a very strong job of implementing.
The app uses a Room database structure to persistently store events across various user accounts so that any given user is only able to view their own events in their account.
The structuring of the Room classes and methods was new to me for this project, but I felt confident in writing in the SQL queries that were necessary to plug the database's
functionality into the app.
