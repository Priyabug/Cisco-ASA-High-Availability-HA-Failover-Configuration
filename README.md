# 🌐 Cisco ASA High Availability (HA) Failover Configuration  

## 📌 Description  
Cisco ASA (**Adaptive Security Appliance**) is a security device that provides **firewall, VPN, and other security services** to protect networks and data. Understanding how to configure and manage **Cisco ASA firewalls** is essential for **network administrators and security professionals**.  

In these labs, you will gain **hands-on experience** configuring Cisco ASA firewalls using **real-world scenarios**. Each lab covers key topics, including:  
✅ **Basic Configuration**  
✅ **Security Policies**  
✅ **Network Address Translation (NAT)**  
✅ **Virtual Private Network (VPN)**  
✅ **High Availability (HA) & Failover**  

By completing these labs, you will develop **practical skills and in-depth knowledge** applicable in real-world network environments.  

---

### **🔧 Lab Topology**  
![Lab Topology](https://github.com/hegdepavankumar/cisco-asa-firewall-training/raw/main/Courses/All%20Labs/Topologies_Image/Active%20and%20Standby%20-%20Failover_Lab.PNG)  

---

## 🚀 Cisco ASA Lab Setup Guide  

### 🔹 **Download Required Images and Licenses**  
Before you start, download the necessary Cisco ASA images and VMware licenses:  

- 🔗 **[Cisco Images for GNS3 and EVE-NG](#)**  
- 🔗 **[VMware Workstation Pro 17 License Keys](#)**  
- 🔗 **[VMware ESXi License Keys](#)**  

---

## 🛠️ Set Up EVE-NG Environment  
1. Install and configure **EVE-NG** on your system following the provided instructions.  
2. Ensure that **Cisco ASA images** are correctly loaded into EVE-NG.  

---

## 📂 Import Lab Topologies  
- Import the provided **lab topologies** into your **EVE-NG environment**.  
- Verify that all devices are correctly mapped and functional.  

---

## 📝 Start Lab Exercises  
- Follow the step-by-step **lab instructions** provided in each folder.  
- You will be guided through **configuration steps** for each **lab topic**.  

---

## 🔬 Practice and Experiment  
- After completing the **initial configurations**, experiment with:  
  - 🔹 **Different failover settings**  
  - 🔹 **Redundant interfaces**  
  - 🔹 **Failover trigger conditions**  
- Enhance your **troubleshooting skills** by simulating various failure scenarios.  

---

## ✅ Verification  

### 🔍 **Check Failover Status**  
Run the following command to verify **failover synchronization** between the **active and standby units**:  

## 🔄 Test Failover Functionality  
To simulate a **failover event**, perform the following actions:  

- 🔹 **Disconnect interfaces** or **shut down the active unit**.  
- 🔹 Ensure **automatic switchover** to the standby unit.  

---

## 🌍 Verify Network Reachability  
After failover, test the connectivity of devices on:  

✅ **Inside Network**  
✅ **Outside Network**  
✅ **Stateful Link**  
✅ **Stateless LAN Network**  

✔ **Confirm** that all services remain functional during failover.  
✔ Validate that **redundancy mechanisms** operate as expected.  

---

🛠️ **Pro Tip:** Regularly **test failover scenarios** to ensure high availability and **minimal downtime** in production environments.

