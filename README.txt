Please refer to this for the explanation of the methods found with in the Jupiter notebook.

Question A:

- It scans user input so the user could input some test cases and see if the function is giving the correct output or not. This is more efficient than hard coding the test cases, it's inefficient and wastes a lot of time.
- The method itself is very straight forward. It returns whether two lines on the x-axis over laps or not
- The test cases have been included and explained with in the Jupiter notebook

Question B: 

- It scans user input so the user could input some test cases and see if the function is giving the correct output or not. This is more efficient than hard coding the test cases, it's inefficient and wastes a lot of time.
- This class/library provides a framework for determining whether two strings are equal, greater than, or less than another. Pretty self explanatory. 
- The test cases and class structure have all been explained in Jupiter notebook

Question C:

- This question is a little trickier than the last two but still doable
- I wrote a class/library for the LRU Cache data structure
- I chose to use python dictionaries because hashing keys and storing values is O(1) and as well as retrieving the stored values for unique keys
- This is an amiable outcome as real time LRU Caches will have to support instantaneous writes and reads from the data structure by many different users
- The cache also supports expiration, which means periodically the cache will delete the least recently used entry. My expiration protocol looks at the smallest stored time stamp within the cache and use it's corresponding key to delete that entry. 
- The protocol does not use any for loops as that will ascertain the runtime to be of O(N) where N is proportional to the number of entries in the cache. We want efficient constant time cache expirations on entries so we exploit the python dictionary hashed key-value pair. 
- The schema of the LRU cache is flexible as it is written as a class and features within could be changed without affecting outside integration concerns
- Data stored within the cache I think consistent across regions as python dictionaries with doing a lot of insertion and popping the built in functions keep data consistent
- One thing about this implementation is that the data structure may or may not be resilient to network crashes or failures....this i think could be a missing functionality 

   