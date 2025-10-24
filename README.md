# DAWA – Smart Medical Dispensing Machine (Prototype 1)**



## **1. Project Overview**

**Project Name:** Dawa
**Version:** Prototype 1
**Category:** Smart Healthcare Device
**Developer:** Ndagire Catherine, Mirembe Peace Mercy, Ainomugisha Faith, Ebong Jesse, Kobumanzi Trishia, Edgar Baluku Mukisa.
**Institution:**  Uganda Christian University

**Project Description:**
Minimed is an AI-assisted smart medicine dispensing system designed to automate and monitor the process of administering medication in environments with limited healthcare personnel — particularly **highly populated schools** and **refugee camps** in Uganda.

The prototype aims to reduce nurse workload, prevent unauthorized access to medicine, and ensure accurate dosage tracking using a combination of **hardware automation** and **AI-powered reporting**.

---

## **2. Problem Statement**

In overcrowded schools and refugee camps, nurses face challenges in dispensing medication efficiently and securely.

* Long queues form as each student waits for their dose.
* Nurses rely on **manual records**, which are time-consuming and error-prone.
* Sometimes, **students access medicine without supervision**, leading to misuse.
* Keeping track of who has taken their dose and when becomes extremely difficult.

**Problem Summary:**

> There is a lack of an efficient, secure, and intelligent medicine dispensing system that ensures dosage accuracy, reduces workload, and prevents unauthorized access.

---

## **3. Objectives**

### **Main Objective:**

To design and develop a smart prototype that automates medicine dispensing and tracks dosage using AI.

### **Specific Objectives:**

1. To automate the process of dispensing accurate doses to registered users.
2. To implement a digital identification system for secure medicine access.
3. To monitor and record dosage history automatically.
4. To use AI for generating health reports and detecting anomalies (e.g., missed doses).
5. To create a scalable design suitable for schools and refugee camps.

---

## **4. Target Users**

* **Primary Users:**

  * Students in highly populated schools.
  * Refugees in camps where medical staff are few.

* **Secondary Users:**

  * Nurses and healthcare staff managing medication.
  * NGOs and health administrators monitoring medicine use.

---

## **5. System Description**

### **5.1 Functional Overview**

Minimed Prototype 1 performs the following main functions:

1. **User Authentication:**

   * Uses a simple ID system (e.g., student ID, fingerprint, or passcode) to verify identity.
2. **Automated Dispensing:**

   * Dispenses pre-measured doses automatically to the verified user.
3. **Data Logging:**

   * Records each dispensing event (time, user ID, medicine type).
4. **AI Monitoring Module:**

   * Analyzes usage data to identify missed doses, detect irregular access, and generate summary reports.
5. **Display Interface:**

   * Shows confirmation of successful dispensing and alerts for errors or low stock.

---

## **6. System Components**

### **Hardware Components**

* **Microcontroller:** ESP32 (Wi-Fi enabled for future cloud integration)
* **Servo or Stepper Motor:** To control the dispensing mechanism.
* **Display Screen:** LCD or OLED to show messages (e.g., “Dose Complete”).
* **Keypad / RFID / Fingerprint Sensor:** For user authentication.
* **Sensors:** To monitor medicine level in storage.
* **Power Supply:** 5V DC (can use adapter or rechargeable battery).

### **Software Components**

* **Embedded Program:** Written in Arduino C/C++ for ESP32 control.
* **AI Module:** (Cloud or Local) Python-based model analyzing logs and generating reports.
* **Database:** Local storage (initially) for logs of users, doses, and timestamps.
* **Dashboard (Future):** Web or mobile interface for nurses and administrators.

---

## **7. System Workflow**

1. **Registration Phase:**

   * Nurse registers each user (student/refugee) with a unique ID and prescribed medicine schedule.

2. **Dispensing Phase:**

   * User identifies themselves using their ID or fingerprint.
   * System checks dosage schedule → if valid, the dispenser releases one dose.
   * Confirmation message appears on the screen (“Dose Complete”).

3. **Monitoring Phase:**

   * All transactions are logged (user, time, medicine type).
   * AI model reviews logs to identify missed or irregular doses.
   * Reports are sent to the nurse or administrator.

---

## **8. AI Integration**

The **AI component** of Minimed plays three major roles:

1. **Dose Tracking:** Learns each student’s medication schedule and flags inconsistencies.
2. **Predictive Analytics:** Estimates when medicine will run out and recommends restocking time.
3. **Health Insights:** Detects abnormal patterns — e.g., repeated requests for certain medicine indicating a possible outbreak (flu, malaria, etc.).

---

## **9. Prototype Design**

**Physical Design:**

* Compact rectangular enclosure (inspired by a mini vending machine).
* One front slot for medicine dispensing.
* LCD display and button panel for user interaction.
* Medicine compartment with motorized control.


## **10. Expected Outcomes**

* Reduction in nurse workload by automating repetitive tasks.
* Prevention of unauthorized medicine access.
* Creation of digital records for accountability.
* Improved dosage adherence among students.
* Foundation for AI-driven health monitoring in low-resource settings.

---

## **11. Challenges**

* Integrating secure authentication in the first prototype (due to cost).
* Ensuring accurate dispensing mechanism calibration.
* Limited data for training AI models in early stages.
* Power stability in schools and camps without constant electricity.

---

## **12. Future Improvements**

* Add solar power support for off-grid operation.
* Connect AI dashboard to cloud for remote monitoring.
* Integrate voice interface for accessibility.
* Expand to multiple medicine types and dosage sizes.
* Collaborate with Ministry of Health and NGOs for large-scale testing.

---

## **13. Conclusion**

The Minimed Prototype 1 demonstrates a practical and scalable approach to solving a real problem faced by schools and refugee camps in Uganda — the inefficiency and risk of manual medicine dispensing.

By combining **hardware automation** with **AI-driven monitoring**, the system ensures that every student receives the right medicine, at the right time, safely and efficiently.

Minimed is a step toward a smarter, safer, and more accountable healthcare environment for Uganda and beyond.


