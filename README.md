## **Project Description**

**Project Title:**
**Design and Analysis of a Hybrid Passive-Active Battery Thermal Management System (BTMS) for Electric Vehicles using Phase Change Materials (PCM) and Thermally Actuated Valves**

**Domain:** Mechanical Engineering / Thermal Engineering / EV Technology
**Semester:** 6th

---

### **1. Introduction**

Electric Vehicles (EVs) rely heavily on Lithium-ion battery packs, which are highly sensitive to temperature. The optimal operating temperature for these batteries is typically between **15°C and 35°C**, with a safety upper limit of **60°C**. Exceeding this limit leads to capacity fading, reduced lifecycle, and potential safety hazards like thermal runaway. In tropical climates like India, maintaining this temperature range is a significant engineering challenge due to high ambient heat.

### **2. Problem Statement**

* **High Ambient Temperature Constraint:** In Indian summers, the ambient temperature () often reaches **45°C–50°C**.
* **Inefficient Heat Transfer:** The maximum safe temperature for the battery () is approximately **60°C**. This results in a very small temperature difference () between the battery and the cooling air.
* **Failure of Passive Air Cooling:** Conventional air cooling relies on a high  to remove heat. With  at 50°C, simple air cooling is insufficient to keep the battery below 60°C, necessitating a more advanced hybrid solution.

### **3. Proposed Solution (The Innovation)**

To address the low  issue, we propose a **Hybrid Cooling System** that integrates two subsystems:

1. **Passive Stage (PCM Matrix):** The battery cells will be embedded in a **Phase Change Material (PCM)**, such as Paraffin Wax. This material will absorb heat as "Latent Heat" during its melting phase (solid to liquid) without a rise in temperature, effectively clamping the battery temperature at the PCM's melting point (e.g., 45°C).
2. **Active Stage (Thermally Actuated Valve):** To prevent overheating once the PCM is fully melted, we will design a **mechanical relief valve system**. This valve will be actuated by a thermal expansion element (Wax Motor or Bimetallic Strip) that physically expands at critical temperatures (e.g., >55°C), opening a flap to allow emergency airflow or pressure release.

### **4. Project Objectives**

1. To select and characterize a suitable PCM with a melting point range of **40°C–48°C** for the Indian climate.
2. To design a **mechanical actuation mechanism** (linkage/valve) that operates autonomously based on thermal expansion, removing the need for electronic sensors or battery power.
3. To model and simulate the battery pack thermal performance using **ANSYS / CFD** software.
4. To fabricate a working prototype (using acrylic, dummy cells, and PCM) to demonstrate the phase change phenomenon and the mechanical valve operation.

### **5. Methodology (Work Plan)**

* **Step 1: Literature Review:** Study existing BTMS, properties of Paraffin wax, and thermal expansion coefficients of actuator materials.
* **Step 2: Material Selection:** Identify the specific commercial grade of PCM (e.g., RT-42) and thermal conductivity enhancers (Aluminum foam/Graphite).
* **Step 3: CAD Modeling:** Design the 3D model of the battery module and the **thermal valve assembly** using SolidWorks/CATIA.
* **Step 4: Simulation:** Perform transient thermal analysis in ANSYS to compare:
* Battery with No Cooling.
* Battery with PCM only.
* Battery with Hybrid PCM + Valve System.


* **Step 5: Fabrication:** Build a physical prototype using an acrylic casing to visualize the PCM melting process and the movement of the mechanical valve.

### **6. Expected Outcomes**

* A validated design for an EV battery pack that stays within the safe operating range (<60°C) even when outside temperatures are 50°C.
* A fully mechanical, fail-safe cooling trigger that enhances battery safety without consuming battery power.

### **7. Hardware & Software Requirements**

* **Software:** SolidWorks (Design), ANSYS Fluent (Simulation).
* **Hardware:** Li-ion 18650 Cells (Dummy/Dead cells for safety), Paraffin Wax, Graphite Powder, Acrylic Sheets, Thermal Actuator (Wax Motor/Thermostat).

---
