This Matlab Simulink module can be used to conduct time-domain simulations on the IEEE 24-bus system. (Mingjian Tuo, @July 2020)
* 'IEEE24_bus.m': generators and load settings of proposed model.
* 'IEEE24_bus.slx': simulink model: system architecture, generator models, load models, and simulation output.
* 'IEEE24bus_simplified.slx': simulink model of Patrice Brunelle's work as benchmark.
* 'IEEE24bus_simplified_benchmark.m': generators settings of P. Brunelle's benchmark model.

This is for our TPWRS paper: *Security-Constrained Unit Commitment Considering Locational Frequency Stability in Low-Inertia Power Grids*.


##### Test system:
* The IEEE 24-bus power system used here is one area out of the three-area system modified IEEE RTS-96 reliability test system (73-bus). The original reference is: "The IEEE Reliability Test System-1996. A report prepared by the Reliability Test System Task Force of the Application of Probability Methods Subcommittee" and link is <a class="" target="_blank" href="https://ieeexplore.ieee.org/document/780914">here</a>. 


## Citation:
If you use any module/data here for your work, please cite the following papers as your reference:

Mingjian Tuo and Xingpeng Li, “Security-Constrained Unit Commitment Considering Locational Frequency Stability in Low-Inertia Power Grids”, *IEEE Transactions on Power Systems*, Oct. 2022.

(DOI: 10.1109/TPWRS.2022.3215915)

Paper website: <a class="off" href="/papers/MJ-Tuo_SCUC_LFS/"  target="_blank">https://rpglab.github.io/papers/MJ-Tuo_SCUC_LFS/</a>


## Acknowledgment:
This work is modified based on Patrice Brunelle's benchmark model whose copyright notice is copied in the file "copyright_notice.txt". The modifications we made are as follows:

* Nodes and lines are defined based on IEEE 24-bus system;
* Generators are increased from 10 to 35; basic parameters are defined in 'IEEE24_bus.m';
* Generator models are extended based on the benchmark case;
* Information about generator rotating speed and bus voltage level are added.  


## Contributions:
Mingjian Tuo developed this dataset and Simulink module. Xingpeng Li supervised this work.


## Contact:
Dr. Xingpeng Li

University of Houston

Email: xli83@central.uh.edu

Website: https://rpglab.github.io/


## License:
This work is licensed under the terms of the <a class="off" href="https://creativecommons.org/licenses/by/4.0/"  target="_blank">Creative Commons Attribution 4.0 (CC BY 4.0) license.</a>


## Disclaimer:
The author doesn’t make any warranty for the accuracy, completeness, or usefulness of any information disclosed; and the author assumes no liability or responsibility for any errors or omissions for the information (data/code/results etc) disclosed.

