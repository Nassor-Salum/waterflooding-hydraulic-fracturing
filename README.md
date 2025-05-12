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

🖼️ **Screenshots**

<p align="center">
  <img src="https://raw.githubusercontent.com/Nassor-Salum/waterflooding-hydraulic-fracturing/main/saturation_map.png" alt="Saturation Map" width="600"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Nassor-Salum/waterflooding-hydraulic-fracturing/main/fracture_effect.png" alt="Fracture Impact on Production" width="600"/>
</p>

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

1. Open `PROJECT.DATA` in **ECLIPSE Black Oil Simulator**
2. Run simulation and monitor `SUMMARY` and `UNRST` files
3. Use Petrel or Office tools to visualize results (optional)
4. Check charts for oil rate, water cut, and pressure behavior

---

🧠 **What I Learned**

- The integration of **fracturing with waterflooding** can drastically improve recovery in low-permeability zones
- Proper injector placement and schedule optimization are critical to efficient sweep
- Simulation is a powerful way to test EOR strategies before field application

---

📬 **Contact**

**Author:** Nassor  


