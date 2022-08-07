# Threads_RepeatingStream
This application produces a set of 2 numbers which the user is tasked at flagging duplicates

To run, simply run the .EXE file.

This is a multi-threaded appication that produces a contant stream of a two number set every one second.
The user is tasked at flagging when the set has a patching pair of numbers, eg: 8 and 8.
The user can press any key to flag at any time without halting the entire application doing so.
There will be a notification whether the flag was successful, or a failure (Flagged when the numbers did not match). 

*Learning experience: Multi-threaded application methods were used to simutaneously run different processes on different threads without the program needing to halt for anything, such as user entry, or lack there-of.
