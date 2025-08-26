# 📊 Daikibo Factory Machine Downtime Analysis

This project analyzes telemetry data from Daikibo’s 4 factories to identify:
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
