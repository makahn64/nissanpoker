Nissan Poker Node Server
========================

Seriously old project, but rewritten a bit. 

Installation
------------

All Bower and NPM dependencies are checked into Github for your installation pleasure. You should not need to 
`bower update` or `npm update` because of that. So just:

`git clone [repo]`

I did not check in the video, that needs to go in `public/vids/attract.mp4`!

To run the app:  `node www/bin`

To see the app: `localhost:8003`. Why 8003? Who knows? I cannot remember that far back. 
You can change it in `bin/www`.


Usage
-----

`http://localhost:8003`

You can add fake people to the leaderboard by going to the leaderboard edit page and clicking on the Nissan logo
to reveal a secret menu.

You can change the video with the handy video change page.


MK Notes from 5-2016
--------------------


Entire leaderboard, game, video app rewritten into 3 distinct Angular controller/view pairs and massively
simplified. All this lives in nissanNgApp. Enjoy the breeze.
