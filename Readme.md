My database will store the following:

User Email.
User Password,
Number of timers started,
trial period over,
and has paid.

the landing page is a sign in or sign up page, after a succesfull register and/or login, the user is redirected to the timer component.  when a user starts a timer a request is sent to check the number of timers previously started.  If it is less than 5 then their is no limit on the timer.  when the user reaches 5 timers started then they will be limited to a timer of 60 seconds or less, unless the has paid has been marked T (which would happen after a user pays for the full version)
