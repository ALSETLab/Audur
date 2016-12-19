Khorjin Template

This template is divided into two parts and runs only on the NI-cRIO.

1. RT.vi: Executed on the real-time processor of the NI-cRIO. Here Khorjin is used to unwrap the PDC stream into raw LabVIEW measurements. This template expects a PDC stream including one voltage measurement and one current measurement. The input signal used in this template is active power but can easily be modified by the user. The input signal is finally forwarded to the FPGA of the NI-cRIO.
2. FPGA.vi: Executed on the FPGA processor of the NI-cRIO. This is the same file as is used for the S3DK template.
