Task 0: 0. My name is Betty:
- 
in this task, I used the




Task 3: New owner:
-
I have to change the current owner of the hello file (root) to a new owner called betty by using <chown betty hello> chown command changes the owenr of the file to the newowner which in is case, betty 

Task 14: change_owner_and_group:
-
I used the command <find . type -f -o type -d  -exec cchown vincent:staff {} +>
<find .> will search in  the current dirctory
<- type> will determin what to find whihch in this case, d(directory) and f(files)


Task 16 :if_only:
-
in this task, i have to change the owner of the "hello" file to "vincent" only if the current user is "guillaume".
using the flag <-user> for type command will  first check the current user and it will execute using <-exec> to change the owner. 



