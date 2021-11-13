## BattleShip

server runs as a daemon process w/ logging to syslog.

The server is capable of running multiple game sessions with many clients at once

client provides server auto-discovery feature using multicast address (default 224.0.0.200) so you don't need to spcify the IP address nor the port when connecting to the server, it works only in the local subnetwork

server by default binds to port 1111 (configurable)

partially based on the code by github.com/rougeth/


## How to play

To install this, simply run `make` command

run the server: `./server`

run the client(s): `./client`


# Placing the Ships 
![1](https://user-images.githubusercontent.com/78519911/141607672-21239ada-5b4f-4d1c-a3cc-f031e3150580.png)

# Attacking
![4](https://user-images.githubusercontent.com/78519911/141607725-72ba6445-ea80-4f91-af8a-47c1ccd0e74e.png)

# You Win
![6](https://user-images.githubusercontent.com/78519911/141607662-4601c367-1bfe-4fc0-99d0-ddfafd825516.png)

# You Lose
![7](https://user-images.githubusercontent.com/78519911/141607663-368883ca-0f33-44d2-8ee7-f89b7babe042.png)
