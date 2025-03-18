# Creating Home Servers using Mini-Racks

There is a trend of using mini-racks for the home user or those studying for a job in networking or information security. This is just the beginning of a guide on how to set up a mini rack for such use cases.


## Equipment Used in a Mini-Rack Project  
Based on the mini-rack project, the key equipment used includes:  

1. **Mini Rack Chassis** – A small, portable rack (like a 6U or 9U rack) for mounting hardware:

**RackChoice 1U Compact Server/Desktop Mini-ITX Chassis**  
Features an internal drive bay accommodating either one 3.5" HDD or two 2.5" SSDs. Equipped with two 40mm fans (expandable to three) and a hidden front grille for efficient airflow. Price: $99.99. citeturn0search1

**In Win IW-RF100-S315 1U Short-depth Rackmount Server Chassis**  
Compatible with Mini-ITX and ATX motherboards. Includes a 315W power supply and front ports with two USB 3.0 connections. Dimensions: 1.75" x 19.00" x 14.37". Price: $176.99. citeturn0search2

**iStarUSA S-35-B4RD Tower Compact Stylish Chassis**  
Supports Mini-ITX motherboards. Features four hot-swap 3.5" drive bays and one internal 2.5" drive bay. Includes one expansion slot and two front USB 2.0 ports. Dimensions: 8.90" x 8.68" x 12.76". Price: $175.95. citeturn0search2

**iStarUSA D-400-6-Blue 4U Rackmount Compact Stylish Server Chassis**  
Compatible with motherboards up to 12" x 10". Offers six external 5.25" drive bays, two external 3.5" drive bays, and two internal 3.5" drive bays. Front ports include two USB 2.0 connectors. Dimensions: 19.0" x 7.0" x 20.8". Price: $199.99. citeturn0search2

**Sonnet RackMac mini 1U Rack Enclosure**  
Designed to securely install one or two Mac minis in a standard 1U rackmount enclosure. Provides front panel access to the power button, IR sensor, and USB port for each Mac mini. Ensures proper airflow to keep the installed Mac minis cool. Price: $209.99. citeturn0search8
   
2. **Compact Servers/Nodes** – Small form factor servers or Raspberry Pis for computing tasks.  

**HPE ProLiant DL20 Gen10**  
A compact 1U rack server designed for versatility and performance. Supports Intel® Xeon® E processors, up to 64 GB DDR4 ECC memory, and offers flexible storage options with up to two Large Form Factor (LFF) or four Small Form Factor (SFF) drives. Ideal for small businesses and remote offices requiring a balance of performance and affordability.

**Dell PowerEdge R240**  
An entry-level 1U rack server optimized for budget-conscious businesses. Equipped with Intel® Xeon® E-2200 processors, supports up to 64 GB DDR4 memory, and provides flexible storage configurations with up to four 3.5-inch cabled hard drives. Suitable for web hosting, mail, and file servers.

**Lenovo ThinkSystem SR250**  
A 1U rack server offering enterprise-class features for small to medium-sized businesses. Supports Intel® Xeon® E-2100 processors, up to 64 GB DDR4 memory, and flexible storage options, including up to four 3.5-inch or eight 2.5-inch drives. Ideal for workloads like virtualization and cloud computing.

**Supermicro SuperServer 5019C-M**  
A compact 1U rack server featuring Intel® Xeon® E processors, up to 64 GB ECC DDR4 memory, and support for up to four 3.5-inch hot-swap SATA drives. Designed for applications requiring reliability and performance in a space-saving form factor.

**Inspur NF5280M6**  
A 2U dual-socket rackmount server suitable for data analysis and processing, as well as distributed storage in deep learning training. Supports the latest Intel® Xeon® Scalable processors and offers flexible storage configurations. 

Please note that compatibility with specific mini-rack enclosures depends on the enclosure's dimensions and mounting specifications. It's advisable to verify the server's dimensions and consult the enclosure's documentation to ensure proper fit and compatibility. 

3. **Network Switch** – Managed or unmanaged gigabit network switch for interconnecting devices.  

When selecting a network switch for a home mini-rack or server setup, it's essential to consider factors such as port count, speed, management capabilities, and rack compatibility. Below is a selection of both new and used rack-mountable switches suitable for home networks:

**Cisco CBS350-8MGP-2X**  
This switch offers 8 Gigabit Ethernet ports with PoE+ support and 2 10-Gigabit SFP+ uplink ports. It's known for its robust features suitable for advanced home networking needs. citeturn0search0

**TP-Link TL-SG3210XHP-M2**  
Featuring 8 Multi-Gigabit ports with PoE++ and 2 10-Gigabit SFP+ slots, this switch is ideal for high-speed home networks requiring Power over Ethernet capabilities. citeturn0search0

**TRENDnet TPE-TG380**  
An 8-port Gigabit PoE+ switch that's easy to set up, making it suitable for straightforward home networking requirements. citeturn0search0

**Dell PowerConnect 6224**  
A 24-port Gigabit managed switch with robust features, suitable for complex home networks. Used models are available at reasonable prices. citeturn0search1

**Cisco SG300-10**  
This 10-port Gigabit managed switch includes 2 SFP ports, offering flexibility for fiber connections. It's a reliable choice for home setups. citeturn0search1


4. **Storage Devices** – NAS units or self-built storage servers.  
5. **Power Distribution Unit (PDU)** – Provides power to all devices from a single source.  
6. **Cooling Solutions** – Active cooling like rack-mounted fans.  
7. **UPS (Uninterruptible Power Supply)** – Provides backup power to the rack.  
8. **Cable Management Accessories** – Velcro ties, rack rails, and patch panels.  

---

### Guidelines for Building a Mini-Rack Home Lab  
1. **Size Consideration** – Choose a small, portable rack (6U-12U) if you plan to move it frequently.  
2. **Power Efficiency** – Opt for energy-efficient devices like Intel NUCs, Raspberry Pis, or ARM-based servers.  
3. **Networking** – Use a managed switch for VLAN management, remote access, and network isolation.  
4. **Storage** – Consider NAS units (like Synology) or build your own with TrueNAS or Unraid.  
5. **Redundancy** – Install a UPS to protect against power outages and data loss.  
6. **Expandability** – Use a rack that allows easy expansion in the future.  
7. **Noise Reduction** – Look for low-noise cooling options and SSDs for quieter operation.  

For a detailed breakdown and parts list, visit: [Jeff Geerling's Mini-Rack Project](https://www.jeffgeerling.com/blog/2025/project-mini-rack-compact-and-portable-homelabs).