<h1>Cisco ASA High Availability HA Failover Configuration.</h1>

<h2>Description</h2>
Cisco ASA (Adaptive Security Appliance) is a security device that provides firewall, VPN, and other security services to protect networks and data. Understanding how to configure and manage Cisco ASA firewalls is essential for network administrators and security professionals.

In these labs, you will get hands-on experience with configuring Cisco ASA firewalls using real-world scenarios. Each lab is designed to cover specific topics, such as basic configuration, security policies, NAT, VPN, high availability, and more. By completing these labs, you will gain practical skills and knowledge that you can apply in real-world network environments.
<br />

<img src="https://github.com/hegdepavankumar/cisco-asa-firewall-training/raw/main/Courses/All%20Labs/Topologies_Image/Active%20and%20Standby%20-%20Failover_Lab.PNG" alt="Lab Topology" style="max-width: 100%;">

<h2>Cisco ASA Lab Setup Guide</h2>

<h3>Download Required Images and Licenses</h3>
Before you start, download the required Cisco ASA images and VMware licenses:<br>
<b>- **[Cisco Images for GNS3 and EVE-NG](#)** </b><br>
<b>- **[VMware Workstation Pro 17 License Keys](#)**</b><br>
<b>- **[VMware ESXi License Keys](#)**</b>

## Set Up EVE-NG Environment
Install and configure EVE-NG on your system following the provided instructions.

## Import Lab Topologies
Import the lab topologies provided in this repository into your EVE-NG environment.

## Start Lab Exercises
Follow the lab instructions provided in each lab folder. You will be guided through the configuration steps for each lab topic.

## Practice and Experiment
Once you have completed the initial configurations, feel free to experiment with different settings and scenarios to further enhance your understanding.

## Verification
Verify failover status and synchronization between active and standby units using the show failover command.
Test failover functionality by disconnecting interfaces or shutting down the active unit to simulate failover.
Verify reachability of devices on the Inside, Outside, stateful link, and stateless LAN networks from both firewalls.

