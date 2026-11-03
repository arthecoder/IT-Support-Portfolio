# Hands-On IT Support & Systems Administration Portfolio

Welcome to my IT support portfolio. This repository serves as documentation for my hands-on technical training, where I utilize cloud-hosted enterprise networks to simulate corporate IT help desk scenarios, network diagnostics, and system administration.

---

## 🛠️ Technical Skill Stack
*   **Operating Systems:** Windows 10/11, Windows Server, Linux (Ubuntu/Debian)
*   **Networking Utilities:** `ping`, `traceroute`, `nslookup`, `ipconfig`/`ifconfig`, CIDR, DHCP, DNS
*   **System Administration:** Core Windows Event Viewer, Services Management, File Permissions, Local Security Policies

---

## 📂 Completed Training & Simulations

### 1. Enterprise Network Diagnostics & Infrastructure
*   **Platform Modules:** TryHackMe Pre-Security (Network Fundamentals)
*   **Skills Demonstrated:** Analyzing the OSI Model, troubleshooting TCP/IP connections, and diagnosing DNS/DHCP issues.
*   **Ticket Scenarios Handled:**
    *   *Scenario:* User reports an inability to connect to a specific internal server.
    *   *Resolution:* Used `nslookup` and `ping` to isolate whether the issue was a local network failure or a domain resolution error.

### 2. Windows System Configuration & Administration
*   **Platform Modules:** TryHackMe Pre-Security (Windows Fundamentals) & Cybersecurity 101
*   **Skills Demonstrated:** Navigating the Windows File System, utilizing Administrative Tools, auditing system logs, and managing user access controls (UAC).
*   **Ticket Scenarios Handled:**
    *   *Scenario:* Investigating a service that failed to launch on startup.
    *   *Resolution:* Utilized `services.msc` and audited the Windows Event Viewer logs to isolate the error code causing the application crash.

### 3. Linux Command Line & File Permissions
*   **Platform Modules:** TryHackMe Linux Fundamentals
*   **Skills Demonstrated:** Navigating the Linux CLI, modifying directory structures, managing user groups, and setting strict file permissions (`chmod`, `chown`).
*   **Ticket Scenarios Handled:**
    *   *Scenario:* A user lacks authorization to execute a critical script.
    *   *Resolution:* Audited the file's read/write/execute permissions and safely updated access control to align with the principle of least privilege.

---

## 🎯 Current Objectives
*   [ ] Complete the remaining modules of **Cybersecurity 101** (Focusing on identity management and defense fundamentals).
*   [ ] Spin up a local **Active Directory (AD)** virtual machine lab to practice corporate user provisioning and Group Policy Objects (GPOs).
