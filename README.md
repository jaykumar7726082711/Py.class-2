ye yy📒 Notes (11/08/2025, Py.class-2)

🖥️ Hardware & Companies

TSMC – Leading semiconductor manufacturing company (Taiwan).

ASML (Netherlands) – Provides lithography machines for chip manufacturing.


Processor Units

CPU (Central Processing Unit) – Made by Intel, AMD.

GPU (Graphics Processing Unit) – Made by NVIDIA.

DPU (Data Processing Unit) – Made by NVIDIA.

IPU (Intelligence Processing Unit) – Made by Intel.

HPU (Holographic Processing Unit) – Made by D-Wave.

TPU (Tensor Processing Unit) – Made by Google.



---

📡 Networking

NIC – Network Interface Card.

SMART NIC – Advanced NIC with offloading and acceleration features.

DPDK (Data Plane Development Kit) – Framework for fast packet processing.

SR-IOV (Single Root Input/Output Virtualization) – Allows multiple virtual machines to share a single physical NIC.



---

⚙️ Operating System Concepts

User Space – Where user applications run.

Kernel Space – Core part of OS, manages hardware and system calls.



---

💻 Programming Language Translation

Compiler

Converts high-level language → machine language.

Works on the entire program.

Generates machine code in form of “packs.”


Interpreter

Converts high-level language → machine language line by line.

Slower than compiler but easier for debugging.




---

🔢 Architectures

x86 – Common CPU architecture (Intel/AMD).

ARM – Power-efficient architecture (mobile devices, servers).

RISC-V – Open-source instruction set architecture.


🌐 How the Internet Works (Data Packet Journey)

1. User Request (Application Layer)

You type a website in your browser (e.g., google.com).

The request starts at the Application Layer (HTTP/HTTPS).



---

2. Breaking into Packets (Transport Layer)

The request is divided into small packets at the Transport Layer.

TCP → Reliable, no data loss (used for web browsing, file download).

UDP → Faster, but may lose data (used for video calls, streaming).



---

3. Adding IP Address (Network Layer)

Each packet gets a Source IP (your computer) and Destination IP (server).

This helps routers know where the packet should go.



---

4. Sending through NIC (Data Link Layer)

The packet goes to the Network Interface Card (NIC).

NIC converts it into electrical/optical/wireless signals.

Packet is sent over cable or WiFi.



---

5. Routers and Switches (Path Selection)

Switch → Works inside Local Area Network (LAN).

Router → Sends packet across different networks, chooses the best path.

Packets may travel through many routers (called hops).



---

6. Internet Backbone

High-speed fiber optic cables, data centers, and ISPs carry packets across countries.

This is the "highway" of the Internet.



---

7. Destination Server

The packet arrives at the server (e.g., Google).

Server processes the request and prepares a response packet.



---

8. Response Back to User

Response travels the same path backwards.

NIC of your computer receives it, OS assembles packets,

Browser displays the web page to you. ✅



---

📦 Key Terms

Packet = Small unit of data (Header + Payload).

Header = Source IP, Destination IP, Protocol info.

Firewall = Filters packets for security.

SMART NIC, DPDK, SR-IOV = Technologies to make packet processing faster.



---

🔁 Quick Flow (Diagram Recap)

User (Browser) → Transport Layer (TCP/UDP) → Network Layer (IP) → NIC → Router → Internet Backbone → Server → Response → Back to User
