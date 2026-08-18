# 🌐 DHCP Server Lab

## 📝 Description
This lab builds upon the previous Active Directory project by demonstrating DHCP server deployment and configuration on an existing domain controller.

## 🛠️ Environment & Tools
* **Hypervisor:** VMware Workstation Pro
* **Operating Systems:** Windows Server 2022 (`DC01`), Windows 11 Enterprise (`CLIENT01`)
* **Core Technologies:**
  * Dynamic Host Configuration Protocol (DHCP)
  
## 🚀 Lab Walk-through

### 🔹 Phase 1: Initial Server Deployment & Configuration
1. Installed the DHCP server role on `DC01` via Server Manager. *(Figure 1.1)*

2. Configured a DHCP scope ranging from `192.168.64.150` to `192.168.64.200` for domain clients. *(Figure 1.2)*

3. Configured Option 003 (Router) to point to the default gateway and Option 006 (DNS Servers) to point to the domain controller. Retained the standard 8-day lease duration. *(Figure 1.3)* 

<br>

<details>
 <summary>📸 Click to view Phase 1 Screenshots</summary>
  <br>
  <p align="center">
   <img width="513" height="512" alt="dhcp-deployment" src="https://github.com/user-attachments/assets/404bef5c-ae6e-4662-988d-3b1a3fb3aaea" />
   <br>
   <b>Figure 1.1</b>
   <br><br>
   <img width="642" height="522" alt="scope_config1" src="https://github.com/user-attachments/assets/8a2bbde1-d1ba-4516-9537-97d9f66cccdb" />
   <br>
   <b>Figure 1.2</b>
   <br><br>
  <img width="498" height="121" alt="003 006-config-DHCP" src="https://github.com/user-attachments/assets/a7328b14-cc52-4913-8c98-1e1b481f4e22" />
  <br>
  <b>Figure 1.3</b>
  <br><br>
</p>
</details>

<br>

