# PROJECTS-ON-AZURE-AZ-900-
# Azure Cloud Fundamentals (AZ-900) Comprehensive Project Lab
Welcome to my Azure Cloud Fundamentals (AZ-900) repository. This project is a hands-on exploration of the Microsoft Azure ecosystem, demonstrating the deployment, management, and security of various cloud services including IaaS, PaaS, Networking, Storage, and IoT. 
As a SecOps Engineer in the Making, I utilized these labs to build practical skills in cloud architecture while following industry best practices for resource management and connectivity. 
________________________________________
# 🛠 Project Management & Workflow

• To ensure a professional and organized deployment environment, the following standards were applied:
•	Local Documentation: Created dedicated folders on a local PC for each lab to house configuration screenshots and logs. 
•	Portal Access: All tasks were performed via the Azure Portal. 
•	Cost Management: Utilized the Azure Sandbox and the $200 free credit tier. 
•	Cloud Hygiene: Resources and resource groups were deleted immediately upon completion of each lab to prevent unnecessary costs. 
________________________________________
# 🌐 Virtual Networking (Networking & Connectivity)

• Designed and implemented a partitioned network architecture to simulate a multi-site environment. 
•	VNet Configuration: Established a Virtual Network using the $10.0.0.0/16$ address space. 
•	Subnetting:
o	Site 1: $192.168.20.0/24$ (Subnetted from $10.0.1.0/24$). 
o	Site 2: $192.168.40.0/24$ (Subnetted from $10.0.2.0/24$). 
•	Compute Integration: Deployed two Virtual Machines and associated them with their respective subnets (Server1 IP: 192.168.20.4; Server2 IP: 192.168.40.4). 
•	Connectivity Testing: Verified inter-site communication by allowing ICMP protocol via the following command:
# netsh advfirewall firewall add rule name="Allow ICMPv4-In" protocol="icmpv4:8,any" dir=in action=allow 
________________________________________
# 🏗 Infrastructure as a Service (IaaS)
• Focused on full control over the operating system and web server environment. 
•	Virtual Machine: Deployed a Windows Server 2016 instance with 8GB RAM. 
•	Web Server Role: Installed and configured the IIS (Internet Information Services) role. 
•	Security & Firewall: Enabled Port 80 (HTTP) for web traffic and Port 3389 (RDP) for remote management. 
________________________________________
# ☁️ Platform as a Service (PaaS)

• Streamlined application deployment without managing the underlying infrastructure. 
•	Web App Deployment: Created a web app in the Canada Central region, optimized for high performance. 
•	Code Deployment: Utilized the latest Microsoft Code deployment path. 
•	Live Modifications: Used the built-in Azure PowerShell terminal to modify the wwwroot and edit the live web page. 
•	Validation: Successfully verified the live site via a web browser. 
________________________________________
# 💾 Storage & Databases

• Managed structured and unstructured data while monitoring system health. 
•	Storage Accounts: Provisioned containers for Blob and File storage. 
•	Data Management: Uploaded files to blob storage and validated access. 
•	Insights: Utilized Azure Monitor/Insights to track storage account performance. 
•	Azure SQL: * Created an Azure SQL database instance. 
o	Security: Accessed the Query Editor using Microsoft Entra ID Authentication (formerly Azure AD) instead of standard SQL Server Authentication. 
________________________________________
# 🤖 Internet of Things (IoT) Hub

• Explored the lifecycle of connected devices and cloud telemetry. 
•	Hub Creation: Deployed an Azure IoT Hub and registered a new IoT device. 
•	Simulation & Testing: Verified connectivity using the Raspberry Pi Simulator and the IoT Plug and Play mobile app. 
•	Telematics Research: Explored AutoPi for connecting vehicles to the cloud to monitor metrics like speed, fuel efficiency, and engine health. 
________________________________________
# 👨‍💻 Connect with Me

•	LinkedIn: linkedin.com/in/hilarynwaja
•	Email: h.n@hilarynwaja.com

