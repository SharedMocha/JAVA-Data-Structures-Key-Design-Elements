Below notes helps anyone to refresh or learn key componenets for designing an application.
It also helps in asking correct questions anf answers during the design process.


# System_Design_Architecture


3 main methods for designing a system are (Problem Exploration,Solution Exploration,Execution) 

# Problem Exploration  --> Questions To Ask yourself/team -
Type of data ?
How often it comes & how many events (Ex -1M Events/sec)
Operations on data as it comes(Count,Max,Mean,Median)
What is Refresh stratagey
how about presenting/searching data ?
What channels should this data be available ?
Need API's ?
Business logic ?

# Solution Exploration  --> Questions To Ask yourself/team -
Load balancer needed ?
How much ram memory/db size  we need (2,4,6,120 gb?) -- > what is the size of data (20 Kb?) ?How many   events/sec (100k) So- How many records should we store in memeory for quick access (100k) or 24 hrs of data ?

need nosql db ?
will be sort the data as it comes ?
What is Archival & Purging process

we need in memory db ?
What data structures should we use for faster movements of data ?

should we use buckets  like hash table to group elments and save space rather than a array list.

Can we store data better like map instead of array ? So what are the tradeoffs of this way ? (talk trade  offs) 

The amount of time that each bucket represents depends on much accuracy you want to lose

primary keys -secondary keys--search/sort criteria ?

What are the components where we will have more risk ?system or human ?

# Execution --> Questions To Ask yourself/team -
What APIs to build ? 

Access modifiers

write some code here..saying what array to use - and if we need pointers for fast retrival and storage..identify key variables and methods..

CHECK TIME/SPACE Complexity if possible.
Your code should have the basic methods to read/write/report on data

Max latency ?
