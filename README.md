# 🛢️ Waterflooding & Hydraulic Fracturing Simulation in Eclipse

📌 **Overview**  
This project focuses on simulating enhanced oil recovery (EOR) using **waterflooding** and **hydraulic fracturing** techniques in a synthetic reservoir model. Implemented using Schlumberger's **ECLIPSE** simulator, the study evaluates how water injection and fracture stimulation influence oil production, pressure behavior, and sweep efficiency under a **five-spot injection pattern**.

---

🎯 **Objectives**

- Simulate waterflooding to displace oil toward producer wells
- Model the effect of hydraulic fracturing on well performance
- Analyze saturation changes, flow patterns, and water breakthrough
- Assess improved oil recovery under combined EOR techniques

---

🛠️ **Tools Used**

- **ECLIPSE (Black Oil Simulator)** – For dynamic reservoir simulation  
- **Petrel** – For visualization of fractures and saturation maps  
- **Python & Excel** – For data extraction and analysis of simulation output

---

🔬 **Methodology**

- Defined reservoir geometry, fluid properties, and rock parameters
- Designed a **five-spot water injection pattern** with one central producer and four surrounding injectors
- Applied **hydraulic fracturing** to the main producer (P1) by modifying well transmissibility and effective grid dimensions
- Scheduled injection and production periods to observe dynamic fluid movement
- Visualized saturation fronts and production performance using output results

---

✅ **Key Outcomes**

- Water injection effectively pushed oil toward the producer well in a radial pattern
- Hydraulic fracturing significantly enhanced oil flow by reducing pressure drop near the wellbore
- Observed earlier water breakthrough in fractured wells, indicating higher connectivity
- Improved cumulative oil recovery compared to non-fractured waterflooding scenario

---

🖼️ **Results**

  **Saturation Map**

  
- Five Spot Pattern
  
![Screenshot 1](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/Screenshot%202025-05-05%20225625.png?raw=true)


- Water Injection Effect 

  
![Screenshot 2](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/Screenshot%202025-05-05%20225824.png?raw=true)


  - Oil Recovery Factor Increased to 47% (Water Injection Effect)


    ![Screenshot](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/Screenshot%202025-05-06%20023633.png?raw=true)
  
  
   **Fracture Impact on Production**

   - Fractured Horizontal Well


 ![Screenshot 4](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/Screenshot%202025-05-06%20095224.png?raw=true)
     


   - Late Water Breakthrough For Five-Sport Pattern
    

      ![Screenshot 6](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/Screenshot%202025-05-06%20174736.png?raw=true)


   - Increased Oil Recovery Factor Incresed From 47% to 56% Due (Fracturing Effect)
      

       ![Screenshot 5](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/Screenshot%202025-05-06%20141950.png?raw=true)
---

📊 **Simulation Highlights**

| Feature                | Description                               |
|------------------------|-------------------------------------------|
| Pattern Type           | Five-Spot Injection Pattern               |
| Enhanced Recovery      | Waterflooding + Hydraulic Fracturing      |
| Target Well            | P1 (Fractured Producer)                   |
| Observation Period     | 2000–2025                                 |
| Output Monitored       | Oil Rate, Water Cut, Saturation Changes   |

---

📂 **How to Use**

1. [Download `PROJECT.DATA`](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/SNARK.DATA)
2. The simulation requires additional input files included in the `.DATA` file using `INCLUDE` statements.
You can download all required files here:
 [Download ECLIPSE_includes.zip](https://github.com/Nassor-Salum/waterflooding-hydraulic-fracturing/blob/main/Includes.rar)

3. Open it in **ECLIPSE Black Oil Simulator**
4. Run simulation and monitor `SUMMARY` and `UNRST` files
5. Use Petrel or Office tools to visualize results (optional)
6. Check charts for oil rate, water cut, and pressure behavior

---

🧠 **What I Learned**

- The integration of **fracturing with waterflooding** can drastically improve recovery in low-permeability zones
- Proper injector placement and schedule optimization are critical to efficient sweep
- Simulation is a powerful way to test EOR strategies before field application

---
## **Author**
Nassor Salum



