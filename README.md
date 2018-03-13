# wize node sharding blockchain

The main purpose of the WizeBit network is to enable users to safely store files, which implies absolute reliability, anonymity and fault tolerance. In order to achieve that the following conceptual technologies were implemented:
- RSA encryption: provides identification of entities as well as cryptographic protection of communication between network members;
- Distributed database system RAFT: storage of records of stored files on the network;

The accounting system for the network usage pricing plans, as well as bonus payments for providing the user's computing capacity to the network, bonus accruals through the affiliate program is located in BlockChain distributed nodes.

The main participants of the network are:
- Client applications represented by binary multi-platform applications;
- Storage units for user file fragments (Storage Node);
- BlockChain nodes (BlockChain Node);
  
Any member of the network receives a pair of RSA keys upon registration, and then distributes his public keys between the network members.

One of the elements of the concept guaranteeing reliable user file storage on the network is to enable users to create a file storage node in their own disk space and provide the network with the ability to save fragments of files. Information about the location of fragments of files, their belonging to users and files are stored in RAFT distributed DB.
The disk space provided by users should be highly protected and, if possible, reliably managed by the network through the user application. The technology of file masking is also applied to exclude detection of used disk space. To interest users to comply with the terms of participating in the network having provided their disk space, a financial stimulation program for in the form of bonus accruals has been developed.
