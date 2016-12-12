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
  - [S3DK](https://github.com/SmarTS-Lab-Parapluie/S3DK)
  - [Khorjin](https://github.com/SmarTS-Lab-Parapluie/Khorjin-IEC61850-90-5) 

## Citation


## References
Any further details can be found in the "Reference"-folder:

SoftwareX2016.pdf: "Audur - A Platform for Synchrophasor-Based Power System Wide-Area Control System Implementation", a Software X journal paper under revision that presents the Audur platform.

GM2015.pdf: "RT-SIL Performance Analysis of Synchrophasor-and-Active Load-Based Power System Damping Controllers", confrence paper presented at PES General Meeting in Denver 2015. Presents the RT-SIL simulation results of the load-control algorithm.

GM2016.pdf: "RT-HIL Hardware Prototyping of Synchrophasor and Active Load-Based Power System Oscillation Damping Controller", confrence paper presented at PES General Meeting in Boston 2016. Presents a summary of the RT-HIL testing and development of the hardware prototype of the load controller.

GMJthesis2015.pdf: "Real-Time PMU-Assisted Wide-Area Oscillation Damping using Active Load Control", master thesis from KTH about the development of the Audur platform.

ER_1.pdf, ER_2.pdf & ER_3.pdf: Present the prior work done and the steps taken towards the development of this platform with special emphasis on the Phasor POD.

ERthesis2014.pdf: "Bla", master thesis done at KTH SmarTS Lab describes the development and testing of the Phasor POD algorithm prelimanary hardware protoype.
