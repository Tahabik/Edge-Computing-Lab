## CICIoV2024DecimalCSV

### Overview:

The decimal dataset are part of the larger CICIoV2024 collection, designed to aid the development and validation of instruction detection system(IDS) for the IoV. These datasets are particularly valuable for researchers and practitioners who require a straightforward numerical representation of network data that aligns well with typical data analysis and machine learning workflows.

### Data Conent and Types:

The decimal dataset consist of several files, each corresponding to different types of network behavior, both normal and malicious. Here's a brekadown of types of data you'll find in the decimal format:

1. **Benign Traffic Data**: This dataset represent normal operation within the IoV environment. It includes traffic data that does not contain any **malacious** activities, serving as a baseline for what typical, non-threatening data traffic looks like.

2. **DoS Attack Data**: This file contains data simulating Denial of Service (DoS) attacks. These datasets are crucial for training and testing models to detect and respond to DoS scenarios, where the system is overwhelmed with traffic to disrupt service.

3. **Spoofing Attack Data**: There are multiple datasets for different spoofing attacks, each targeting specific vehicle controls:

4. **GAS Spoofing**:  Data that simulates attacks aimed at manipulating gas control systems.

5. **RPM Spoofing**: Includes malicious data affecting the revolutions per minute (RPM) controls.

6. **SPEED Spoofing**: Consists of spoofed data that targets vehicle speed controls

7. **STEERING_WHEEL Spoofing**:  Contains data that mimics attacks on the steering control systems.

### Dataset Structure and Features

Each file in the decimal dataset typically includes a wide range of features extracted from network traffic. These features might include, but not limited to:

1. **Timestamps**:  Indicating the time the data packets were captured.
2. **Packet Sizes**: The size of each packet in the network traffic.
3. **Protocol Types**: Which protocols are used in the communication sessions, e.g., TCP, UDP, HTTP.
4. **Source and Destination IP Address**: IP addresses from which data packets originate and where they are being sent.
5. **Port Numbers**:  Port numbers involved in the network communication.
6. **Payload Information**: This might include specific data extracted from the packet payloads, presented in decimals.
7. **Label**: Each instance is labeled as benign or specifies the type of attack, making it suitable for supervised learning tasks.
License:-
