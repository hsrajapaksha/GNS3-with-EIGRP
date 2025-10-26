
# 🛰️ GNS3 Project – EIGRP Configuration (3 Routers)

This project demonstrates a **GNS3 network topology** configured with **EIGRP (Enhanced Interior Gateway Routing Protocol)** using **three  routers**.
It’s designed for students to practice **dynamic routing** configuration and verification in a simulated environment.

---

## 📘 Project Overview

* **Topology:** 3 Routers connected via serial and FastEthernet links
* **Routing Protocol:** EIGRP
* **Platform:** GNS3
* **Files Included:**

  * GNS3 project file
  * Router configuration commands
  * Network topology screenshot

---

## ⚙️ Features

* EIGRP setup and verification
* Basic IP addressing and interface configuration
* Route summarization (optional)
* Network connectivity testing using ping and traceroute

---

## 📂 Project Files

All project files are stored in Google Drive.GOOGLE DRIVE LINK INSIDE EIGRP PROJECT FOLDER


---

## 🖼️ Topology Screenshot

Include your topology image here (example):
![EIGRP Topology]<img width="1912" height="999" alt="Screenshot 2025-10-26 090053" src="https://github.com/user-attachments/assets/6c6efae7-d998-42e8-acaf-730cda22ebe9" />


---

## 🧠 Configuration Commands (Sample)

```bash
Router(config)# router eigrp 100
Router(config-router)# network 10.0.0.0
Router(config-router)# network 192.168.1.0
Router(config-router)# no auto-summary
```

---

## 🧩 How to Use

1. Download the GNS3 project files from Google Drive.
2. Open the project in GNS3.
3. Start all routers.
4. Verify EIGRP configuration and connectivity.

---

## 🏁 Verification Commands

```bash
Router# show ip route
Router# show ip eigrp neighbors
Router# show ip protocols
```

---


