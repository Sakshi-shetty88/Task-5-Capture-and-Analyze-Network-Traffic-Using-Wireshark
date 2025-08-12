# Task-5-Capture-and-Analyze-Network-Traffic-Using-Wireshark

## 📌 Objective
Capture live network packets using Wireshark, filter them by protocol, and identify at least three different types of traffic.

---

## 🛠 Tools Used
- **Wireshark** (Free, Open-Source)
- Windows Command Prompt (`ping` command)

---

## 📂 Files in this Repository
- `task5_network_capture.pcap` – Packet capture file containing TCP, TLSv1.3, QUIC, and ICMP traffic.
- `Task5_Report.pdf` – Detailed analysis report of captured protocols.
- `README.md` – This file.

---

## 🔍 Procedure
1. Installed and opened Wireshark.
2. Started capture on the active **Wi-Fi** interface.
3. Generated traffic by:
   - Browsing multiple websites (HTTPS sessions).
   - Running:
     ```bash
     ping google.com
     ```
4. Stopped capture after ~60 seconds.
5. Applied protocol filters:
   - `tcp`
   - `tls`
   - `icmp`
   - `quic`
6. Saved results and documented findings.

---

## 📡 Protocols Identified
1. **TCP** – Reliable transport layer protocol for web communications and other services.
2. **TLSv1.3** – Encrypts HTTPS sessions for secure browsing.
3. **ICMP** – Used for network diagnostics; `ping` traffic to `142.250.77.110` (Google).
4. **QUIC** – Modern UDP-based protocol for faster, secure connections.

---

## ✅ Outcome
Successfully captured and analyzed multiple protocols, gaining practical experience in packet inspection and filtering in Wireshark.

---

## 📷 Screenshots
<img width="1911" height="1073" alt="Screenshot 2025-08-12 092457" src="https://github.com/user-attachments/assets/bd207ba9-848e-4d4f-925e-0312d645209a" />


---

**Author:** Sakshi Shetty  
**Date:** August 2025
