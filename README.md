# IoT Experiments

### Student Details

NAME: J Phani Kumar

1ST M.Tech - CSE

261FB04013

# IoT Experiments and Network Simulation Projects

A collection of IoT experiments and networking simulations created for learning, experimentation, and practical implementation.

### 2. Layers of IoT — Virtual Monitoring Notebook

**Objective:** Demonstrate selected IoT and OSI-layer concepts using Python, generated data, tables, charts, and simple condition checks.

**Tools**

- Python
- Jupyter Notebook
- pandas
- Matplotlib

**Layers Demonstrated**

- **Perception Layer:** Generates simulated temperature, humidity, and light readings, plots them, and flags high temperatures.
- **Network Layer:** Simulates sensor-data packets with packet size, latency, and transmission status.
- **Data Link Layer:** Simulates frames with MAC addresses, frame sizes, and checksum status.
- **Transport Layer:** Simulates TCP/UDP segments, port numbers, sizes, retries, delays, and delivery status.
- **Session Layer:** Simulates sessions with IDs, users, durations, and states.
- **Presentation Layer:** Encodes sample messages as UTF-8 hexadecimal strings, decodes them, and checks the result.

### 3. NS-3 Network Simulation Programs

**Objective:** Explore networking concepts by simulating nodes, links, routing, transport protocols, and network performance with NS-3 and C++.

**Programs**

1. **UDP Echo Communication Between Two Nodes** — Simulates UDP client-server communication with an echo server.
2. **Bandwidth, Delay and Throughput Analysis Using FlowMonitor** — Measures packet statistics, average delay, and throughput for UDP traffic.
3. **Three-Node Network Communication Using Routing** — Sends UDP packets from a source through an intermediate router to a destination.
4. **IoT Gateway Communication Using NS-3** — Simulates four IoT nodes sending UDP packets to a central gateway.
5. **Performance Comparison of TCP and UDP Protocols** — Runs TCP and UDP traffic and compares received bytes.
6. **Network Congestion and Throughput Analysis** — Simulates UDP traffic over a limited-bandwidth link with a small queue and measures received throughput.

