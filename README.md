# Servos and stepper motors controlled by the Intel® RTF Drone.

In this project, an Arduino will be connected to an Intel® RTF Drone using the USB port, or through the UART via the Telemetry port. Thus, all manner of things can then be controlled by the drone's code, such as servos, stepper motors, and a vast array of sensors.  

There are three physical methods for connecting Arduino:
1. Arduino USB to the RTF Drone USB
2. Arduino serial port to Telemetry port using a Bi-Directional Logic Level Converter
3. Arduino Due board to Telemetry port

The Intel® RTF Drone will run Ubuntu. The Ardino IDE will be downloaded and installed directly on the drone.  A mouse, keyboard, and an Arduino Uno or Megga can be plugged into the drone's USB port via a multi-port hub.  The drone can be used as a development workstation and Arduino scripts can be uploaded and run. All the Arduno sample scripts will run, including those that move a servo.



