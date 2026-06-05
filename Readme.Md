# Cisco Packet Tracer - Local Network Lab 🌐

Welcome to my networking lab repository! As an engineering graduate transitioning into IT, I am documenting my hands-on configuration files here as I build them. 

## 🛠️ Project 1: Multi-Switch VLAN Trunking Architecture
I have built and validated a local network simulation focusing on basic broadcast domain separation and multi-switch trunk links.

### 📐 Network Topology Breakdown
*   **End Devices:** 4 PCs total, split across different logical networks.
*   **Switching Infrastructure:** 2 Cisco Switches connected together.
*   **Core Concepts Tested:** 
    * Creating and naming custom VLANs on Cisco switches.
    * Assigning switch ports to specific VLAN networks.
    * Configuring **802.1Q Trunking** to allow VLAN traffic to travel between both switches.

### 🔍 Verification Commands Used
To confirm the ports and trunk lines were mapped correctly, I used the following Cisco IOS commands:
*   `show vlan brief` — To verify VLAN creation and interface bindings.
*   `show interfaces trunk` — To verify active trunk links between the switches.
*   `ping` — To test and verify connectivity boundaries between the PCs.

---
## 📂 Repository Layout
*   📂 **`Switching-Blueprints/`** — Contains the `.pkt` (Packet Tracer) source files for direct environment inspection, featuring the *Vlan Trunking architecture* lab.

---
## 🚀 How to Use
You can navigate into the `Switching-Blueprints` folder above, download the `.pkt` file, and open it directly inside Cisco Packet Tracer to view the configuration and port layouts!
