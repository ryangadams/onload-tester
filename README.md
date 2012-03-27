onload time Tester
======================

This is a simple 1 page tool to quickly check the time a webpage takes to load.  It provides you with a form to enter the url you want to test and the number of times you want to run the test.

The page is loaded in an iframe and the onload event is timed. Times are averaged over the number of runs you've specified.

If sessionStorage is available the test history is saved.

You can pass the arguments in the address

url - the url of the site  
times - the number of times to run the test  
discard=no - don't throw away the first test  

e.g. path_to_file?url=http://www.bbc.co.uk&times=2&discard=no

url and times _must_ be set