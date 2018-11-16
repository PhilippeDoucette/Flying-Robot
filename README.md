# Servos and stepper motors can be controlled by the Intel® RTF Drone.

An Arduino is connected to the drone using the USB port, or through the UART via the Telemetry port 

There are three methods for connecting Arduino:
1. Any Arduino USB to the RTF Drone USB
2. Any Arduino serial port to Telemetry port using a Bi-DirectionalLogic Level Converter
3. Arduino Due to Telemetry port

It is not possible to connect the serial ports of of the Intel® Aero Compute Board directly to the serial ports of most Arduinos.  The Aero Compute Board has 3.3v ports, while most Arduino (Uno and Mega) have 5v serials. The RTF Drone exposes a serial port via the Telemety connector, which is unused as the drone ships from the factory.  Remove the plastic cover to expose the connector:


