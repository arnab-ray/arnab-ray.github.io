## Introduction

I started it off to consolidate resources for learning distributed systems, but it is slowly expanding it's wings to cover not only distributed systems, but in general anything that piques my interest.

### Amazon
* [A Conversation with Werner Vogels](https://queue.acm.org/detail.cfm?id=1142065) - Coverage of Amazon's transition to a service-based architecture.
* [Discipline and Focus](https://queue.acm.org/detail.cfm?id=1388773) - Additional coverage of Amazon's transition to a service-based architecture.
* [Werner Vogels](https://www.allthingsdistributed.com/) on [Scalability](http://web.archive.org/web/20130729204944id_/http://itc.conversationsnetwork.org/shows/detail1634.html).
* [SOA creates order out of chaos @ Amazon](https://searchmicroservices.techtarget.com/news/1195702/SOA-creates-order-out-of-chaos-Amazon).

### Latency
* [Latency Exists, Cope!](http://www.addsimplicity.com/adding_simplicity_an_engi/2007/02/latency_exists_.html) - Commentary on coping with latency and it's architectural impacts.
* [Latency - the new web performance bottleneck](https://www.igvita.com/2012/07/19/latency-the-new-web-performance-bottleneck/) - Not at all new (see [Patterson](http://dl.acm.org/citation.cfm?id=1022596)), but noteworthy.
* [The Tail At Scale](https://research.google.com/pubs/pub40801.html) - The challenges inherent of dealing with latency in large scale systems. Alternate [link](https://www2.cs.duke.edu/courses/cps296.4/fall13/838-CloudPapers/dean_longtail.pdf).

### Theory
* [Distributed Computing Economics](https://arxiv.org/pdf/cs/0403019.pdf) - Jim Gray.
* [Rules of Thumb in Data Engineering](https://www.microsoft.com/en-us/research/publication/rules-of-thumb-in-data-engineering/?from=http%3A%2F%2Fresearch.microsoft.com%2Fpubs%2F68636%2Fms_tr_99_100_rules_of_thumb_in_data_engineering.pdf) - Jim Gray and Prashant Shenoy.
* [Fallacies of Distributed Computing](https://www.computing.dcu.ie/~ray/teaching/CA485/notes/fallacies.pdf) - Peter Deutsch.
* [Impossibility of distributed consensus with one faulty process](https://dl.acm.org/citation.cfm?doid=3149.214121) - also known as FLP [access requires account and/or payment, a free version can be found [here](http://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)].
* [Unreliable Failure Detectors for Reliable Distributed Systems](https://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/p225-chandra.pdf) - A method for handling the challenges of FLP.
* [Lamport Clocks](http://lamport.azurewebsites.net/pubs/time-clocks.pdf) - How do you establish a global view of time when each computer's clock is independent.
* [The Byzantine Generals Problem](http://lamport.azurewebsites.net/pubs/byz.pdf).
* [Lazy Replication: Exploiting the Semantics of Distributed Services](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.17.469).
* [Scalable Agreement - Towards Ordering as a Service](https://www.usenix.org/legacy/event/hotdep10/tech/full_papers/Kapritsos.pdf).
* [Scalable Eventually Consistent Counters over Unreliable Networks](https://arxiv.org/pdf/1307.3207v1.pdf) - Scalable counting is tough in an unreliable world
* [A Cache of Theoretical Papers](https://github.com/papers-we-love/papers-we-love/tree/master/distributed_systems).

### Languages and Tools
* [Programming Distributed Erlang Applications: Pitfalls and Recipes](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.137.9417&rep=rep1&type=pdf) - Building reliable distributed applications isn't as simple as merely choosing Erlang and OTP.

### Infrastructure
* [Principles of Robust Timing over the Internet](https://queue.acm.org/detail.cfm?id=1773943) - Managing clocks is essential for even basics such as debugging.

### Storage
* [Consistent Hashing and Random Trees](https://www.akamai.com/us/en/multimedia/documents/technical-publication/consistent-hashing-and-random-trees-distributed-caching-protocols-for-relieving-hot-spots-on-the-world-wide-web-technical-publication.pdf).
* [Amazon's Dynamo Storage Service](https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html).

### Paxos Consensus
* [Paxos Made Simple](http://lamport.azurewebsites.net/pubs/paxos-simple.pdf) - Leslie Lamport.
* [The Part-Time Parliament](http://lamport.azurewebsites.net/pubs/lamport-paxos.pdf) - Leslie Lamport.
* [Paxos Made Live - An Engineering Perspective](http://static.googleusercontent.com/media/research.google.com/en/us/archive/paxos_made_live.pdf) - Chandra et al.
* [Revisiting the Paxos Algorithm](http://groups.csail.mit.edu/tds/paxos.html) - Lynch et al.
* [How to build a highly available system with consensus](https://www.microsoft.com/en-us/research/publication/how-to-build-a-highly-available-system-using-consensus/) - Butler Lampson.
* [Reconfiguring a State Machine](https://www.microsoft.com/en-us/research/publication/reconfiguring-a-state-machine/?from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fum%2Fpeople%2Flamport%2Fpubs%2Freconfiguration-tutorial.pdf) - Lamport et al - changing cluster membership.
* [Implementing Fault-Tolerant Services Using the State Machine Approach: a Tutorial](https://www.cs.cornell.edu/fbs/publications/smsurvey.pdf) - Fred Schneider.

### Other Consensus Papers
* [Mencius: Building Efficient Replicated State Machines for WANs](https://www.usenix.org/legacy/event/osdi08/tech/full_papers/mao/mao_html/) - consensus algorithm for wide-area network.
* [In Search of an Understandable Consensus Algorithm](https://raft.github.io/raft.pdf) - The extended version of the RAFT paper, an alternative to PAXOS.

### Gossip Protocols (Epidemic Behaviours)
* [How robust are gossip-based communication protocols?](https://infoscience.epfl.ch//record/109302?ln=en)
* [Astrolabe: A Robust and Scalable Technology For Distributed Systems Monitoring, Management, and Data Mining](http://www.cs.cornell.edu/home/rvr/papers/astrolabe.pdf)
* [Epidemic Computing at Cornell](https://www.allthingsdistributed.com/historical/archives/000456.html).
* [Fighting Fire With Fire: Using Randomized Gossip To Combat Stochastic Scalability Limits](https://www.cs.cornell.edu/home/rvr/papers/FightingFire.pdf).
* [Bi-Modal Multicast](https://www.cs.cornell.edu/courses/cs614/2003sp/papers/BHO99.pdf).
* [ACM SIGOPS Operating Systems Review - Gossip-based computer networking](https://dl.acm.org/citation.cfm?id=1317379&picked=prox).
* [SWIM: Scalable Weakly-consistent Infection-style Process Group Membership Protocol](http://www.cs.cornell.edu/projects/quicksilver/public_pdfs/SWIM.pdf).

### P2P Systems
* [Chord](http://nms.csail.mit.edu/papers/chord.pdf) - A Scalable Peer-to-peer Lookup Protocol for Internet Applications.
* [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) - A Peer-to-peer Information System Based on the XOR Metric.
* [Pastry](http://rowstron.azurewebsites.net/PAST/pastry.pdf) - Scalable, decentralized object location and routing for large-scale peer-to-peer systems.
* [PAST](https://people.mpi-sws.org/~druschel/publications/PAST-hotos.pdf) - A large-scale, persistent peer-to-peer storage utility - storage system atop Pastry.
* [SCRIBE](https://people.mpi-sws.org/~druschel/publications/Scribe-jsac.pdf) - A large-scale and decentralised application-level multicast infrastructure - wide area messaging atop Pastry.

### Miscellaneous 
* [The Value of Science](http://www.faculty.umassd.edu/j.wang/feynman.pdf) - Post involvement in Manhattan Project, Prof. Feynman answers question concerning _Is there evil in science?_
* [Meltdown Attack](https://meltdownattack.com/).

### Contact

I am reachable through [LinkedIn](https://www.linkedin.com/in/arnab008/).
