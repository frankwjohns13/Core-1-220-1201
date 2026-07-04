<!-- Core 1 Notes -->
# <div style="text-align: center;">CompTIA A+ Core 1 (220-1201) Notes</div>

<!-- Domain 1 -->
## Domain 1.0 - Mobile Devices (13%)

### 1.1 Given a scenario, install and configure laptop hardware and components Laptop Components

**Laptop Components**

- **Motherboard** — Main circuit board connecting all components
- **CPU** — Central Processing Unit (often soldered, not easily replaceable)
- **RAM** — SODIMM modules (laptop-specific form factor)
- **Storage** — M.2 SSDs, SATA SSDs, or HDDs
- **Display** — LCD, LED, OLED screens with specific connectors
- **Keyboard & Touchpad** — Often connected via ribbon cables
- **Battery** — Lithium-ion, removable or internal
- **Cooling System** — Fans and heat sinks (dust buildup is common)

**Installation & Replacement**

- Use proper ESD protection
- Follow manufacturer disassembly guides
- Common replacements: RAM, SSD, battery, screen, keyboard


### 1.2 Compare and contrast characteristics of components of mobile devices 

**Mobile Device Types**

-	**Laptops** — Full desktop OS, powerful hardware
-	**Tablets** — Touch-focused, lighter OS (iPadOS, Android)
-	**Smartphones** — iOS or Android
-	**Wearables** — Smartwatches, fitness trackers
-	**IoT Devices** — Smart home devices

**Connection Types**

-	USB-C (most common now)
-	Lightning (Apple)
-	Wireless (Wi-Fi, Bluetooth, NFC)

### 1.3 Given a scenario, set up and configure accessories and ports of mobile devices

**Common Ports**

-	USB-C (charging, data, video)
-	HDMI (video out)
-	microSD card slots
-	Headphone jacks (less common now)

**Accessories**

-	Docking stations
-	External monitors
-	Bluetooth peripherals
-	Stylus pens (iPad, Surface)


<!-- Domain 2 -->
## Domain 2.0 – Networking (23%)

### 2.1 Compare and contrast TCP and UDP ports, protocols, and their purposes

**Common Ports & Protocols**
- TCP (reliable, connection-oriented)
  -	80 (HTTP)
  -	443 (HTTPS)
  -	3389 (RDP)
  -	445 (SMB)

- UDP (faster, connectionless)
  - 53 (DNS)
  - 67/68 (DHCP)
  -	161 (SNMP)
  -	514 (Syslog)

### 2.2 Compare and contrast common networking hardware

**Network Devices** 

-	**Router** — Connects networks, performs NAT, provides Wi-Fi
-	**Switch** — Connects devices within a LAN
-	**Access Point** — Extends wireless coverage
-	**Firewall** — Protects network traffic
-	**Modem** — Connects to ISP

**Cabling**
-	Twisted Pair (Cat5e, Cat6, Cat6a)
-	Fiber Optic (single-mode, multi-mode)
-	Coaxial (older cable internet)

### 2.3 Compare and contrast wireless networking protocols

**Wi-Fi Standards**

-	802.11a/b/g/n/ac/ax (Wi-Fi 6)
-	Frequency bands: 2.4 GHz (range) vs 5 GHz (speed)

**Bluetooth**

-	Short-range wireless for peripherals

**NFC**

-	Very short range for payments and data transfer

### 2.4 Summarize the purposes of services provided by networked hosts

**Common Services**

-	**DHCP** — Assigns IP addresses
-	**DNS** — Resolves domain names
-	**HTTP/HTTPS** — Web traffic
-	**SMB** — File sharing
-	**RDP** — Remote desktop

### 2.5 Given a scenario, install and configure basic wired/wireless small office/home office (SOHO) networks

**SOHO Setup**

-	Connect modem → router
-	Configure Wi-Fi SSID and strong password
-	Enable WPA3 encryption
-	Set up guest network if needed

**Troubleshooting Connectivity**

-	Check cables
-	Restart devices
-	Verify IP configuration

<!-- Domain 3 -->
## Domain 3.0 – Hardware (25%)

### 3.1 Explain basic cable types and their connectors, features, and purposes

**Common Cable Types**

- **Twisted Pair (Ethernet)**
   - Cat5e, Cat6, Cat6a
   - RJ-45 connectors

- **Fiber Optic**
   - Single-mode (long distance)
   - Multi-mode (short distance)

- **Coaxial**
   - Older cable internet, BNC or F-connectors

- **USB**
   - Type A
   - Type C
   - microUSB

- **Thunderbolt** — High-speed data + video

