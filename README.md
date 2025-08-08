**🛡 Firewall Rule Creation, Testing & Removal Report**

**Overview**

This project demonstrates how to create, test, and remove a firewall rule in Windows Defender Firewall to block inbound TCP connections on port 23 (Telnet).

**Steps Performed** 

- Open Windows Defender Firewall with Advanced Security (wf.msc).

- Create an Inbound Rule for TCP port 23 → Block the connection.

- Test the rule using the Telnet client (telnet localhost 23).

- Confirm connection failure.

- Remove the test rule to restore original state.

**Firewall Filtering Summary**

- A firewall filters network traffic based on predefined rules.

- Allow rules → Permit traffic matching criteria.

- Block rules → Drop or reject packets.

**Results** 

- Blocks all inbound TCP connections on port 23 (Telnet) to prevent remote access via insecure Telnet protocol.

