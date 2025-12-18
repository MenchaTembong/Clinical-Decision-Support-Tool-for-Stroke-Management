# 🚑 CDSS for Prehospital Management of Acute Ischemic Stroke  
### *Stroke Kinesis*

---

## 📘 Description

**StrokeKinesis** is a comprehensive clinical decision support (CDS) platform designed to transform **prehospital acute ischemic stroke (AIS) management** by providing real-time triage support, intelligent destination routing, and seamless EMS–hospital integration.

---

## ❗ The Problem

**Current-State Stroke Care Pathway (BPMN):**  

Despite major advances in acute stroke treatment, **prehospital stroke care remains fragmented and inconsistent**, creating preventable delays during the most time-critical phase of care.

#### 🚨 Key Challenges

- **Inconsistent Stroke Triage**  
  EMS teams apply stroke screening tools (FAST, BE-FAST, LAMS) variably, leading to inconsistent severity assessment and missed large vessel occlusions.

- **Suboptimal Destination Decisions**  
  Patients are frequently transported to the *nearest* hospital rather than the *most appropriate* stroke center, resulting in avoidable inter-facility transfers and treatment delays.

- **Limited Pre-Arrival Communication**  
  Hospitals often receive minimal or late notification, leaving stroke teams unprepared at patient arrival and increasing door-to-needle times.

- **Duplicate Documentation & Data Loss**  
  Prehospital assessments are manually repeated in the emergency department, increasing cognitive load, documentation errors, and workflow inefficiencies.

- **Lack of Real-Time Clinical Decision Support**  
  Paramedics must make high-stakes routing and treatment decisions under time pressure without integrated, evidence-based decision support.

- **Geographic Inequities**  
  Rural and remote regions lack standardized stroke protocols, real-time routing support, and consistent access to telestroke services.


These gaps result in delayed escalation of complications and weakened post-acute continuity of care.

<p align="center">
  <img src="https://i.imgur.com/kDCPrpV.png" width="85%" alt="Current-state stroke care BPMN"/>
</p>

---


## ✅ The Solution

### Future-State Prehospital Stroke Management with StrokeKinesis

- **Standardized, Guided Stroke Assessment**  
  StrokeKinesis embeds validated stroke screening tools (**BE-FAST and LAMS**) into a guided, step-by-step workflow, ensuring consistent and accurate stroke severity assessment across all EMS providers.

- **Real-Time Stroke Severity Scoring**  
  Patient inputs and clinical findings are processed instantly to generate objective stroke severity scores, supporting rapid and confident decision-making in the field.

- **Intelligent Destination Routing**  
  An AI-assisted routing engine recommends the most appropriate stroke center

- **Automated Hospital Pre-Notification**  
  StrokeKinesis transmits structured clinical data to the receiving hospital before arrival, enabling early **stroke team activation** and eliminating redundant assessments.

- **Seamless EMS–Hospital Handover**  
  Prehospital data flows directly into the hospital electronic health record (EHR), ensuring continuity of information and reducing documentation errors.

- **Offline-First, Field-Ready Design**  
  The system is optimized for ambulance use, with support for intermittent connectivity, large touch targets, and rapid interaction in high-stress environments.


<p align="center">
  <img src="https://i.imgur.com/10YtNAZ.png" width="85%" alt="Future-state BPMN with Stroke Kinesis"/>
</p>

---

## 🛠️ Key Features

- Guided **BE-FAST** and **LAMS** stroke assessments  
- Real-time stroke severity scoring  
- AI-assisted destination routing  
- Automated hospital pre-notification  
- EMS–hospital data continuity (EHR-ready)  
- Offline-first, ambulance-optimized design  


---

## 🧪 How It Works

- EMS opens StrokeKinesis at scene arrival  
- Guided BE-FAST/LAMS assessment completed  
- Vital signs and last-known-well captured  
- System calculates stroke severity  
- Optimal stroke center recommended  
- Hospital pre-notified before arrival  

---

## 🧩 Model & Architecture

- Workflow-driven digital health prototype  
- BPMN-based modeling of current and future stroke pathways  
- Emphasis on post-acute care continuity and decision support  

---

---

## 🚀 Planned Upgrades

- AI-driven rehabilitation personalization  
- Predictive risk modeling  
- Integration with EHR systems  
- Expanded clinician dashboards  

---

## ⚙️ Tech Stack

- **PowerShell** – Extraction of failed RDP logon events from Windows Event Viewer  
- **JavaScript** – Command-line interface prototyping  
- **BPMN** – Clinical workflow modeling  

---

## 🧰 Utilities Used

- Visual Studio Code  
- Microsoft Visio  
- Lucidchart  

---

## 🖼️ Prototype Screenshots


### 🏠 Landing Page
<p align="center">
  <img src="https://i.imgur.com/l80hKIu.png" width="85%" alt="Stroke Kinesis Landing Page"/>
</p>

---

### 🧠 BE-FAST Assessment – Step 1
<p align="center">
  <img src="https://i.imgur.com/SVIXaH6.png" width="85%" alt="BE-FAST Assessment Step 1"/>
</p>

---

### 🧠 BE-FAST Assessment – Step 2
<p align="center">
  <img src="https://i.imgur.com/NJcEEHU.png" width="85%" alt="BE-FAST Assessment Step 2"/>
</p>

---

### 🏥 Destination Selection
<p align="center">
  <img src="https://i.imgur.com/g7KUFKb.png" width="85%" alt="Hospital Destination Selection"/>
</p>

---

### 📡 Hospital Pre-Notification
<p align="center">
  <img src="https://i.imgur.com/HzyGigO.png" width="85%" alt="Hospital Pre-Notification Screen"/>
</p>

### JavaScript CLI (VS Code)
<p align="center">
  <img src="https://i.imgur.com/9XZHnlW.png" width="85%" alt="JavaScript CLI in VS Code"/>
</p>

---

## 👤 Author

**Mencha Tembong**  
Health Informatics Student • Data Scientist enthusiast • Digital Health Advocate  


---

## ⚠️ Disclaimer

This tool is intended for **educational and decision-support purposes only**.  
It does **not replace professional medical diagnosis, clinical judgment, or treatment**.
