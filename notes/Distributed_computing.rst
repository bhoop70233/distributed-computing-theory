##DISTRIBUTED SYSTEMS 

**CHARACTERIZATION OF DISTRIBUTED SYSTEMS**
*INTRODUCTION*

Networks of computers are everywhere. The Internet is one, as are the many networks of which 
it is composed. Mobile phone networks, corporate networks, factory networks, campus networks, 
home networks, in-car networks – all of these, both separately and in combination, share the 
essential characteristics that make them relevant subjects for study under the heading distributed
systems.
Distributed system is the one in which hardware or software components located at networked 
computers communicate and coordinate their actions only by passing messages. This simple 
definition covers the entire range of systems in which networked computers can usefully be 
deployed.
#Characteristics of Distributed Systems are,
*Concurrency*:In a network of computers, concurrent program execution is the norm. I can do
my work on my computer while you do your work on yours, sharing resources such as web 
pages or files when necessary. The capacity of the system to handle shared resources can be 
increased by adding more resources (for example. computers) to the network. The coordination 
of concurrently executing programs that share resources is also an important and recurring topic.
*No global clock*:When programs need to cooperate they coordinate their actions by exchanging
messages. Close coordination often depends on a shared idea of the time at which the programs’ 
actions occur. But it turns out that there are limits to the accuracy with which the computers in a 
network can synchronize their clocks – there is no single global notion of the correct time. This 
is a direct consequence of the fact that the only communication is by sending messages through a 
network.
*Independent failures*:All computer systems can fail, and it is the responsibility of system
Designers to plan for the consequences of possible failures. Distributed systems can fail in new 
ways. Faults in the network result in the isolation of the computers that are connected to it, but 
that doesn’t mean that they stop running. In fact, the programs on them may not be able to detect 
whether the network has failed or has become unusually slow. Similarly, the failure of a 
Computer, or the unexpected termination of a program somewhere in the system (a crash), is not 
immediately made known to the other components with which it communicates. Each 
component of the system can fail independently, leaving the others still running






 
