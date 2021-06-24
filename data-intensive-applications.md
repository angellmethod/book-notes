* Designing Data-Intensive Applications by Martin Kleppmann *

* 1: Reliable, Scalable and Maintable Applications *

Reliability - Tolerating hardware & software faults; Human Error 
            - work correctly even in the face of adversity
            
 Fault - one component of the system deviating from its spec, 
 Failure - when the system as a whole stops providing the required service to the user.           
 Chaos Monkey approach (or other) deliberately introduces faults to make system more fault tolerant because
 you have to test (and correct) against the faults that occur in known situations.
         
         
Scalability - Measuring load & performance; Latency percentiles, throughput
            - as system grows, should be reasonable ways of dealing with that growth
Load: what are the load parameters for your system?
1) What happens if the system resources stay the same but the load increases? Ex. does performance decrease?
2) If performance decreases and you want it to remain the same with a heavier load, what has to change?
           
Maintainability - Operability, simplicity, evolvability
                - everyone working on the system should be able to work on it productively

