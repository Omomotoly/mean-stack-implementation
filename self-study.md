# Self-Study Assignment

## 1. OSI Model

The **Open Systems Interconnection (OSI) Model** is a framework that explains how data is transmitted from one computer to another over a network. It consists of 7 layers, with each layer performing a specific function to ensure successful communication.

### Layer 1 – Physical Layer

The Physical Layer is responsible for transmitting data as electrical, optical, or radio signals through cables or wireless connections. It deals with the physical hardware used in networking, such as cables, switches, hubs, and network interface cards.

**Example:** Ethernet cable, fibre optic cable, and Wi-Fi signals.

### Layer 2 – Data Link Layer

The Data Link Layer ensures that data is transferred correctly between two devices on the same network. It detects transmission errors and uses MAC addresses to identify devices on the network.

**Example:** Ethernet, network switches, and MAC addresses.

### Layer 3 – Network Layer

The Network Layer is responsible for routing data from the source to the destination across different networks. It uses IP addresses to determine the best route for data packets.

**Example:** IP protocol and routers.

### Layer 4 – Transport Layer

The Transport Layer ensures that data is delivered accurately, completely, and in the correct order. It also manages data flow and performs error checking during transmission.

**Example:** TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).

### Layer 5 – Session Layer

The Session Layer establishes, manages, and terminates communication sessions between devices. It ensures that communication remains active while data is being exchanged.

**Example:** Video conferencing and online meetings.

### Layer 6 – Presentation Layer

The Presentation Layer translates data into a format that both communicating devices can understand. It is also responsible for data encryption, decryption, and compression.

**Example:** SSL/TLS encryption and file formatting.

### Layer 7 – Application Layer

The Application Layer is the layer closest to the user. It provides network services that allow software applications to communicate over a network.

**Example:** Web browsers, email applications, and file transfer services.

---

## 2. Load Balancing

### What is Load Balancing?

**Load balancing** is the process of distributing incoming network traffic or user requests across multiple servers instead of sending all requests to a single server. This helps improve performance, increases reliability, and prevents servers from becoming overloaded.

For example, when many users visit a popular website at the same time, a load balancer distributes the requests among several servers so that the website remains fast and available.

### Types of Load Balancing

#### 1. Hardware Load Balancing

Hardware load balancing uses a dedicated physical device to distribute incoming network traffic. It is commonly used in large organisations because it provides high performance and reliability.

#### 2. Software Load Balancing

Software load balancing uses software installed on servers to manage traffic distribution. It is more flexible and less expensive than hardware load balancing.

#### 3. Cloud Load Balancing

Cloud load balancing is provided by cloud service providers. It automatically distributes traffic across cloud servers and can easily adjust to changes in traffic demand.

### Traffic Load Balancing Techniques

#### Round Robin

Requests are sent to each server one after another in a fixed order. This ensures that every server receives approximately the same number of requests.

#### Least Connections

New requests are directed to the server with the fewest active connections. This helps distribute workloads more efficiently.

#### Weighted Round Robin

Servers with greater processing power are assigned more requests than servers with lower capacity.

#### IP Hash

The user's IP address determines which server processes the request. This allows the same user to remain connected to the same server during a session.

#### Least Response Time

Requests are directed to the server with the fastest response time, improving overall performance and user experience.

### Advantages of Load Balancing

- Improves website and application performance.
- Prevents servers from becoming overloaded.
- Increases system reliability and availability.
- Reduces downtime during periods of heavy traffic.
- Makes it easier to expand systems by adding additional servers.
- Provides a better user experience by reducing delays and improving response times.
Markdown