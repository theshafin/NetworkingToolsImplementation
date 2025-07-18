## Lab – Configuring a Screened Subnet/DMZ Using pfSense

🎥 [Watch the walkthrough video](https://youtu.be/rO2jFewfGWE)

🎯 **Objective:**  
Set up a secure DMZ network behind a pfSense Security Gateway to host a web server and additional internet-facing devices.

🛠️ **Steps Performed:**
- Logged into pfSense management console (admin / P@ssw0rd).
- Created a new interface named `DMZ` with static IP `172.16.1.1/16`.
- Enabled the interface and added a firewall rule to allow all outbound traffic (`Allow DMZ to any`).
- Configured DHCP on the DMZ interface with an IP range of `172.16.1.100–172.16.1.200`.

🔐 **Purpose:**
- Isolate public-facing devices in a DMZ to protect internal resources.
- Simplify network management with DHCP while maintaining controlled access.
