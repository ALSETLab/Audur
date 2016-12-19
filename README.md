# Auður
A provides a software platform for Synchrophasor-Based PowerSystem Wide-Area Control System Implementation.
It provides a LabVIEW package for developing custom Power System WACS implentations using the NI-cRIO platform.

![alt text][arch]
[arch]: https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/4_Images/flowchart.png "Audur - Templates"

## Contents:
This package is divided into two parts, utilizing two different synchrophasor data mediation tool-kits, [S3DK](https://github.com/SmarTS-Lab-Parapluie/S3DK) and [Khorjin](https://github.com/SmarTS-Lab-Parapluie/Khorjin-IEC61850-90-5) 
which need to be installed in order use this package.

Each part includes three templates:
  - An empty project, allowing the user to create a custom WACS from scratch.
  - A project including Phasor POD.
  - A project including a Load control algorithm that utilizes the Phasor POD algorithm.
  
## Dependencies:
### LabVIEW extensions:
To utilize this package the following LabVIEW extensions need to be installed:
- LabVIEW Real-Time: [link](http://www.ni.com/labview/realtime/)
- LabVIEW FPGA: [link](http://www.ni.com/labview/fpga/)
- NI-cRIO compiler (depending on the NI-platform used): [link](http://www.ni.com/white-paper/9381/en/)

### Real-Time Data Mediators:
Audur provides two different templates, depending on the real-time data mediator that you will use and implicitly the control architecture that you will be able to use. These mediators have also been developed by SmarTS-Lab, and are available in the following link:
  - [S3DK](https://github.com/SmarTS-Lab-Parapluie/S3DK): Smart grid Synchrophasor Software Development Kit
  - [Khorjin](https://github.com/SmarTS-Lab-Parapluie/Khorjin-IEC61850-90-5): An IEC 61850-90-5 Gateway for Synchrophasor Data Transfer with support for IEEE C37.118.2 

## Quick-Start
- Instructions on how to use the S3DK-based controller templates can be found here: [S3DK Quick Start](https://github.com/Krokkodilli/Audur/blob/master/1_s3dk_template/READ_ME.md)
- Instructions on how to use the Khorjin-based controller templates can be found here: [Khorjin Quick Start](https://github.com/Krokkodilli/Audur/blob/master/2_khorjin_template/READ_ME.md)

## Use our software? = Cite our work! ;-)
If you use our software, please cite the following paper: 
> L. Vanfretti, G.M. Jonsdottir, M.S. Almas, E. Rebello, S.R. Firouzi and M. Baudette, "Audur – A platform for Synchrophasor-Based Power System Wide-Area Control System Implementation," submitted for review, Software X (Elsevier), December 2016. Pre-print: [here](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/SoftwareX2016.pdf).

## References/Documentation
Any further details can be found in the "Reference"-folder:

[SoftwareX2016.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/SoftwareX2016.pdf): "Audur - A Platform for Synchrophasor-Based Power System Wide-Area Control System Implementation", the pre-print of the Software X journal paper under revision that presents the Audur platform within this repository.

[GM2015.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/GM2015.pdf): "RT-SIL Performance Analysis of Synchrophasor-and-Active Load-Based Power System Damping Controllers", pre-print of the confrence paper presented at PES General Meeting in Denver 2015. It presents the RT-SIL simulation results of the load-control algorithm, before it was implemented in the LabVIEW FPGA used in the load control templates. 
The final paper is available through IEEEXplore in the following [link](http://ieeexplore.ieee.org/abstract/document/7286372/).
    
>    *Citation:* G. M. Jonsdottir, M. S. Almas, M. Baudette, M. P. Palsson and L. Vanfretti, "RT-SIL performance analysis of synchrophasor-and-active load-based power system damping controllers," 2015 IEEE Power & Energy Society General Meeting, Denver, CO, 2015, pp. 1-5. doi: 10.1109/PESGM.2015.7286372
  
[GM2016.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/GM2016.pdf): "RT-HIL Hardware Prototyping of Synchrophasor and Active Load-Based Power System Oscillation Damping Controller", a pre-print of a conference paper presented at PES General Meeting in Boston 2016. It presents a summary of the RT-HIL testing and development of the hardware prototype of the load controller. 
The final paper is available through IEEEXplore in the following [link](http://ieeexplore.ieee.org/document/7741307/).
      
>    *Citation:* G. M. Jonsdottir, M. S. Almas, M. Baudette, M. P. Palsson and L. Vanfretti, "RT-HIL hardware prototyping of synchrophasor and active load-based power system oscillation damping controllers," 2016 IEEE Power and Energy Society General Meeting (PESGM), Boston, MA, 2016, pp. 1-5. doi: 10.1109/PESGM.2016.7741307

[GMJthesis2015.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/GMJthesis2015.pdf): "Real-Time PMU-Assisted Wide-Area Oscillation Damping using Active Load Control", G.M. Jonsdottir Master's Thesis carried out at KTH SmarTS-Lab that presents the final work towards the development of the Audur platform.


[ER_1.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/ER_1.pdf): "PMU-based Real-Time Damping Control System Software and Hardware Architecture Synthesis and Evaluation," pre-print of the conference paper describing the first implementation of the software and hardware architecture used to develop Audur. The final paper is available through IEEEXplore in the following [link](http://ieeexplore.ieee.org/document/7285812/).

>    *Citation:* E. Rebello, L. Vanfretti and M. Shoaib Almas, "PMU-based real-time damping control system software and hardware architecture synthesis and evaluation," 2015 IEEE Power & Energy Society General Meeting, Denver, CO, 2015, pp. 1-5. doi: 10.1109/PESGM.2015.7285812
  

[ER_2.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/ER_2.pdf): "Software Architecture Development and Implementation of a Synchrophasor-based Real-Time Oscillation Damping Control System," pre-print of the conference paper describing the initial development of the software architecture and its implementation carried out through a `streamlining` process. The final paper is available through IEEEXplore in the following [link](http://ieeexplore.ieee.org/document/7165470/).

>    *Citation:* E. Rebello, M. S. Almas and L. Vanfretti, "An experimental setup for testing synchrophasor-based Damping control systems," 2015 IEEE 15th International Conference on Environment and Electrical Engineering (EEEIC), Rome, 2015, pp. 1945-1950. doi: 10.1109/EEEIC.2015.7165470

[ER_3.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/ER_3.pdf): "An Experimental Setup for Testing Synchrophasor-based Damping Control Systems," pre-print of the conference describint the expermental laboratory environment used to test the first version of the control software and hardware. The final paper is available through IEEEXplore in the following [link](http://ieeexplore.ieee.org/document/7232288/).

>    *Citation:* E. Rebello, L. Vanfretti and M. Shoaib Almas, "Software architecture development and implementation of a synchrophasor-based real-time oscillation damping control system," 2015 IEEE Eindhoven PowerTech, Eindhoven, 2015, pp. 1-6. doi: 10.1109/PTC.2015.7232288

[ERthesis2014.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/ERthesis2014.pdf): "Real Time PMU Assisted Wide Area Oscillation Damping using Compact Reconfigurable Controllers", E. Rebello's Master's Thesis carried out at KTH SmarTS-Lab that presents the development and testing of the Phasor POD algorithm in the first (prelimanary) hardware protoype.

![alt text](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/4_Images/Best_sample.png "Test Results from Oscilloscope")
