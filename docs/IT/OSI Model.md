### 1. Physical Layer

- **Function**: Responsible for the transmission of raw, unstructured data over physical mediums.
- **Protocols & Standards**: Ethernet, USB, Bluetooth.
- **Summary**: Deals with the physical connection between devices, including cables, switches, and network interface cards.

### 2. Data Link Layer

- **Function**: Handles error detection and correction, and frames data for transmission.
- **Protocols**: Ethernet, Wi-Fi, MAC (Media Access Control).
- **Summary**: Responsible for creating a reliable link between two physically connected nodes, using MAC addresses to manage how data is placed onto the network medium.

### 3. Network Layer

- **Function**: Determines the best path for data to travel from the source to the destination.
- **Protocols**: IP (IPv4 & IPv6), ICMP, OSPF.
- **Summary**: Focuses on routing and forwarding packets, using logical addressing (such as IP addresses) to direct packets to their destination.

### 4. Transport Layer

- **Function**: Ensures reliable data transfer between two devices.
- **Protocols**: TCP, UDP.
- **Summary**: Provides error checking and correction, and determines how much data is sent and at what rate, ensuring that the data arrives accurately and in sequence.

### 5. Session Layer

- **Function**: Establishes, maintains, and terminates connections between applications.
- **Protocols**: RPC, SQL, NFS.
- **Summary**: Acts as a controller that keeps applications' connections in sync, ensuring that data from the upper layers is properly synchronized and organized.

### 6. Presentation Layer

- **Function**: Translates data between the application and the transport layers, handling encryption and compression.
- **Protocols**: SSL/TLS, JPEG, MPEG.
- **Summary**: Transforms data into a format that the application layer can understand, performing functions such as data translation, encryption, and compression.

### 7. Application Layer

- **Function**: Provides network services to end-user applications.
- **Protocols**: HTTP, FTP, SMTP, DNS.
- **Summary**: The closest layer to the user, allowing interaction with network services through applications such as web browsers and email clients.

### Summary

The OSI Model serves as a guide for understanding the various tasks involved in network communication. By breaking down communication into seven layers, each with specific functions and protocols, the OSI Model provides a standardized framework that facilitates design, troubleshooting, and communication between different systems and networks. Understanding this model is essential for anyone working in networking or related fields.