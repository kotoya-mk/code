## asyncore scheduler  
Originally published: 2011-07-25 21:17:07  
Last updated: 2011-07-25 23:42:21  
Author: Giampaolo Rodolà  
  
The thing I miss mostly in asyncore is a system for calling a function after a certain amount of time without blocking. This is crucial for simple tasks such as disconnecting a peer after a certain time of inactivity or more advanced use cases such as [bandwidth throttling](http://code.google.com/p/pyftpdlib/source/browse/tags/release-0.6.0/pyftpdlib/ftpserver.py#1048).