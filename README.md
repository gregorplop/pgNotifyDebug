# pgNotifyDebug

A small utility to explore, test and debug Postgresql's asynchronous message queue mechanism.
It demostrates the use of the LISTEN/NOTIFY/UNLISTEN statements provided by the database.

The message queue is a useful way to implement inter-process communication among clients connecting to a postgresql system.
You need to understand the mechanism's limitations though.
