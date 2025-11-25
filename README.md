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



Screenshots are in the **Screenshots/** folder.  
Test cases are in **Test-Cases/device_control_test_cases.md**.

---

# 🔵 Step-by-Step (With Screenshots)

### **STEP 1 – Device Control Module Enabled**
![Device Control ON](Screenshots/1. Device Control Module ON.PNG)

### **STEP 2 – Device Classes Overview**
![Policy Creation](Screenshots/01 – policy-creation.png)

---

## 🔒 Device Blocking Rules

### **STEP 3 – USB / External Storage Blocked**
![USB Block Rule](Screenshots/3. External Storage Rule (BLOCK).png)

### **STEP 4 – Bluetooth Blocked**
![Bluetooth Block](Screenshots/4. Bluetooth Rule (BLOCK).png)

### **STEP 5 – CDROM Blocked**
![CDROM Block](Screenshots/5. CDROM  BLOCK Rule.png)

---

## 🟩 Whitelisting (Exclusions)

### **STEP 6 – Exclusion List (Empty)**
![Empty Exclusion](Screenshots/6. Exclusions Menu (Empty State).png)

### **STEP 7 – Add Exclusion (Device ID)**
![Add Exclusion](Screenshots/7. Add Exclusion Window (Device ID selected).png)

### **STEP 8 – Mark Authorized USB as Allowed**
![Authorized USB Allowed](Screenshots/8. Authorized USB Highlighted + Description Filled.png)

### **STEP 9 – Whitelist Saved**
![Whitelist Saved](Screenshots/9. Exclusion Added (After Saving).png)

---

## 🧪 Testing & Results

### **STEP 10 – Allowed USB (Pop-Up)**
![USB Allowed Popup](Screenshots/10. USB Allowed Pop-Up.png)

### **STEP 11 – Allowed USB (Threats Xplorer Log)**
![USB Allowed Log](Screenshots/11. USB Allowed Event (Authorized USB).png)

### **STEP 12 – Blocked USB (Pop-Up)**
![USB Block Popup](Screenshots/12. USB Block Pop-Up.png)

### **STEP 13 – Blocked USB (Threats Xplorer Log)**
![USB Block Log](Screenshots/13. USB Block Event in Logs (Unauthorized USB).png)

---

## 🔧 STEP 14 – Policy Applied to Endpoint
![Policy Applied](Screenshots/14. Policy Applied to Endpoint.png)

---

# 📊 Test Cases
Full test cases available here:



