trakt-python
============

trakt api via python

Shows the next weeks TV shows you have on your trakt.tv watch list
also stores the json from trakt.tv to /tmp/trakt/data
checks for a new day each run, if new pulls new json data

need trakt.tv api key as well


eg;
% python2.6 trakt.py
Two and a Half Men airs at 8:30pm on Thursday
         10.4 - You Do Know What the Lollipop Is For CBS
         watchlist: True - runtime: 30min
Person of Interest airs at 9:00pm on Thursday
         2.3 - Masquerade CBS
         watchlist: True - runtime: 60min
Nikita airs at 9:00pm on Friday
         3.1 - 3.0 The CW
         watchlist: True - runtime: 60min
Dexter airs at 9:00pm on Sunday
         7.4 - Run Showtime
         watchlist: True - runtime: 60min
The Walking Dead airs at 9:00pm on Sunday
         3.2 - Sick AMC
         watchlist: True - runtime: 60min
Homeland airs at 10:00pm on Sunday
         2.4 - New Car Smell Showtime
         watchlist: True - runtime: 60min
Alphas airs at 8:00pm on Monday
         2.13 - God's Eye Syfy
         watchlist: True - runtime: 60min
American Horror Story airs at 10:00pm on Wednesday
         2.2 - Tricks And Treats FX
         watchlist: True - runtime: 60min
 


====
doing  % python2.6 trakt.py reset   will force the json to update no matter what the date is 
