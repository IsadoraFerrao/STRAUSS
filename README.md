# ✈️ ReSilienT aiR taxis architectUre for Smart cities (STRAUSS) ✈️

  STRAUSS is a resilient, robust, and fault-tolerant architecture for eVTOLs (and UAVs) that operate in adverse, intentional, or unintentional conditions. The main objective of STRAUSS is to propose a robust and fault-tolerant system for air taxis (or UAVs) that can adapt their planned mission dynamically, sharing information with other aircraft. The main components have different functionalities, namely:
  

  🔴 Detection
  
  🔴 Decision-making
  
  🔴 Resilience
  
  🔴 Security
  
  🔴 Safety

# ⚙️ General functioning of the STRAUSS

The aircraft will start the mission usually, continuously checking whether there is a problem (in real-time). If the detection module identifies no problem, the system continues the mission until all necessary objectives are completed. If the detection module identifies an anomaly, it will forward it to the next one. In this phase, the anomaly will be categorized as a safety or security problem to facilitate the decision-making process in the assertiveness of the solution. After being defined by the decision-making module, which is the most appropriate action based on its techniques, it forwards the solution to the resilience module. Resilience will detect which action is indicated to be taken and will perform it, which may be a safety or security restoration action or both measures. Finally, these processes repeat until all mission objectives are successfully completed.

<hr></hr>

# 🛡️ Detection Module

This project investigates the use of machine learning to detect two main scenarios: if the plane is crashing or a network attack is happening. The scenario of the plane crashing was determined because it is known to be the most severe case that an aircraft can suffer, leading to partial or total loss of the vehicle and fatal injuries in human lives.

🟥 branch Detection Scenario 01 - faults  ✔️

🟥 branch Detection Scenario 02 - failures  ✔️

🟥 branch Detection Scenario 03 - Validation using the MRS UAV System
