#

* Sending login information to a website means you need to protect the data (lock it up). The problem is that the browser and the server are separate and so you need a way for them to both have the same key without sending it. 

* Start with a shared color (yellow) - this is public
* Browser and Server both pick a private color (blue for server, red for browser).
* The server mixes the shared color with it's private color. (the browser does the same) - giving green to server, orange to browser.
* Now, the server and browser exchange these mixed colors. (this is public - but unmixing colors is REALLY hard - so not too useful to steal it here )
* Next, browser and server mix their private colors into the mixed exchange color. Which gives them BOTH the same color. This is the key. 
