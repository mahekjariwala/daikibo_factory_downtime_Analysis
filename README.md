# 📊 Daikibo Factory Machine Downtime Analysis

This project analyzes telemetry data from **Daikibo’s 4 factories** to identify:
1. In which location did machines break the most?
2. Which machines broke most often in that location?

The analysis was performed using Tableau, based on a unified JSON telemetry dataset covering May 2021.  

## 🏭 Dataset Overview
- **Factories**:  
  - Daikibo Factory Meiyo (Tokyo, Japan)  
  - Daikibo Factory Seiko (Osaka, Japan)  
  - Daikibo Berlin (Germany)  
  - Daikibo Shenzhen (China)  

- **Devices (9 types)**:  
  `AirWrench, CNC, ConveyorBelt, Furnace, HeavyDutyDrill, LaserCutter, LaserWelder, MetalPress, SpotWelder`

- **Granularity**: Each machine sends a message every **10 minutes**.  
- **Period**: **May 2021 (1 month of data)**.

- ## 📈 Dashboard Highlights
### 1. Downtime per Factory
Shows total downtime (`Unhealthy hours`) for each factory.  
👉 Helps identify which **location had the highest breakdowns**.  

### 2. Downtime per Device
Shows downtime by machine type in the **most affected factory**.  
👉 Helps identify the **weakest devices**.

<img width="1920" height="1080" alt="Screenshot (342)" src="https://github.com/user-attachments/assets/2ec20569-3755-420b-a33c-3aada8383edb" />


# 🔍 Insights

**Factory with most breakdowns**: Osaka (Daikibo Seiko)

**Most problematic device**: Laser Welder

These insights can guide preventive maintenance and resource allocation.

 # 🛠Tools & Tech

-Tableau Public (Data visualization)

-JSON Parsing (Data ingestion & unification)

-GitHub (Project hosting & sharing)



