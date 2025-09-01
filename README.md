# NECT-Project
Network and Cloud Technology (NECT) project covered the theoretical and practical aspects of network and cloud technology. Topics covered include how data is transmitted within an organisation and via the internet, as well as cloud computing technologies, its benefits, organisation, cloud usage, and risks.


My NECT consisted of 2 components;
 1) NECT Report Case Study
 2) NECT Presentation + Setup
 3) Demo of my Setup


--------------------------

## 1) NECT Report Case Study

#### Network Implementation
  ##### Logical Topology
  
  - 3-level smart home.
  - Main router placed on the 2nd floor for maximum coverage.
  - Backup router included for redundancy.
  
  ##### IoT & AWS Integration
  
  - IoT devices (Webcams, Smart Doors, Solar Panel) connected via home gateway → AWS S3 Glacier.
  - Remote control of devices via smartphones.
  - Smart doors and cameras installed for physical and data security.
  - Renewable energy integration via solar panels.
  
  ##### Routers & Access Points
  - Used access points on Level 2 to avoid router overload.
  - Switched to mesh routers instead of multiple routers for seamless coverage and reduced latency.
  
  ##### Switches
  - Added switches for faster local data transfer and improved efficiency.
  
  ##### Password Security
  - Enforced strong passwords (≥8 characters, mixed symbols/numbers).
  
  ##### Cloud Printing
  - Configured Google Cloud Print for easy document sharing and remote access.


#### Cloud Services & AWS Security
  ##### Amazon VPC
  
  - Created a Virtual Private Cloud for secure, isolated networking.
  - Benefits: device isolation, bandwidth optimization, improved privacy.
  
  ##### Amazon S3
  
  - Used for scalable, centralized storage of IoT data, camera recordings, and family files.
  - Security features: ACLs, server-side encryption, controlled access.
  
  ##### AWS IAM
  
  - Defined fine-grained access policies.
  - Managed users/groups for household access.
  - Enabled auditing and logging for accountability.
  
  ##### Amazon Cognito
  
  - Added MFA and OAuth 2.0 for secure authentication.
  - Allowed user synchronization across devices.
  - Provided customizable login workflows.

#### Sustainability Proposals
  Shubham
  - Energy-Efficient Ethernet (EEE) for reduced power consumption.
  - Promoted high device density to optimize resource usage.
  - Opted for mesh routers over multiple routers for efficiency.
  - Suggested network virtualization to reduce hardware footprint.
  - Advocated for responsible recycling of old equipment.
  - Recommended Wi-Fi optimization and dynamic routing protocols for energy savings.
  
  Tevian
  - Proposed Energy-Efficient Switches for dynamic power savings.
  - Suggested a low-energy entertainment center with smart TVs and power strips.
  
  Xin Yu
  - Suggested automatic timers for AC units and IoT devices.
  - Added solar panels for renewable energy contribution.
  - Upgraded networking devices to Energy Star certified models.
  
  Yi Jie
  - Implemented Edge Computing to process data locally, reducing bandwidth use.
  - Suggested low-power IoT protocols (e.g., Zigbee) for efficient communication.

  #### References
  - Key sources included AWS documentation, energy-efficient device research, and IoT/smart home best practices.

  #### Conclusion
  - This project successfully demonstrated:
  - A secure smart home network architecture.
  - Integration of IoT with AWS services.
  - Strong focus on cybersecurity, cloud authentication, and encryption.
    Sustainable energy strategies to minimize environmental impact.

--------------

## 2) NECT Presentation

**Network Design (Logical Topology)**
<img width="1880" height="723" alt="image" src="https://github.com/user-attachments/assets/f2d64688-9268-406f-a9b2-fdb638d9b014" />


### Overview
- Designed a smart home network for the Green Family.
- Covered: assumptions, AWS services, network design (wired & wireless), file/printer sharing, and sustainability proposals.

### Scenario & Assumptions
- 3-level house, main router on 2nd floor, mesh routers + switches for seamless coverage.
- IoT devices bought recently and CLS certified for security.
- Solar panels are planned as an alternate energy source.
- Family uses AWS free tier for cloud storage.
- Mostly working from home, requiring easy administrative tools.

### AWS Cloud Services
#### Networking
- Amazon VPC: Created logically isolated sections, subnets for security, and resource management.

#### Storage
- Amazon S3: Centralized, secure storage.
- Used for:
 - IoT data
 - Security camera recordings
 - Shared family files

#### Security
- AWS IAM: Managed users, permissions, and auditing.
- Amazon Cognito: Enabled secure authentication (MFA, OAuth2.0) and cross-device sync.

### Network Design
#### Wireless Connectivity
- Solar Panel: High-quality panel installed, supplies 20–25% of energy needs.
- Webcams: Capture intruders, secure rooms.
- Smart Doors: Restrict unauthorized access.
- Smartphones/Laptops: Control IoT devices via AWS cloud.

#### Wired Connectivity
- Home Gateway: Bridges IoT devices with router/cloud.
- Access Point: Expands Wi-Fi coverage and balances load.
- Mesh Routers: Eliminate dead zones across levels.
- Switches: Improve local performance, connect multiple devices.
- Modem: Provides ISP internet access.

#### File & Printer Sharing
- Printer connected via home router and Google Cloud Print.
- Allowed remote printing and sharing across devices.

### Sustainability Proposals
#### Shubham
- Higher device density → reduced redundancy, energy savings.
- Recycle old devices responsibly.
- Use Dynamic Routing Protocols to optimize traffic and cut energy use.

#### Xin Yu
- Automatic timers for AC and IoT devices.
- Solar panel with attic battery storage.
- Energy Star-certified networking equipment.

#### Tevian
- Energy-efficient switches to reduce power waste.
- Low-energy entertainment system (smart TVs, smart power strips).

#### Yi Jie
- Edge computing for IoT devices (process data locally, save bandwidth).
- Low-power IoT protocols (e.g., Zigbee) to extend device battery life and cut environmental impact.













