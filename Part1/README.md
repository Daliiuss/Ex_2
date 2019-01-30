# Mutex and Channel basics

### What is an atomic operation?
> An operation during which a processor can simultaneously read a location and write it in the same bus operation. This prevents any other processor or I/O device from writing or reading memory until the operation is complete.

### What is a semaphore?
> Limitator for consumer (thread) to access resources (data)

### What is a mutex?
> Is used to optimize system and prevent from multiple data uses at the same time, by giving thread to work with resources and only when it finishes processing data gives to another thread to work with. 

### What is the difference between a mutex and a binary semaphore?
> Mutual Exclusion semaphores are used to protect shared resources giving an error if other task tries to use data
> while
> Semaphore will put other task on pending list which will wait while task finishes data processing

### What is a critical section?
> Place where data is stored and protected from multiple task accessing it. Allows only one thread at the time.

### What is the difference between race conditions and data races?
 >  A data race occurs when 2 instructions from different threads access the same memory location
>
>   A race condition is a semantic error. It is a flaw that occurs in the timing or the ordering of events that leads to erroneous program behavior. 

### List some advantages of using message passing over lock-based synchronization primitives.
> 1. saves software from manual memory management
> 2. 

### List some advantages of using lock-based synchronization primitives over message passing.
> *Your answer here*
