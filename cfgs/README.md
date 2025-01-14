## Configuration Example

Arguments are required to run the program. 
Basically, the arguments consist of the instances and required parameters of the algorithm. 
```
Method InstanceFolder InstanceName ResultFolder NumOfFacililty(p) Radius(r) CE-parameters(N ρ nLS α Cmax) RandomSeed
```
A configuration example:
```
CE Instances SJC708.txt Results 6 800 2000 0.05 20 0.8 50 0
```
- Method: Cross-entropy method (CE)
- InstanceFolder: folder name of the corresponding single instance
- InstanceName:  SJC708.txt is the name of the chosen benchmark instance where SJC represents the data set, and 708 is the number of customers.
- ResultFolder : folder name of the results (Results)
- $p$: number of chosen facility
- $r$:  service radius, 800
- $N$: CE parameter, 2000 
- $\rho$ : CE parameter, 0.05
- $nLS$: CE parameter, 20
- $\alpha$: CE parameter, 0.8
- $Cmax$: CE parameter, 50
- $Seed$: the seed of randomness, 0

We note that the 'InstanceFolder' should be the address of the corresponding instance.
Compilation with the example configuration has been successfully tested on a machine running Windows operating system.
