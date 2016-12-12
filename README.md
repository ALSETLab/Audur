# Audur
A Platform for Synchrophasor-Based PowerSystem Wide-Area Control System Implementation.

This is a LabVIEW package for developing custom Power System WACS implentations using the NI-cRIO platform.

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
- LabVIEW Real-Time [link](http://www.ni.com/labview/realtime/)
- LabVIEW FPGA [link](http://www.ni.com/labview/fpga/)
- NI-cRIO compiler (depending on the NI-platform used)[link](http://www.ni.com/white-paper/9381/en/)

### Real-Time Data Mediators:
Audur provides two different templates, depending on the real-time data mediator that you will use and implicitly the control architecture that you will be able to use. These mediators have also been developed by SmarTS-Lab, and are available in the following link:
  - [S3DK](https://github.com/SmarTS-Lab-Parapluie/S3DK): Smart grid Synchrophasor Software Development Kit
  - [Khorjin](https://github.com/SmarTS-Lab-Parapluie/Khorjin-IEC61850-90-5): An IEC 61850-90-5 Gateway for Synchrophasor Data Transfer with support for IEEE C37.118.2 

## Use our software? = Cite our work! ;-)
If you use our software, please cite the following paper: 
  -  L. Vanfretti, G.M. Jonsdottir, M.S. Almas, E. Rebello, S.R. Firouzi and M. Baudette, "Audur – A platform for Synchrophasor-Based Power System Wide-Area Control System Implementation," submitted for review, Software X (Elsevier), December 2016.

## References
Any further details can be found in the "Reference"-folder:

  -  SoftwareX2016.pdf: "Audur - A Platform for Synchrophasor-Based Power System Wide-Area Control System Implementation", the pre-print of the Software X journal paper under revision that presents the Audur platform within this repository.

  -  [GM2015.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/GM2015.pdf): "RT-SIL Performance Analysis of Synchrophasor-and-Active Load-Based Power System Damping Controllers", pre-print of the confrence paper presented at PES General Meeting in Denver 2015. It presents the RT-SIL simulation results of the load-control algorithm, before it was implemented in the LabVIEW FPGA used in the load control templates. The final paper is available through IEEEXplore in the following [link](http://ieeexplore.ieee.org/abstract/document/7286372/).
  
      - Citation: G. M. Jonsdottir, M. S. Almas, M. Baudette, M. P. Palsson and L. Vanfretti, "RT-SIL performance analysis of synchrophasor-and-active load-based power system damping controllers," 2015 IEEE Power & Energy Society General Meeting, Denver, CO, 2015, pp. 1-5. doi: 10.1109/PESGM.2015.7286372
  
-  [GM2016.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/GM2016.pdf): "RT-HIL Hardware Prototyping of Synchrophasor and Active Load-Based Power System Oscillation Damping Controller", a pre-print of a conference paper presented at PES General Meeting in Boston 2016. It presents a summary of the RT-HIL testing and development of the hardware prototype of the load controller. The final paper is available through IEEEXplore in the following [link](http://ieeexplore.ieee.org/document/7741307/).
      
      - Citation: G. M. Jonsdottir, M. S. Almas, M. Baudette, M. P. Palsson and L. Vanfretti, "RT-HIL hardware prototyping of synchrophasor and active load-based power system oscillation damping controllers," 2016 IEEE Power and Energy Society General Meeting (PESGM), Boston, MA, 2016, pp. 1-5. doi: 10.1109/PESGM.2016.7741307

  -  [GMJthesis2015.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/GMJthesis2015.pdf): "Real-Time PMU-Assisted Wide-Area Oscillation Damping using Active Load Control", G.M. Jonsdottir Master's Thesis carried out at KTH SmarTS-Lab that presents the final work towards the development of the Audur platform.

-  [ER_1.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/ER_1.pdf), 
      -  Citation: 
  
-  [ER_2.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/ER_2.pdf),
      - Citation:
  
-  [ER_3.pdf](https://github.com/SmarTS-Lab-Parapluie/Audur/blob/master/3_References/ER_3.pdf): Present the prior work done and the steps taken towards the development of this platform with special emphasis on the Phasor POD.
      - Citation: 

-  ERthesis2014.pdf: "Title", master thesis done at KTH SmarTS Lab describes the development and testing of the Phasor POD algorithm prelimanary hardware protoype.
