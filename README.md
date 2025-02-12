# NEQ6-Next
  
This project replaces the NEQ6 stock stepper-driver electronics with an OnStep Mini based one. The implementation of this driver is designed as an extension for a Raspberry Pi 4B, where  it plugs into the 40-pin extension connector. Apart from OnStep, the extension board provides the power supply and a GPS module. The PCB connectors are identical to the original NEQ6 ones, so that the assembly is a drop-in replacement for the old driver, by merely plugging in the steppers and Polar alignment LED.  

A replacement front panel needs to be deviced that holds the NEQ-Next + RPi4 stack, and provides access to the RPI4 connectors. This is needed to connect all kinds of devices to the INDI server, such as camera and joystick. Operation of the assembly is completely remoted, by means of VNC remote desktop. This ensures that network problems for example do not interrupt photo sessions.  
 
The files cover a PDF with a description, a ZIP with KiCAD files and another ZIP with the 3D printing files.

