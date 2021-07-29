# PoEM Training Dataset

**Path:** training dataset/*

**Tips:** The corresponding relationship between the number of nodes and the number of training samples is 1000 times. For example, the model of 10 nodes is trained with 10,000 training samples.

**Explanation of each index:**

|  Name |              Feature              |                             Explanation                            |        Type       |
|:-----:|:---------------------------------:|:------------------------------------------------------------------:|:-----------------:|
|  CPR  |          Content Provider         |                   a unique name to identify nodes                  |   class feature   |
| Label |               label               |   1 means this CPR being selected as block producer, otherwise 0   |        1/0        |
|   CT  |              CPU Time             | the CPU execution time required by running the consensus algorithm | numerical feature |
|   UM  |     Percentage of Used Memory     |     the percentage of free storage space of the blockchain node    | numerical feature |
|   NC  |        The Number of Cores        |     the number of cores in the CPU chips of the blockchain node    | numerical feature |
|   CS  |             Cache Size            |               the percentage of cache space remaining              | numerical feature |
|   PC  |         Power Consumption         |     the energy required to support the consensus algorithm(KWH)    | numerical feature |
|   CP  |          Computing Power          |           the computing power of a blockchain node(FLOPS)          | numerical feature |
|   T   |             Join Date             |          the time when a node joins the blockchain system          | numerical feature |
|   PB  |   The Number of Producing Blocks  |          the number of blocks produced by this node so far         | numerical feature |
|   AV  |            Availability           |                     the availability of a node                     | numerical feature |
|  SRBP |  Success Rate of Producing Blocks |             the success rate of nodes producing blocks             | numerical feature |
|  ATPB | Average Time for Producing Blocks |                  the average block producing time                  | numerical feature |
|   RE  |            Reliability            |                      the reliability of a node                     | numerical feature |
|   TG  |           Time Generated          |                   the time of content generation                   | numerical feature |
|   CH  |            Content Hash           |                  the hash value of content([0,99])                 |   class feature   |
|  CTS  |            Content Size           |                     the size of content([0,2])                     |   class feature   |
