## write_path and load_path methods for file generation scripts  
Originally published: 2010-03-31 21:13:03  
Last updated: 2010-07-27 06:45:51  
Author: Trent Mick  
  
I have a lot of scripts that end up writing files (often build system stuff). Everytime I either end up writing the obvious quick `content = open(path).read()` or I re-implement a function that handles things like: making a backup, some typical logging, encoding support, trying to make it no-op if no changes, etc.