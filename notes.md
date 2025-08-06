# Lesson 1

Course intro

# Lesson 2

- Internet is a graph
  - Nodes/Verteces are connected to each other, creating Links/Edges
  - It is a collection of devices interconnected, often through intermediary devices
- Networks are usually categorised by size
  - **PAN** Personal Area Network (small and local). E.g. Bluetooth, wireless devices
  - **LAN** Local Area Network: hosts communicating through switches/routers. You can connect LANs together via the Internet to form larger networks.
  - **WAN** Wide Area Network
- Protocols: ISO/OSI (theoretical) and TCP/IP (practical)
  - Initially, different organizations developed their own protocols with different rules, so hosts from different organizations could not communicate from different orgs were not able to communicate
  - It was necessary to use a shared model, first defined theoretically as the ISO/OSI model, and later implemented as the TCP/IP model
- TCP: Transport Layer
- IP: Network Layer

  <img src="./files/lesson2_1.png" alt="" width="350px">

- ISO Layers:
  Each layer handles a specific type of data and has a specific direction or function
  - **Physical Layer** (1): the lowest level, responsible for moving raw bits over cables or wireless signals
  - **Data-Lin Layerk** (2): Provides standards and devices for local networks. Ensures data is transmitted safely and correctly using Frames
  - **Network Layer** (3): Enables data transfer between different networks (beyond LANs) using IP.