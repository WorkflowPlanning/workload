# workload

After unzipping, the folder contains workflows with different sizes and shapes. Each folder in the unzipped folder contains the DAGs, the performance of tasks on different types of VMs, the price of VMs, the deadlines. 

The DAGs are generated with the GGen tool(https://github.com/perarnau/ggen). 

We use the FIFO(Fan-in/Fan-out) method to generate the DAGs. 

For instance, 1.16.2.3. The second number "16" means the workflow contains 16 nodes except for the entry and exit nodes. The "2" means the maximum fan-out degree when generating DAGs. The "3" means the maximum fan-out degree when generating DAGs.


