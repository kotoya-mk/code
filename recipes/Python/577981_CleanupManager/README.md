## CleanupManager for with statements  
Originally published: 2011-12-13 04:21:08  
Last updated: 2011-12-18 07:20:46  
Author: Nick Coghlan  
  
Inspired by unittest.TestCase.addCleanup(), CleanupManager provides a means to programmatically add resources to be cleaned up when leaving a with statement. This makes it easy to use with optional resources, and those derived from sequences of inputs.