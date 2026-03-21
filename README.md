# HexaCore: Universal Robot Controller

<div align="center">
  <img src="ControlCabinet Solidworks.png" width="600" alt="HexaCore Control Cabinet Render"/>
</div>

<div align="center">
    <img src="https://img.shields.io/badge/Status-In--Development-blue?style=for-the-badge" alt="Status">
    <img src="https://img.shields.io/badge/License-AGPL--3.0_&_CC_BY--SA_4.0-green?style=for-the-badge" alt="License">
</div>

### **PC-Based Industrial Control Cabinet Architecture**
>
> The hardware schematic for the "Brain" of the HexaKinetica ecosystem. This controller is designed to drive **HexaArm Medium**, **HexaArm Heavy**, and **HexaAMR** platforms using standard PC components and EtherCAT.
#### 🚧 Status: COMING SOON (Q2 2026)
*Safety schematics are currently under review.*
---

#### Tech Specs
| Feature | Spec |
| :--- | :--- |
| **Compute** | Standard x86 Mini-IPC |
| **Bus** | EtherCAT (1 kHz Loop) |
| **Voltage** | 220V AC | 24V DC Bus |
| **Safety** | Hardware E-Stop Chain + Safety Relays |

#### Repository Contents (Roadmap)

#### `/Shematic`
*   **Breakout Boards:** Schematics for custom PCBs (EtherCAT signal distribution, IO isolation).
*   **Power Distribution:** Wiring diagrams for 220V -> 48V conversion and braking resistors.

#### `/CAD`
*   **DIY Build Guide:** How to build a compliant controller using off-the-shelf components (MeanWell PSUs, standard PC cases).
*   **BOM:** Shopping list for components.

---

### 🔗 Compatible Robots
*   🦾 **Mechanics:** [HexaArm-Medium](https://github.com/HexaKinetica/HexaArm-Medium)
*   💻 **Operating System:** [HexaMotion](https://github.com/HexaKinetica/HexaMotion_)

---



**[HexaKinetica.com](https://hexakinetica.com)**
