# Task-1

### Task Title: Scan Your Local Network for Open Ports

### 🎯 Objective
To learn how to discover open ports on devices in a local network using Nmap. This helps understand potential network exposure and security risks.

---

### 🛠 Tools Used
- **Nmap** (Free & Open-source Network Scanner)
- **Operating System**: Linux (can be done on Windows/Mac as well)

---

### 🔍 Steps Performed

1. **Installed Nmap**  
   - Downloaded and installed Nmap from the [official website](https://nmap.org/).

2. **Identified Local IP Range**  
   - Used `ifconfig` / `ip a` to find the local IP range.
   - Example: `192.168.1.0/24`

3. **Performed a TCP SYN Scan**
   - Command:  
       nmap -sS 192.168.1.0/24
    

4. **Noted Down IPs and Open Ports**
   - Identified hosts and associated open ports.

5. **Analyzed Potential Security Risks**
   - Matched common services with known risks, e.g., FTP, SMB, RDP.

6. **Saved Results**
   - Results documented in a `.txt` report for submission.

---

### ✅ Outcome
- Gained hands-on experience with port scanning.
- Learned how to identify and interpret open ports in a local network.
- Understood basic network reconnaissance techniques and security implications.

---

### 📚 Concepts Learned
- Port scanning (TCP SYN, TCP Connect, UDP)
- IP ranges and subnetting basics
- Common network services and vulnerabilities
- Importance of securing open ports
