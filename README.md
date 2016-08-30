# LocalNetworkMonitoring

Summary:
A python script to notify user about the number of people present in home/office based on number of connections to wireless network

Motivation:
I forget my house keys a lot, so a few times I had to wait for my room-mates to arrive and unlock the door. I found that this problem can be avoided if I knew the number of people present at a particular time,  without communicating to my room mates. I thought all of us use wireless network a lot, so by observing the number of wifi connections I can guess the number of users. I wrote a script regarding the same.

Functionality:
User can enter the time at which notification is to be sent. The notification is sent via gmail. For local analysis I used nmap library for python. Deployed the application on a raspberry pi.
