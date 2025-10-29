# Laptop_Request
NM project - ServiceNow Laptop Request Automation
# 💻 Laptop Request Catalog Item
### ServiceNow Laptop Request Automation

---

## 👥 Team Members
- **JAYAKIRUBA V** (Team Leader)  
- **SRINITHI K.S**  
- **SRINITHI R**  
- **KAVIPRIYA P**

---

## 📋 Overview
This project automates the **laptop request process** in ServiceNow by creating a **dynamic Service Catalog item**.  
It replaces manual, time-consuming workflows with an interactive, automated form that improves efficiency and accuracy.

---

## 🎯 Objectives
- Build a Service Catalog item for laptop requests  
- Add dynamic form logic using **Catalog UI Policy**  
- Include a **Reset Form** button via **UI Action**  
- Package configurations into an **Update Set**

---

## ⚙️ Implementation
- **Catalog Item:** *Laptop Request* under *Hardware* category  
- **UI Policy:** Shows *accessories_details* only when *additional_accessories = true*  
- **UI Action:** Reset form fields  
  ```javascript
  function resetForm() {
    g_form.clearForm();
    alert("The form has been reset.");
  }

