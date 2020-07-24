# Group-Messaging-System-using-Message-Queues

As part of an assignment of the Network Programming course, we had to develop a group messaging system where clients can choose to create, join, or leave groups.
Communication between clients is through POSIX message queues.

This assignment heavily leverages UNIX system calls and POSIX message queues.

More details are given in the Assignment PDF, and the design of the code is explained in the design document. This was one of my first medium-scale projects developed in C, and I'm hugely grateful for having taken up the course.

As for running the messagin service, use the make file and run the server first, before spawning as many clients as you like on multiple terminals.
