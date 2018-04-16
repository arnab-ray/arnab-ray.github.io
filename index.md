## Introduction

I started it off to consolidate resources for learning distributed systems, but it is slowly expanding it's wings to cover not only distributed systems, but in general anything that piques my interest.

### First Steps
* [Distributed Systems for Fun and Profit](http://book.mixu.net/distsys/) - A book covering basic concepts.

### Thought Provokers
* [Harvest, Yield and Scalable Tolerant Systems](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.33.411) - Real world applications of CAP from Brewer et al.
* [On Designing and Deploying Internet Scale Services](https://mvdirona.com/jrh/talksAndPapers/JamesRH_Lisa.pdf) - James Hamilton.
* [The Perils of Good Abstractions](http://www.addsimplicity.com/adding_simplicity_an_engi/2006/12/the_perils_of_g.html) - Building the perfect API/interface is difficult.
* [Chaotic Perspectives](http://www.addsimplicity.com/adding_simplicity_an_engi/2007/05/chaotic_perspec.html) - Large scale systems are everything developers dislike - unpredictable, unordered and parallel.
* [Data on the Outside versus Data on the Inside](http://cidrdb.org/cidr2005/papers/P12.pdf) - Pat Helland.
* [Memories, Guesses and Apologies](https://blogs.msdn.microsoft.com/pathelland/2007/05/15/memories-guesses-and-apologies/) - Pat Helland.
* [SOA and Newton's Universe](https://blogs.msdn.microsoft.com/pathelland/2007/05/20/soa-and-newtons-universe/) - Pat Helland.
* [Building on Quicksand](https://arxiv.org/abs/0909.1788) - Pat Helland.
* [Why Distributed Computing?](https://www.artima.com/weblogs/viewpost.jsp?thread=4247) - Jim Waldo.
* [A Note on Distributed Computing](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.41.7628) - Waldo, Wollrath et al.
* [Stevey's Google Platforms Rant](https://plus.google.com/+RipRowan/posts/eVeouesvaVX) - Yegge's SOA platform experience.

### Latency
* [Latency Exists, Cope!](http://www.addsimplicity.com/adding_simplicity_an_engi/2007/02/latency_exists_.html) - Commentary on coping with latency and it's architectural impacts.
* [Latency - the new web performance bottleneck](https://www.igvita.com/2012/07/19/latency-the-new-web-performance-bottleneck/) - Not at all new (see [Patterson](http://dl.acm.org/citation.cfm?id=1022596)), but noteworthy.
* [The Tail At Scale](https://research.google.com/pubs/pub40801.html) - The challenges inherent of dealing with latency in large scale systems. Alternate [link](https://www2.cs.duke.edu/courses/cps296.4/fall13/838-CloudPapers/dean_longtail.pdf).

### Google
* [MapReduce](https://research.google.com/archive/mapreduce.html).
* [Chubby Lock Manager](https://research.google.com/archive/chubby.html).
* [Google File System](https://research.google.com/archive/gfs.html).
* [BigTable](https://research.google.com/archive/bigtable.html).
* [Data Management for Internet-Scale Single-Sign-On](https://www.usenix.org/legacy/event/worlds06/tech/prelim_papers/perl/perl.pdf).
* [Dremel: Interactive Analysis of Web-Scale Datasets](https://research.google.com/pubs/pub36632.html).
* [Large-scale Incremental Processing Using Distributed Transactions and Notifications](https://research.google.com/pubs/pub36726.html).
* [Megastore: Providing Scalable, Highly Available Storage for Interactive Services](http://cidrdb.org/cidr2011/Papers/CIDR11_Paper32.pdf) - Smart design for low latency Paxos implementation across datacentres.
* [Spanner](https://research.google.com/archive/spanner.html) - Google's scalable, multi-version, globally-distributed, and synchronously-replicated database.
* [Photon](https://research.google.com/pubs/pub41318.html) - Fault-tolerant and Scalable Joining of Continuous Data Streams. Joins are tough especially with time-skew, high availability and distribution.
* [Mesa: Geo-Replicated, Near Real-Time, Scalable Data Warehousing](https://research.google.com/pubs/pub42851.html) - Data warehousing system that stores critical measurement data related to Google's Internet advertising business.

### Amazon
* [A Conversation with Werner Vogels](https://queue.acm.org/detail.cfm?id=1142065) - Coverage of Amazon's transition to a service-based architecture.
* [Discipline and Focus](https://queue.acm.org/detail.cfm?id=1388773) - Additional coverage of Amazon's transition to a service-based architecture.
* [Werner Vogels](https://www.allthingsdistributed.com/) on [Scalability](http://web.archive.org/web/20130729204944id_/http://itc.conversationsnetwork.org/shows/detail1634.html).
* [SOA creates order out of chaos @ Amazon](https://searchmicroservices.techtarget.com/news/1195702/SOA-creates-order-out-of-chaos-Amazon).

### Consistency Models
* [CAP Conjecture](https://www.glassbeam.com/sites/all/themes/glassbeam/images/blog/10.1.1.67.6951.pdf) - Consistency, Availability, Parition Tolerance cannot all be satisfied at once.
* [Consistency, Availability, and Convergence](http://www.cs.utexas.edu/users/dahlin/papers/cac-tr.pdf) - Proves the upper bound for consistency possible in a typical system.
* [CAP Twelve Years Later: How the "Rules" Have Changed](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed) - Eric Brewer expands on the original tradeoff description.
* [Consistency and Availability](https://www.infoq.com/news/2008/01/consistency-vs-availability) - Vogels.
* [Eventual Consistency](https://www.allthingsdistributed.com/2007/12/eventually_consistent.html) - Vogels.
* [Avoiding Two-Phase Commit](http://www.addsimplicity.com/adding_simplicity_an_engi/2006/12/avoiding_two_ph.html) - Two phase commit avoidance approaches.
* [2PC or not 2PC, Wherefore Art Thou XA?](http://www.addsimplicity.com/adding_simplicity_an_engi/2006/12/2pc_or_not_2pc_.html) - Two phase commit isn't a silver bullet.
* [Life Beyond Distributed Transactions](http://adrianmarriott.net/logosroot/papers/LifeBeyondTxns.pdf) - Helland.
* [If you have too much data, then 'good enough' is good enough - NoSQL, Future of data theory](https://queue.acm.org/detail.cfm?id=1988603) - Pat Helland.
* [Starbucks doesn't do two phase commit](http://www.enterpriseintegrationpatterns.com/docs/IEEE_Software_Design_2PC.pdf) - Asynchronous mechanisms at work.
* [You Can't Sacrifice Partition Tolerance](https://codahale.com/you-cant-sacrifice-partition-tolerance/) - Additional CAP commentary.
* [Replication: Optimistic Approach](http://www.hpl.hp.com/techreports/2002/HPL-2002-33.pdf) - Relaxed consistency approaches for data replication.

### Theory
* [Distributed Computing Economics](https://arxiv.org/pdf/cs/0403019.pdf) - Jim Gray.
* [Rules of Thumb in Data Engineering](https://www.microsoft.com/en-us/research/publication/rules-of-thumb-in-data-engineering/?from=http%3A%2F%2Fresearch.microsoft.com%2Fpubs%2F68636%2Fms_tr_99_100_rules_of_thumb_in_data_engineering.pdf) - Jim Gray and Prashant Shenoy.
* [Fallacies of Distributed Computing](https://www.computing.dcu.ie/~ray/teaching/CA485/notes/fallacies.pdf) - Peter Deutsch.
* [Impossibility of distributed consensus with one faulty process](https://dl.acm.org/citation.cfm?doid=3149.214121) - also known as FLP [access requires account and/or payment, a free version can be found [here](http://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)].
* [Unreliable Failure Detectors for Reliable Distributed Systems](https://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/p225-chandra.pdf) - A method for handling the challenges of FLP.
* [Lamport Clocks](http://lamport.azurewebsites.net/pubs/time-clocks.pdf) - How do you establish a global view of time when each computer's clock is independent.
* [Vector Clocks](http://zoo.cs.yale.edu/classes/cs426/2012/lab/bib/fidge88timestamps.pdf) - A generalisation of Lamport clocks.
* [The Byzantine Generals Problem](http://lamport.azurewebsites.net/pubs/byz.pdf).
* [Lazy Replication: Exploiting the Semantics of Distributed Services](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.17.469).
* [Scalable Agreement - Towards Ordering as a Service](https://www.usenix.org/legacy/event/hotdep10/tech/full_papers/Kapritsos.pdf).
* [Scalable Eventually Consistent Counters over Unreliable Networks](https://arxiv.org/pdf/1307.3207v1.pdf) - Scalable counting is tough in an unreliable world.
* [Consistent snapshot](https://www.microsoft.com/en-us/research/publication/distributed-snapshots-determining-global-states-distributed-system/?from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fum%2Fpeople%2Flamport%2Fpubs%2Fchandy.pdf) - Chandy et al.
* [Leader election algorithm](http://web.info.uvt.ro/~petcu/distrib/SD12.pdf).
* [A Cache of Theoretical Papers](https://github.com/papers-we-love/papers-we-love/tree/master/distributed_systems).

### Languages and Tools
* [Programming Distributed Erlang Applications: Pitfalls and Recipes](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.137.9417&rep=rep1&type=pdf) - Building reliable distributed applications isn't as simple as merely choosing Erlang and OTP.

### Infrastructure
* [Principles of Robust Timing over the Internet](https://queue.acm.org/detail.cfm?id=1773943) - Managing clocks is essential for even basics such as debugging.

### Storage
* [Consistent Hashing and Random Trees](https://www.akamai.com/us/en/multimedia/documents/technical-publication/consistent-hashing-and-random-trees-distributed-caching-protocols-for-relieving-hot-spots-on-the-world-wide-web-technical-publication.pdf).
* [Amazon's Dynamo Storage Service](https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html). Another source is present [here](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf).

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
* [System Design Tutorial](https://www.hiredintech.com/system-design/sample-architectures/).

### Contact

I am reachable through [LinkedIn](https://www.linkedin.com/in/arnab008/).
