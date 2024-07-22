# Troubleshooting

Guidance on troubleshooting topic covered by the CompTIA Network+ exam.

## Table of Contents

- [Cable Troubleshooting](#cable-troubleshooting)
- [Network Troubleshooting](#network-troubleshooting)
- [Wireless Troubleshooting](#wireless-troubleshooting)

## Cable Troubleshooting

Cable troubleshooting involves identifying and resolving issues related to network cables. Various factors need to be considered when troubleshooting cable problems.

### Cable Considerations
- **Crossover cable**: A crossover cable is used to connect two devices of the same type, such as two computers or two switches, directly without the need for a separate network device like a router or switch.
- **Plenum vs. riser**: Plenum-rated cables are designed for use in plenum spaces, such as the space above a suspended ceiling or below a raised floor, where air circulation is required for heating, ventilation, and air conditioning (HVAC) systems. Riser-rated cables are designed for use in vertical shafts or risers between floors of a building.
- **Power over Ethernet (PoE)**: PoE is a technology that allows network cables to carry electrical power to devices such as IP phones, wireless access points, and security cameras, eliminating the need for separate power cables.
- **Rollover/console cable**: A rollover or console cable is a special cable used to connect to the console port of a network device, such as a router or switch, for configuration and management purposes.
- **Shielded vs. unshielded**: Shielded cables have an additional layer of protection against electromagnetic interference (EMI) and radio frequency interference (RFI), while unshielded cables do not have this extra layer of protection.

[Back to ToC](#table-of-contents)

### Common Issues
- **Attenuation**: Attenuation is the loss of signal strength as it travels through a cable. Excessive attenuation can lead to poor network performance or complete signal loss.
- **Bad ports**: Damaged or malfunctioning ports on network devices can cause connectivity issues and need to be identified and replaced.
- **dB loss**: Decibel (dB) loss refers to the reduction in signal strength along a cable. Excessive dB loss can result in poor network performance or signal degradation.
- **Dirty fiber**: Dirt, dust, or other contaminants on fiber optic cable connectors can cause signal loss and poor network performance. Proper cleaning of fiber connectors is essential for optimal performance.
- **Duplex mismatch**: A duplex mismatch occurs when the duplex settings (half-duplex or full-duplex) on two connected devices do not match, leading to collisions and poor network performance.
- **Incorrect pinout**: An incorrect pinout refers to the wrong wiring configuration of a network cable, which can cause connectivity issues or device malfunctions.
- **Interference**: Interference from external sources, such as electrical devices or other wireless networks, can cause signal degradation and affect network performance.
- **LED indicators**: LED indicators on network devices can provide valuable information about the status of cable connections, such as link activity and speed.
- **Open/short**: An open or short circuit in a network cable can result in a complete loss of connectivity or intermittent issues.
- **TX/RX reversed**: If the transmit (TX) and receive (RX) wires in a network cable are reversed, communication between devices will fail.
- **Wrong transceivers**: Using incorrect or incompatible transceivers (e.g., SFP modules) can lead to connectivity issues or poor network performance.

[Back to ToC](#table-of-contents)

### Specifications
- **Distance**: The maximum distance a network cable can run without signal degradation depends on the cable type and specifications. Exceeding the recommended distance can cause connectivity issues.
- **Speed**: The speed of a network connection is determined by the cable type, network devices, and other factors. Mismatched speeds between devices can result in poor performance.
- **Throughput**: Throughput refers to the actual amount of data that can be transferred over a network cable in a given time. It is affected by various factors, including cable quality, network congestion, and device capabilities.

[Back to ToC](#table-of-contents)

### Tools
- **Link speed checker**: A link speed checker is a tool used to determine the speed and duplex settings of a network connection.
- **Optical power meter**: An optical power meter is a device used to measure the power of an optical signal in a fiber optic cable, helping to diagnose issues related to signal strength and attenuation.
- **Protocol analyzer**: A protocol analyzer, also known as a packet sniffer, is a tool used to capture and analyze network traffic, helping to identify and troubleshoot network issues.
- **TDR Time Domain**: Time Domain Reflectometer (TDR) is a tool used to locate faults or breaks in a network cable by sending a signal down the cable and measuring the time it takes for the signal to reflect back from the fault.

## Interface Errors

Interface statistics, errors, and alerts provide valuable information about the health and performance of network interfaces.

- **CRC errors**: Cyclic Redundancy Check (CRC) errors occur when the received data does not match the expected CRC value, indicating data corruption during transmission.
- **CRCs**: CRC errors are often reported as a separate counter, indicating the number of frames with CRC errors received on an interface.
- **Encapsulation errors**: Encapsulation errors occur when there is a mismatch between the expected and actual encapsulation of a packet, such as an incorrect Ethernet frame type or VLAN tag.
- **Giants**: Giant frames are Ethernet frames that exceed the maximum allowed size (1518 bytes for untagged frames or 1522 bytes for tagged frames). Giant frames are often caused by misconfiguration or hardware issues.
- **Link state**: Link state refers to the current status of a network interface, such as up (operational), down (not operational), or administratively down (manually disabled).
- **Packet/byte counts**: Packet and byte counters keep track of the total number of packets and bytes sent and received on an interface, helping to monitor traffic levels and identify potential issues.
- **Runts**: Runt frames are Ethernet frames that are smaller than the minimum allowed size (64 bytes). Runt frames can be caused by collisions, hardware issues, or software problems.
- **Send/receive traffic**: Send and receive traffic counters display the amount of data sent and received on an interface, respectively. Monitoring these counters can help identify traffic imbalances or congestion.
- **Speed/duplex**: The speed and duplex settings of an interface determine the maximum data rate and communication mode (half-duplex or full-duplex). Mismatched settings between connected devices can lead to performance issues.

[Back to ToC](#table-of-contents)

## Network Troubleshooting

Network troubleshooting involves identifying and resolving issues that affect network performance, connectivity, and functionality.

### Identifying Probable Cause
- **Consider multiple approaches**: When troubleshooting network issues, it is essential to consider multiple approaches and perspectives to identify the root cause of the problem.
- **Develop hypotheses**: Based on the available information and symptoms, develop hypotheses about the potential causes of the issue and test them systematically.
- **Divide and conquer**: Break down complex network issues into smaller, more manageable components to isolate the problem and focus troubleshooting efforts.
- **Question the obvious**: Do not assume that the most obvious explanation is always correct. Question and verify assumptions to avoid overlooking potential underlying causes.
- **Top-down approach**: Start troubleshooting from the application layer and work down the OSI model layers to identify the source of the issue systematically.

[Back to ToC](#table-of-contents)

### Problem Identification
- **Approach multiple problems separately**: If multiple problems are present, address each issue separately to avoid confusion and maintain a structured troubleshooting process.
- **Determine if changes occurred**: Investigate whether any recent changes to the network configuration, hardware, or software might have contributed to the issue.
- **Duplicate problem**: Attempt to reproduce the problem in a controlled environment to better understand its characteristics and potential causes.
- **Gather information**: Collect relevant information about the affected devices, network topology, configurations, logs, and user reports to aid in the troubleshooting process.
- **Identify symptoms**: Clearly identify the symptoms of the issue, such as slow performance, connectivity loss, or application failures, to guide the troubleshooting efforts.
- **Question users**: Interview users experiencing the issue to gather additional details about the problem, including when it started, any specific error messages, and the impact on their work.

[Back to ToC](#table-of-contents)

### Testing Theories
- **Gather evidence**: Collect evidence that supports or refutes the hypotheses developed during the troubleshooting process, such as logs, packet captures, or performance metrics.
- **If confirmed**: If the evidence confirms a hypothesis, implement the appropriate solution and verify that it resolves the issue.
- **If not confirmed**: If the evidence does not support a hypothesis, revise the hypothesis based on new information and continue testing alternative theories.
- **Remain flexible**: Be open to adjusting the troubleshooting approach and considering alternative explanations as new information becomes available.
- **Test theory**: Systematically test each hypothesis by making changes to the network, such as modifying configurations, replacing hardware, or updating software, and observe the results.

[Back to ToC](#table-of-contents)

## Wireless Troubleshooting

Wireless networks introduce additional complexities and considerations when troubleshooting issues related to connectivity, performance, and security.

### Considerations and Limitations
- **Antenna cabling**: Ensure that antenna cables are properly connected, undamaged, and of the appropriate type and length to avoid signal loss or degradation.
- **Antennas**: Verify that the antennas are properly installed, oriented, and matched to the wireless access point or device for optimal signal coverage and strength.
- **AP association time**: Monitor the time it takes for wireless clients to associate with an access point. Excessive association times can indicate problems with the wireless network or client configuration.
- **Captive portal problems**: Troubleshoot issues related to captive portals, such as authentication failures, redirect problems, or compatibility issues with client devices.
- **Channel overlap**: Identify and minimize channel overlap between adjacent wireless networks to reduce interference and improve performance.
- **Channel utilization**: Monitor the utilization of wireless channels to identify congestion or interference from other devices operating on the same frequency.
- **Client disassociation**: Investigate frequent client disassociations, which can be caused by signal strength issues, interference, or authentication problems.
- **Distance**: Consider the distance between wireless clients and access points, as well as the presence of obstacles that can affect signal strength and coverage.
- **EIRP/power**: Verify that the Effective Isotropic Radiated Power (EIRP) and transmit power settings of wireless devices comply with regulatory requirements and are appropriate for the environment.
- **Encryption mismatch**: Ensure that the encryption settings (e.g., WPA, WPA2) match between the wireless network and client devices to avoid connectivity issues.
- **Insufficient coverage**: Identify areas with weak or no wireless signal coverage and consider adding additional access points or adjusting their placement to improve coverage.
- **Interference**: Investigate potential sources of interference, such as other wireless networks, cordless phones, microwaves, or metal objects, that can degrade wireless performance.
- **Placement**: Optimize the placement of wireless access points and client devices to minimize obstructions and maximize signal coverage.
- **Polarization**: Consider the polarization of wireless antennas (e.g., vertical or horizontal) and ensure that they match between access points and client devices for optimal signal reception.
- **RF signal loss**: Measure and monitor radio frequency (RF) signal loss to identify areas with weak signal strength and potential causes, such as distance, obstacles, or interference.
- **RSSI**: Monitor the Received Signal Strength Indicator (RSSI) to assess the signal strength and quality of the wireless connection.
- **Site survey**: Conduct a thorough site survey to assess the wireless network coverage, identify potential issues, and optimize access point placement and configuration.
- **Speed**: Verify that the wireless network and client devices are configured to operate at the appropriate speed (e.g., 802.11a/b/g/n/ac) for the desired performance and compatibility.
- **Throughput**: Measure the actual data throughput of the wireless network and compare it to the expected values to identify performance bottlenecks or limitations.
- **Wrong passphrase**: Ensure that wireless clients are using the correct passphrase (or pre-shared key) to authenticate and connect to the wireless network.
- **Wrong SSID**: Verify that wireless clients are attempting to connect to the correct Service Set Identifier (SSID) of the intended wireless network.

[Back to ToC](#table-of-contents)