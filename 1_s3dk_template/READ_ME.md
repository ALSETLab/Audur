S3DK Template

This Template is divided into three parts:

1. UImain.vi: Executed on the workstation PC used. Here S3DK is used to unwrap the PDC stream into raw LabVIEW measurements that are forwarded to the real-time part of the NI-cRIO using shared variables. The PDC stream that this template expects is two voltage and two current measurements.
2. RT.vi: Executed on the real-time processor of the NI-cRIO. Recives the PMU measurements and here signal selection is performed. In this template the user can select from 6 different input signals by default (active power, voltage vagnitude 1, voltage magnitude 2, current magnitude 1, current magnitude 2 and voltage angle difference). To modify the signal selection the Signal Selection Loop in RT.vi has to be modified. Note: The alpha and scaling have to be adjusted by the user based on the set up used.
3. FPGA.vi: Executed on the FPGA of the NI-cRIO. Recieves the selected input signal for the control algorithm and feeds out the control signal that should be connected to control the desiered component. Here the user can use the Phasor POD algorithm (Phasor_POD), the Load control algorithm (Load_control) or design their own algorithm from scratch (Empty project). 


