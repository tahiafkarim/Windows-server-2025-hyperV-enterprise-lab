Windows Server 2025 Enterprise Infrastructure Lab (Hyper-V)

Project Overview
This project demonstrates the design and implementation of a small enterprise IT infrastructure using Hyper-V and Windows Server 2025 Datacenter (Evaluation).
The lab simulates a real-world corporate environment, including:
  - Virtualisation
  - Active Directory
  - File Services
  - DFS & Replication
  - NAT & Networking
  - SQL Server deployment
  - Backup & Recovery
  - Performance Monitoring

This project was built as part of my TAFE NSW Certificate IV in IT and reflects practical system administration skills.

🖥️ Environment Architecture
Virtualisation Platform
  - Hyper-V Manager
  - Generation 2 VM
  - 8200 MB RAM
  - Windows Server 2025 Datacenter (Evaluation)

Client Machines
  - Windows 10 Client
  - Windows 11 Client

🔧 Infrastructure Implementation

1️⃣ Virtual Machine Setup
  - Installed Hyper-V
  - Created Generation 2 VM
  - Allocated 8200MB RAM
  - Installed Windows Server 2025 from ISO
  - Configured server properties
  - Created VM checkpoints
  - Exported VM for full backup
📸 Screenshots available in /screenshots

2️⃣ Network Configuration & NAT
  - Configured Ethernet adapter
  - Assigned IP configuration
  - Configured NAT using Routing & Remote Access, allowing internal virtual machines to access external internet resources. 
  - Verified internet connectivity using IANA test and speed test.
  - Validated connectivity using ping between:
      - Server ↔ Windows 10
      - Server ↔ Windows 11

3️⃣ Windows Updates & Patch Management
  - Checked update history
  - Installed security patches
  - Verified system security status

4️⃣ SQL Server Deployment
  - Installed SQL Server 2022 Express Edition
  - Configured SQL Management Studio
  - Successfully connected from Windows 10 client to the server database instance

👥 Active Directory Implementation

Organizational Units Created
 - GelosIT
 - GelosAdmin

User & Group Management
 - Created user accounts
 - Assigned users to appropriate security groups
 - Applied role-based access control (RBAC)

📁 File Services & Network Shares
  - Created dedicated data drive to configure shared folders
  - Applied NTFS permissions
  - Implemented group-based read/write access control
