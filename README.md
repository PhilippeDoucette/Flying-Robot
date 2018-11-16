# Servos and stepper motors can be controlled by the Intel® RTF Drone.

An Arduino can be connected to the drone using the USB port, or through the UART via the Telemetry port. Thus, all manner of things can then be controlled by the drone's code, such as servos, stepper motors, and a vast array of sensors.  

There are three physical methods for connecting Arduino:
1. Arduino USB to the RTF Drone USB
2. Arduino serial port to Telemetry port using a Bi-Directional Logic Level Converter
3. Arduino Due board to Telemetry port

The Intel® RTF Drone can run Ubuntu. The Ardino IDE can be downloaded and installed directly on the drone.  A mouse, keyboard, and an Arduino Uno or Megga can be plugged into the drone's USB port via a multi-port hub.  The drone can be used as a development workstation and Arduino scripts can be uploaded and run. All the Arduno sample scripts will run, including those that move a servo.

It is not possible to connect the serial ports of of the Intel® Aero Compute Board directly to the serial ports of most Arduinos.  The Aero Compute Board has 3.3v ports, while most Arduino (Uno and Mega) have 5v ports. DO NOT CONNECT AERO SERIAL UART TO ARDUINO UNO THROUGH TX & RX pins.  However, the *Arduino Due* board has 3.3v ports and can be connected directly to the telemetry port.

The RTF Drone exposes a serial port via the Telemety connector, which is unused as the drone ships from the factory.  Remove the plastic cover to expose the connector:

rosserial_arduino can be installed on the drone so that the Arduino becomes a standard ROS node. The net result is that the RTF Drone is now a flying robot.
