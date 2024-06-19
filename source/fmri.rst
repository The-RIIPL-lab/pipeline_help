===================
Networks/ Directory
===================

Function MRI output files from the WFU Graph Theory Connectivity pipeline.
 
Located : / _4D. , /RUN1, /Networks 

Example Structure
-----------------

| RUN1/
| ├── normalized
| └── spm_mat

The Network Output (for each cost function): 
 
| Networks/
| └── RUN1
| ├── ROI-aal_MNI_V4-gmonly
| │   └── rmIsoNodes
| │       ├── cost_0.1000
| │       │   ├── assortativity
| │       │   ├── betweennessCentrality
| │       │   ├── charpath
| │       │   ├── closenessCentrality
| │       │   ├── clusteringCoef
| │       │   ├── degrees
| │       │   ├── efficiency
| │       │   ├── modularity
| │       │   ├── smallworld
| │       │   ├── transivity
| │       │   └── triangles
| ... 
 
File Identification
-------------------

