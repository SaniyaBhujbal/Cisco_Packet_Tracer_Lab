# Cisco Packet Tracer - Local Network Lab 🌐

Welcome to my networking lab repository! As an engineering graduate transitioning into IT, I am documenting my hands-on configuration files here as I build them. 

## 🛠️ Project 1: Multi-Switch VLAN Segmentation Lab
I recently built and validated a local network simulation focusing on basic broadcast domain separation using VLANs.

### 📐 Network Topology Breakdown
*   **End Devices:** 4 PCs total, split across different logical networks.
*   **Switching Infrastructure:** 2 Cisco Switches connected together.
*   **Core Concepts Tested:** 
    * Creating and naming custom VLANs on Cisco switches.
    * Assigning switch ports to specific VLAN networks.
    * Separating broadcast traffic so PCs in different departments can't talk to each other without a router.

### 🔍 Verification Commands Used
To confirm the ports were mapped correctly, I used the following Cisco IOS command:
*   `show vlan brief` — To verify VLAN creation and interface bindings.
*   `ping` — To test and verify connectivity boundaries between the PCs.

---
## 📂 How to Use
You can download the `.pkt` file from this repository and open it directly inside Cisco Packet Tracer to view the configuration and port layouts!
