# Overall Design

## Design Choices - Android Client & Spring Boot Server 
The fundamental problem with this approach is, server can't access the personal google drive storage of user. This is the traditional client server design with central storage. Privacy will remain a central issue.

## Design Choies - Android Client running on device DB
In this approach the device has to be loaded from personal Gdrive of the user. Locking of the data file when multiple devices are used should somehow be done. 

TODO: We should explore what server synch capability Gdrive api provides.

This approach can have an MVC architecture.

Another issue is size of data file. Since the data is considered immutable, there should be a mechanism to segement it over time. This data should stay hidden from Gdrive UI like whats app backup.

TODO: should the data file be encrypted? What if you lose the key? What should be its format? 
