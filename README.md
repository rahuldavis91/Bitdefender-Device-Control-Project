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


# 🔐 Bitdefender GravityZone – Device Control Policy Project  
A complete demonstration of **USB, Bluetooth, CD-ROM blocking**, along with **Authorized USB exception handling**, implemented and tested in **Bitdefender GravityZone**.

---

## 📁 **Project Overview**
This project showcases:
- Full Device Control Policy creation  
- Blocking unauthorized USB & external storage  
- Blocking Bluetooth, CD-ROM  
- Adding exceptions for Authorized USB devices  
- Log verification (Allowed / Blocked events)  
- Applying policy to endpoints  

---
## 📸 Screenshots (Step-by-Step)

### 1️⃣ Policy Creation
![Policy Creation](Screenshots/1.%20Policy%20Creation.png)

---

### 2️⃣ Device Control Module ON
![Device Control Module ON](Screenshots/2.%20Device%20Control%20Module%20ON.PNG)

---

### 3️⃣ External Storage Rule – Block All
![External Storage Rule](Screenshots/3.%20External%20Storage%20Rule%20(BLOCK).png)

---

### 4️⃣ Bluetooth Blocking Rule
![Bluetooth Blocking Rule](Screenshots/4.%20Bluetooth%20Rule%20(BLOCK).png)

---

### 5️⃣ CD-ROM Drive Blocking Rule
![CDROM Blocking Rule](Screenshots/5.%20CDROM%20BLOCK%20Rule.png)

---

### 6️⃣ Exclusions Menu (Before Adding)
![Exclusions Menu](Screenshots/6.%20Exclusions%20Menu%20(Empty%20State).png)

---

### 7️⃣ Add Exclusion Window – Device ID Selected
![Add Exclusion Window](Screenshots/7.%20Add%20Exclusion%20Window%20(Device%20ID%20selected).png)

---

### 8️⃣ Authorized USB Highlighted
![Authorized USB](Screenshots/8.%20Authorized%20USB%20Highlighted%20+%20Description%20Filled.png)

---

### 9️⃣ Exclusion Added Successfully
![Exclusion Added](Screenshots/9.%20Exclusion%20Added%20(After%20Saving).png)

---

### 🔟 USB Allowed Pop-Up
![USB Allowed Pop-Up](Screenshots/10.%20USB%20Allowed%20Pop-Up.png)

---

### 1️⃣1️⃣ Allowed Event in Logs
![USB Allowed Event](Screenshots/11.%20USB%20Allowed%20Event%20(Authorized%20USB).png)

---

### 1️⃣2️⃣ Unauthorized USB Block Pop-Up
![USB Block Pop-Up](Screenshots/12.%20USB%20Block%20Pop-Up.png)

---

### 1️⃣3️⃣ Blocked USB Event in Logs
![USB Block Event](Screenshots/13.%20USB%20Block%20Event%20in%20Logs%20(Unauthorized%20USB).png)

---

### 1️⃣4️⃣ Policy Applied to Endpoint
![Policy Applied](Screenshots/14.%20Policy%20Applied%20to%20Endpoint.png)



# 🚀 **Conclusion**
This project demonstrates:
- Real-world Enterprise Endpoint Security  
- Fine-grained Device Control  
- Policy enforcement  
- Logging & Threat visibility  
- Exception handling for business-approved devices  

This is a **complete hands-on EDR/Device Control project** suitable for SOC, MDR, Security Engineering & IT Security roles.

---

# ⭐ **Author**
**Rahul Kumar**  
Security Analyst (Aspiring)  


## 📂 Project Structure

```text
Bitdefender-Device-Control-Project/
├── Screenshots/
├── Test-Cases/
└── README.md





