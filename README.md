# Practical-no.5

### **Aim of the Experiment**  
To design and model the **Data Flow Diagram (DFD)** and **Control Flow Diagram (CFD)** for an **Ayurvedic Management System**, identifying data movement and control flow within the system.

### **Introduction**  
An **Ayurvedic Management System** is a healthcare system that provides users with access to Ayurvedic treatments, consultations, medicines, and wellness programs. The system involves multiple entities, including patients, doctors, pharmacists, and administrators, ensuring seamless interaction among them.  
Data Flow Diagrams (DFDs) help in understanding how data moves between these entities, while Control Flow Diagrams (CFDs) illustrate the logical flow of processes within the system.

### **Objectives**  
After completing this experiment, you will be able to:  
- Identify **external entities** and **functionalities** in the Ayurvedic Management System.  
- Understand the **flow of data** between different modules.  
- Represent the **data flow and process interactions** using Data Flow Diagrams.  

### **Theory**  

#### **1. Data Flow Diagram (DFD)**  
A **DFD** is a graphical representation of the flow of data in a system. It shows how data enters, is processed, stored, and leaves the system.  

##### **DFD Levels in the Ayurvedic Management System**  
- **Level 0 (Context Diagram):**  
  - Shows the **high-level** interaction between the system and external entities like **patients, doctors, pharmacy, and admin**.  
- **Level 1 DFD:**  
  - Breaks the system into modules such as **User Registration, Appointment Booking, Treatment Recommendations, and Medicine Purchase**.  
- **Level 2 DFD:**  
  - Further details each process, such as **patient prescription generation, payment processing, and Ayurvedic doctor consultations**.

#### **2. Graphical Notations for Data Flow Diagram**  
- **External Entity:** Represents actors like **patients, doctors, and pharmacy**.  
- **Process:** Represents tasks such as **booking an appointment or processing payments**.  
- **Data Store:** Represents stored data like **patient records, Ayurvedic treatments, and medicine inventory**.  
- **Data Flow:** Represents the flow of data between processes and entities.  

#### **3. Explanation of Symbols Used in DFD**  
- **Circle (○):** Represents a process (e.g., "Consultation Scheduling").  
- **Rectangle:** Represents external entities (e.g., "Patient" or "Pharmacy").  
- **Arrows (→):** Represent data movement (e.g., "Patient Data" → "Doctor").  
- **Open-ended rectangle:** Represents a data store (e.g., "Patient Records Database").  

#### **4. Context Diagram & Leveling DFD**  
- The **Context Diagram** provides a high-level overview of the system, showing how entities interact.  
- **Leveling DFDs** helps in refining processes at different abstraction levels to show detailed interactions.  

### **Case Study**  
Consider a **patient booking an Ayurvedic consultation**:  
1. The **patient** enters the system and requests an appointment.  
2. The **doctor reviews** the request and schedules a consultation.  
3. The **system stores patient details** and recommended treatments.  
4. If medicines are required, the **pharmacy module** processes the order.  
5. Payments are processed, and **confirmation is sent to the patient**.  

### **Simulation**  
A **prototype DFD model** can be created using tools like Microsoft Visio, Lucidchart, or draw.io to visualize the **data and control flow** of the Ayurvedic Management System.

---

![image](https://github.com/user-attachments/assets/cdac7871-2ded-441a-92ac-9cf746e3d9d6)
