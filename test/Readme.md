Testing page for REST API:

Starting with two JSONP objects: People and Pods. 

getting a Person Object should return profile data and a list of Participating pods, used to populate Pod menu and initiate query to API for those pods.

*test.html - simple container for output
*test.js - recursive query to test API
-->GET People list
-->GET Person 0 (John Doe)
-->GET PiccoPods list
-->GET PiccoPods for Person 0
