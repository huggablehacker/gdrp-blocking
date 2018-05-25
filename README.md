# GDRP Blocking
If you havent already heard GDRP went live yesterday. An on queue, people flipped out and scrambled to get their sites within compliance. So what's a small site like this to do?  Well I figured that instead of trying to get my site in compliance, I'd take a more blunted approach and just block the the EU from accessing my site via the .htaccess config.  My process used GEO IP location (and yes it is easy to get around using a VPN, the point here is that I am placing the responsibility on the user)  and the .htaccess file to block all the 28 member states of the EU. Editing your .htaccess file is pretty strait forward and most hosting sites have a nice "how-to" for this sort of thing, but my standard disclaimer is: `Dont edit your .htacces file if you're not comfortable.`

The three files are: 
- Two Cidr blocking files, one for Apache 2.0-2.3 adn the other for Apace 2.4. 
- The Third file is blocking by country code for Apache 2.4
