# Assignment 6 Answers to Questions

### Do you find your code showing race conditions? Try it with larger p values to get many concurrent processes. What can you do about that? Why or why not are you seeing race conditions? 


#### I noticed that I would get race conditions in Prog 2 when I didn't have a mutex lock. But when I added a mutex lock, I didn't get any race conditions. So I think mutex locks are what we can use to prevent race conditions. The mutex would make it so that only one goroutine can modify res at a time. This prevents the  goroutines from reading and writing to res simultaneously.
