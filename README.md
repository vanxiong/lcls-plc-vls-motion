# lcls-plc-vls-motion

This repository contains the code for the VLS spectrometer motion control
PLC project. 

For more documentation on this system, please see the Confluence page:
TBD

## Adding the VLS to your motion PLC

This project is intended to run witin another PLC project. An example main
program is included to give an example of how to include the VLS into your
project and serves as a stand alone test program for the VLS spectrometer. 

 - [ ] Checkout this project from the appropriate Git repository. 
 - [ ] Open your project and add the PRG_VLS_MOTION program from the checked
       out VLS motion project.
 - [ ] Add this program to your main program, optionally checking the
       connection status of the VLS before executing it. 
