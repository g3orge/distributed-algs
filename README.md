A collection of distributed algorithms on PeerJS
------------------------------------------------

### Two phase commit
This is a two phase commit algorithm implementation on the PeerJS platform.  
It uses two files, one for the "leader" which should open first and accepts all the messages and one for all the other nodes.  

TODO: merge files (you would need leader election to pick the node-0 one)  

### Lamport mutual exclusion algorithm
This is a Lamport mutual exclusion algorithm implementation on the PeerJS platform.  
It's using the Lamport Time algorithm to implement logical clocks.  
It utilizes a server "process", which has no role in the algorithm,
but is necessary for the shared resource, and enforcing the topology of the network,
in a consistent (for all processes) way.

TODO: add more specific info

-------
These were written as part of the CEID Distributed Systems course in 2013  
George 'papanikge' Papanikolaou
