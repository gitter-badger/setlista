######The problem

I usually go to a concert, come back home and want to listen again to the gigs songs. 
Or, I get invited to a gig of a band I don't know and I want to check out their music. 

######Solution? 

Connect setlist.fm API to Spotify. 

An example query to setlistfm:

	http://api.setlist.fm/rest/0.1/search/setlists.json?artistName=jayhawks&date=15-07-2014

With a bit of JS magic you can then query spotify for the songs returned: 

	https://api.spotify.com/v1/search?q=jayhawks I'm Gonna Make You Love Me


######Todo

* error handling 
* empty results 
* ~~analytics ~~
* feedback form 
* better ui :-)
* *play has to work on mobile*
