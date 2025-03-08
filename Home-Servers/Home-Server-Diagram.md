This will give you a clear visual representation of how everything will connect and operate.

//TODO: Insert Home Network Diagram here.


Here is the network diagram for your home lab and media center setup:  

- **Internet → Router/Firewall (UDM-Pro)**: This is your core router/firewall for network segmentation.  
- **Router → 24-Port Managed Switch**: Handles network traffic and VLAN management.  
- **Primary Server**: Hosting Proxmox, ESXi, or Docker for virtualization.  
- **NAS (TrueNAS/Synology)**: For media storage, backups, and Plex server.  
- **Media Center**: Connects to your NAS for media streaming.  
- **Wi-Fi Access Points**: Connect mobile devices, smart TVs, etc.  
- **Power Management**: Rack PDU and UPS for power redundancy.  
