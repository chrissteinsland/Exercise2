# Mutex and Channel basics

### What is an atomic operation?
> *A concurrent operation that runs completely independent of other processes*

### What is a semaphore?
> *A variable that manages resource access for multiple threads. Can be a range of value but non-negative. Used for synchronization of processes. Uses a signaling mechanism.*

### What is a mutex?
> *Your answer here*

### What is the difference between a mutex and a binary semaphore?
> *A binary semaphore is a signalling mechanism, signalling when process is finished to the next process. Mutex is a locking mechanism, keeping the resources locked while in use*

### What is a critical section?
> *It is a section with shared variables, which requires a semaphore or mutex to avoid synchronization issues*

### What is the difference between race conditions and data races?
 > *Your answer here*

### List some advantages of using message passing over lock-based synchronization primitives.
> *With message passing, it is easier to synchronize*

### List some advantages of using lock-based synchronization primitives over message passing.
> *Lock-based synchronization is faster*
