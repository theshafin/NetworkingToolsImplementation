## Snort Configuration on pfSense

🎥 [Watch the walkthrough video](https://youtu.be/Y-x2p0PgF48)

🎯 **Objective:**  
Set up Snort IDS on pfSense to monitor and block threats on the WAN interface.

🛠️ **Summary of Actions:**
- Signed into pfSense and configured Snort rule sets (Registered, GPLv2, ET Open, OpenAppID).
- Set rule updates to run every 4 days at 12:10 a.m.
- Enabled auto-blocking (1-day ban) and system log alerts.
- Assigned Snort to the WAN interface as "Snort-WAN".
- Started Snort with blocking and alerting enabled.

🔐 **Purpose:**  
Deploy intrusion detection on the edge of the network to detect and respond to external threats.
