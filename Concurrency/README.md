# Go | Quickstarts
- Concurrency: how programs are written
- Parallelism: how programs run

## Mathematical Models
There are several mathematical models that have been developed to analyze and validate the behavior of concurrent systems.
- It can also be called a framework
### CSP - Communicating Sequential Processes
- Influence the design of Go
- Compose of multiple sequential processes that are running in parallel
- Each process can communicate with each other synchronously
- In Go ubuffered channels behave: in synch meaning the system that is sending the message to the other can only continue once other system receives it
#### Validation
- Provides certain properties of complex systems
- Most validation activities boil down to proving properties about the states of the program
- Properties: 
  - "can the system deadlock?"

> Warning!
>
> When multiple systems run together:
> 
> The possible states of the composite system grow exponentially.
>
> It becomes difficult to prove properties about concurrent systems difficult.

## Documents
- [Solution of a Problem in Concurrent Programming Control | Edsger W. Dijkstra](./Documents/dijkstra.pdf)
