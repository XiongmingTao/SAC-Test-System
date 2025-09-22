# SAC-Test-System
The specific configurations of the five test systems for the SAC mechanism and their corresponding sharding schemes.

The approach is applied to numerical simulations on 24 bus, 66 bus, 109 bus, 151 bus, and 179 bus systems, which are extended from the original IEEE test systems. Details of the files are provided below.
## The details of the test system.
<div align="center">
  <img src = "/IMG/img1-1.png"/>
</div> 

Each Excel file contains four sheets: Producers, Consumers, Shard_Info, and System_Network. The details are described below:

### Producers & Consumers
These sheets contain detailed information for producers and consumers, including cost parameters, variable bounds, communication delay parameters, indices, and the buses to which they belong.
<div align="center">
  <img src = "/IMG/img5.png"/>
</div> 

### Shard_Info
This sheet presents the sharding scheme obtained by assigning prosumers using the proposed sharding method.
<div align="center">
  <img src = "/IMG/img3-1.png"/>
</div> 

### System_Network
This sheet provides the parameters of the system buses and lines.
<div align="center">
  <img src = "/IMG/img4.png"/>
</div> 