### 3.2 Summarize common networking hardware

**Key Devices**
-	**Router** — Connects networks, NAT, firewall
-	**Switch** — Connects devices in a LAN
-	**Access Point** — Wireless coverage
-	**Modem** — ISP connection
-	**Firewall** — Security appliance

### 3.3 Given a scenario, install and configure basic wired/wireless SOHO networks

**SOHO Setup Steps**

-	Connect modem to router
-	Configure Wi-Fi SSID and WPA3
-	Set strong admin password
-	Enable guest network (optional)

**Troubleshooting**
-	Check physical connections
- Verify IP configuration
- Restart devices
-	Check for interference

### 3.4 Compare and contrast wireless networking protocols

**Wi-Fi Standards**
-	802.11ac (Wi-Fi 5)
-	802.11ax (Wi-Fi 6)
-	Frequency bands: 2.4 GHz (range) vs 5 GHz (speed)

**Bluetooth**
-	Short-range peripherals

**NFC**
-	Contactless payments


<!-- Domain 4 -->
## Domain 4.0 – Virtualization and Cloud Computing (11%)

### 4.1 Summarize cloud computing concepts

**Cloud Deployment Models**
- **Public Cloud** — Services provided by third-party (AWS, Azure, Google Cloud)
- **Private Cloud** — Dedicated infrastructure for one organization
- **Hybrid Cloud** — Combination of public and private
- **Community Cloud** — Shared among organizations with common needs

**Cloud Service Models**
- **IaaS** (Infrastructure as a Service) — Virtual machines, storage, networking
- **PaaS** (Platform as a Service) — Development platforms
- **SaaS** (Software as a Service) — Applications like Office 365, Gmail

### 4.2 Given a scenario, set up and configure client-side virtualization

**Virtualization Basics**
- **Hypervisor** — Software that creates and manages virtual machines
  - Type 1 (bare-metal): VMware ESXi, Microsoft Hyper-V
  - Type 2 (hosted): VMware Workstation, VirtualBox

**Common Use Cases**
- Testing different operating systems
- Running legacy applications
- Lab environments for learning

**Client-Side Virtualization Tools**
- VirtualBox (free)
- VMware Workstation Player
- Hyper-V (Windows Pro/Enterprise)

**Key Concepts**
- Resource allocation (CPU, RAM, storage)
- Snapshots for backups
- Guest additions/tools for better performance

<!-- Domain 5 --> 
## Domain 5.0 – Hardware and Network Troubleshooting (28%)

### 5.1 Given a scenario, apply troubleshooting methodology

**CompTIA Six-Step Troubleshooting Process**
1.	**Identify the Problem** — Gather information from user, check symptoms
2.	**Establish a Theory of Probable Cause** — Question the obvious, research
3.	**Test the Theory** — Confirm or disprove, escalate if needed
4.	**Establish a Plan of Action** — Implement solution
5.	**Verify Full System Functionality** — Test and apply preventative measures
6.	**Document Findings** — Record problem, actions, and outcome

### 5.2 Given a scenario, troubleshoot common hardware problems

**Common Hardware Issues**
- No power / won’t boot
- Overheating
- Blue Screen of Death (BSOD)
- No display / distorted image
- Strange noises (grinding, clicking)
- Device Manager errors (yellow exclamation marks)

**Troubleshooting Tools**
- Multimeter, POST card, loopback plugs
- System Information, Event Viewer
- Safe Mode, Startup Repair

### 5.3 Given a scenario, troubleshoot common networking problems

**Common Network Issues**
- No connectivity
- Intermittent connectivity
- Slow speeds
- IP address conflicts
- DNS resolution failures
- Limited or no connectivity

**Troubleshooting Steps**
- Check physical connections
- Verify IP configuration (ipconfig)
- Ping gateway and external sites
- Check DNS settings
- Restart router/modem

### 5.4 Given a scenario, troubleshoot and resolve printer problems

**Common Printer Issues**
- Paper jams
- Print quality problems (faded, streaks, ghosting)
- Printer offline
- Print queue stuck
- Driver issues

**Troubleshooting Steps**
- Check power and connections
- Clear print queue
- Restart Print Spooler service
- Update/reinstall drivers
- Run printer troubleshooter


<!-- End of Notes -->

<!-- Link to Core 2 notes -->
**View Core 2 Notes** → [View Core 2 Notes](https://github.com/frankwjohns13/Core-2-2202-1202)

<!-- Link back to the main A+ page -->
**View A+ Main Page** → [View A+ Main Page](https://github.com/frankwjohns13/CompTIA-A-Plus-Notes)

<!-- End of Page --> 




