##Description
Storing	data	in	the	cloud	or	on	a	network	of	servers	share	a	common	challenge	-	
how	to	securely	share,	store,	and	survive	failures	and	corruption	of	data.	There	are	
systems	like	Drop	Box,	Sync,	Google	Drive,	and	server	installations	like	HDFS	and	
databases	like	Mongo	that	use	multiple	servers	and	redundant	storage	approaches.			
	
The main aim of this project is to design and implement	a new approach to storing and finding data in a larger, decentralized, heterogeneous platform.

We have built the communication	and balancing overlay system to	collect, store and stream data with emphasis on:	
1. Cloud – server – personal device transparency	
2. Balance work across stacks	
3. Survive failures
	
##Technologies
Languages:		 	
Java and Python	(client	API)
Core Packages:			
Google Protobuf, Netty	
Storage:		
In-memory database: Redis
Persistent: Mongo		
Challenges:	 	
Leader election, replication, and work/data balance	
