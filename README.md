# 🥤 Automated Bottle Separation System

## 📌 Project Overview
The **Automated Bottle Separation System** is designed to automatically identify and sort bottles into **metal, plastic, and glass** categories.  
This project is implemented using the **NI USB-6001 DAQ card** with **LabVIEW**, eliminating the need for an external microcontroller.  
Bottle redirection is achieved with a **DC motor-driven linear actuator**.

---

## ⚙️ Key Features
- 🔍 **Metal Detection** using an induction proximity sensor  
- ⚖️ **Weight Measurement** with a load cell  
- 🔄 **Bottle Sorting** using a DC motor + linear actuator  
- 📡 **Fill-Level Detection** with a Laser–LDR sensor  
- 📧 **Automated Email Alerts** via LabVIEW when bins are full  

---

## 🛠️ Components Used
- **NI USB-6001 Multifunction I/O Card** (14-bit, 20 kS/s, 32-bit counter)  
- Metal Induction Proximity Sensor  
- Load Cell + Signal Conditioning Circuit  
- **DC Motor with Linear Actuator**  
- Laser Diode + LDR  
- Laptop with **LabVIEW** + **NI-DAQmx drivers**  

---

## 🔄 System Workflow
1. Bottle enters the system.  
2. **Proximity sensor** detects if it is metallic.  
3. If not metal → **Load cell** measures weight to distinguish glass from plastic.  
4. **NI USB-6001** processes inputs and controls the **DC motor with linear actuator** for bin redirection.  
5. **Laser–LDR sensor** monitors bin fill levels.  
6. **LabVIEW** generates **email alerts** when bins are nearly full.  

---

