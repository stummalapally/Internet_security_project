MIRAI BOTNET

Mirai is malware designed for building large scale botnet of IoT devices.The bot and related programs was created by Anna-senpai, firstly discovered and researched by MalwareMustDie in the end of August 2016.In reply to their blog post, one month later, Anna-sepai published sources and manual on how to build and run botnet.
A large number of connected devices (bots) that can be controlled to attack others on the Internet. This is done without the owner's consent. Generally, these attacks take the form of Distributed Denial of Service (DDoS) attacks.

Like most malware in this category, Mirai is built for two core purposes:

1)Locate and compromise IoT devices to further grow the botnet.

2)Launch DDoS attacks based on instructions received from a remote C&C.

The bot will carry out the following actions:

It attempts to kill processes that would prevent it from running and persisting on the device. The telnet server, and often web server, is killed at this stage.

It connects to a command and control server, waiting for commands to attack other machines.

It continuously scans for other devices that may be vulnerable, attempting to login with the list of known credentials.
