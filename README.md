# Bitdefender GravityZone – Device Control Policy Project

This project shows how I configured and tested a **Bitdefender GravityZone policy** with:

- **Device Control** (USB / external storage / Bluetooth / CDROM)
- **Whitelisting** using Device ID
- **Evidence from logs & endpoint notifications**

It simulates how a real company protects endpoints against **data leakage via USB**.

---

## 🎯 Objectives

- Block all unauthorized USB and removable storage devices.
- Block Bluetooth, imaging and CDROM usage.
- Allow only **IT-approved USB** based on Device ID.
- Monitor Device Control events in **Threats Xplorer** and on the endpoint.
- Show full end-to-end evidence in screenshots and test cases.

---

## 🛠 Environment & Tools

- **Bitdefender GravityZone** cloud console  
- **Bitdefender Endpoint Security Tools** on Windows 10 VM  
- Policies: `Device Control Policy`  
- Logs: Threats Xplorer → Device Control activity

---

## 📂 Project Structure

```text
Bitdefender-Device-Control-Project/
├── Screenshots/
├── Test-Cases/
└── README.md

