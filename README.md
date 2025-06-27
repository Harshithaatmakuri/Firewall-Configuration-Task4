# Task 4 – Firewall Configuration (Windows)

## 🔐 Objective
To configure Windows Firewall to block Telnet traffic (port 23) and gain practical experience with basic firewall rule management.

## 🧰 Tools Used
- Windows Defender Firewall with Advanced Security (GUI)

## ✅ Actions Performed

1. Opened Windows Firewall using `wf.msc`.
2. Navigated to **Inbound Rules** in the left sidebar.
3. Clicked **New Rule** on the right panel and selected:
   - **Rule Type**: Port
   - **Protocol**: TCP
   - **Port**: 23
   - **Action**: Block the connection
   - **Profile**: Domain, Private, Public
   - **Name**: `Block_TELNET_Port_23`
4. Verified the rule is listed and active in Inbound Rules.
5. Took a screenshot of the rule as evidence.
6. (Optional) Removed the rule after testing.

## 🧠 Summary
- **Telnet (port 23)** is outdated and insecure.
- Blocking it enhances system security.
- This task demonstrates basic network traffic filtering using Windows Firewall.

## 📸 Screenshot
- `firewall_telnet_block.png` – shows the blocked Telnet rule in the firewall.

## 📘 Outcome
Successfully created, tested, and managed a firewall rule in Windows to block Telnet traffic, demonstrating understanding of inbound rules and traffic filtering.

