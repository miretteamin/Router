# Router
Threads and Semaphores:
 ## Java Synchronization
 
 
The following rules should be applied:
➔ The Wi-Fi number of connected devices is initially empty.
➔ If a client is logged in (print a message that a client has logged in) and if it can be served
➔ (means that it can reach the internet), then the client should perform the following
activities:
◆ Connect
◆ Perform online activity
◆ Log out
➔ Note: these actions will be represented by printed messages, such that there is a
random
➔ waiting time between the printed messages when a client connects, do some online
➔ activities and logged out.
➔ If a client arrives and all connections are occupied, it must wait until one of the currently
➔ available clients finish his service and leave.
➔ After a client finishes his service, he leave and one of the waiting clients (if exist) will
➔ connect to the internet.
Solution Design
You program must contain the following classes:
1. Router Class: that contains a list of connections and methods to occupy a
connection and release a connection.
2. Semaphore Class: as given the synchronization lab.
3. Device Class: represent different devices (threads) that can be connected to the
router;
each device has its own name (i.e. C1) and type (i.e. mobile, pc, tablet...) and it may
perform three activities: connect, perform online activity and disconnect/logout.
4. Network Class: this class contains the main method in which the user is asked
for two
inputs:
● N: max number of connections a router can accept
● TC: total number of devices that wish to connect).
● TC lines that contain: name of each device, and its type

## Contributers
- Kareem Mostafa
- Christina Saad
