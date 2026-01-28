# Parallel and Distributed Computing



## Jan 28, 2026

Distributed Computing: Two or more machine sharing the same hardware for solving a single task at the same time. 


### Agenda
    - Distributed Computing
    - Grid Computing
    - Cluster Computing
    - Utility Computing
    - Cloud Computing



A task on a machine is taking 100 minutes and I've another machine which has the capability to process the task. Why shouldn't combine these machines?

### What is Computing

Computing is any activity that uses ...


### Distributed Computing
... with diagram


### Trends in Computing

- Distributed
- Cluster
- Grid
- Utility
- Cloud


### Computers in a Distributed System
    - Workstations
    - Servers Sytems
    - Personal Assitance Devices

### Common properties of Distributed Computing
    - Fault Tolerance | Fault Tolerance vs Disaster Recovery | Error, fault and failure
    - Each node play partial role: can contribute and does its ows task
    - Resource sharing: can share both software and hardware
    - Load Sharing: share the task of that machine is capable to do such as a machine has 4GB RAM and another has 8GB 
    - Easy to Expand (Scalable)
    - Performance: 

### Why Distributed Computing

    - Nature of Application: Rather than providing all the major resources to a single machine.
    - Performance:  
        - Computing Intesnsive
        - Data Intensive

    - Robustness
        - No SPOF (Single Point of Failure)
        - other nodes can execute the same task executed on failed node.


### Distributed Applications
    - Applications that consist of a set of processes that are distributed across a network of machine and work togher as an ensembel to solve a common proble.

    - In the past, mostly "client-server"
    - Peer to Peer: From here the story of Distributed started, why just to share the data and not the resources

    - Example Diagrams


### Grid Computing

Grid computing enables the virtualization of disbributed computing and data resrouces such as processing, network badnwidth and storagee capacity...

Linking different types of machines. Hetrogenous Connectivity. 


- Need of Grid Computing

- Applications 
    - Weather Forecast
    - Detection and Modeling of Natural Disasters
    - Physics Applications
    - And many others


- Types of Grid
    - Computational Grid
    - Data Grid
    - Collaboration Grid
    - Network Grid: Remote patient operation example
    - Utility Grid: 


- Distributed vs Grid vs Cluster vs Utility
    - Distributed: managing or pooling hundreds or thousands of computer systems to solve a large computational problem.
    - Grid: Efficiently utilication of a pool of hetrogeneous systems; more wide scale and geographically distributed
        - at least one needs to be different: either hardware or software
    - Cluster: Consists of homogeneous hardware and OS; geographically connected by LAN
        - Homogenuous hardware **and** OS; 
    - Utility: service provisioning model; computing resources available for consumers as needed.
        - SaaS; ex: Online IDE

### Cluster Computing

A type of parallel or distributed computer systems.

can be parallel or distributed

...

- Key componenets:
    - Multiple standalone comptuers
    - Operating systems
    - High-Performance
    - ...


- In a typical cluster:
    - Network: Faster, closer, ...
    - Low Latency
    - Loosely coupled than symmetric multiprocessing (SMP)


### Benefits of Cluster

- System availbility:
    - Due to the redundancy of hardware, operating systems, and applications.
        - Zoom naming example

- Hardware fault tolerance
    - Redundancy for most system componenets (eg. disk-RAID: Redundance array of indepnedent disk), including both HW & SW

- OS and application reliability
    - Run multiple copies of the OS and applications

- Scalability
    - Adding servers to the cluster as the need arises

- High perforamnce
    - Compared to grid, which is expanded geographically, clustering is faster