Academics
🚗 An Efficient Approach for the Detection and Prevention of Gray-Hole Attacks in VANETs
📄 Description
This project proposes a novel and efficient method for detecting and preventing Gray-Hole attacks in Vehicular Ad Hoc Networks (VANETs). Gray-Hole attacks selectively drop or modify packets, compromising network reliability and security. Our approach uses anomaly detection techniques, dynamic trust and reputation management, and secure routing protocols to mitigate such threats.

The system was implemented in Network Simulator 2 (NS-2) using Tcl scripting language and evaluated on various performance metrics such as throughput, delay, energy consumption, and packet delivery ratio.


✨ Features
Dynamic Trust and Reputation System
Intrusion Detection System (IDS) with anomaly detection
Enhanced secure routing using AODV/DSR
Collaborative detection mechanism
Adaptive detection with machine learning
Low-overhead multipath routing
Simulation results using NAM and XGraph

🛠️ Technologies Used
Network Simulator 2 (NS-2)
Tcl (Tool Command Language)
XGraph and NAM for visualization
Ubuntu OS for development and simulation

🗂️ Folder Structure / Key Files
Src code

Here's your simulation parameters presented in a clear table format:

| **Parameter**       | **Value**               |
| ------------------- | ----------------------- |
| Simulation Area     | 1000 x 1000 m²          |
| Nodes               | 100                     |
| Communication Range | 250 m                   |
| Simulation Time     | 900 seconds             |
| Packet Size         | 512 bytes               |
| Traffic Type        | CBR (Constant Bit Rate) |
| Mobility Model      | Srinagar Highway        |

🚀 How to Run
Install NS-2 on your Linux system (tested on Ubuntu 10.04).
Place all Tcl scripts inside your project folder.
Run the main simulation file using:
ns simulation.tcl

Install NS-2 on your Linux system (tested on Ubuntu 10.04).
Place all Tcl scripts inside your project folder.
Run the main simulation file using:
ns simulation.tcl

Results
📦 Throughput: Improved delivery rate under attack conditions

🕒 Delay: Reduced end-to-end delay

🔋 Energy Efficiency: Lower energy consumption

📤 Packet Delivery Ratio (PDR): Enhanced delivery success rate

Future Enhancements

Integrate real-time GPS data for live VANET simulation
Use deep learning for more accurate anomaly detection
Extend support to other types of attacks (Black-Hole, Sybil, etc.)
