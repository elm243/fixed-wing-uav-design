\# Mission Definition



\*\*Project Name:\*\* High Altitude Fixed-Wing UAV

\*\*Document:\*\* Mission Definition

\*\*Version:\*\* 0.1

\*\*Status:\*\* Preliminary

\*\*Date:\*\* 2026-09-01



\## Revision History



| Version | Date | Description |

| --- | --- | --- |

| 0.1 | 2026-09-01 | Initial project definition |

| 0.2 | 2026-09-08 | Continued initial definition |

| 0.3 | 2026-09-09 | Continued project definition |



\## 1. Project Overview



This project focuses on the design and development of a fixed-wing, electric unmanned aerial vehicle (UAV) that is capable of carrying modular payloads to a high altitude. The UAV should be able to reach and maintain its target operational altitude for a period of time and return safely. The design should also include provisions for future waypoint-based and autonomous flight capabilities.



The UAV design should focus on efficient high-altitude operation and the ability to reliably reach the target operational altitude. With that, there should be an emphasis on the payload being modular and standardized for convenient interchangeability. This modular payload system is intended to support a variety of missions, including multiple forms of photography and videography and scientific measurement equipment.



The UAV will first be developed solely in simulation and based on the results of simulation and preliminary analysis may be developed into a physical prototype. Physical testing will be pursued where practical and legally permitted. Where portions of the intended operating envelope cannot be physically tested, digital modeling and simulation will be used to evaluate aircraft performance.



The design will not be optimized for all weather conditions and instead will be used in favorable, non-severe weather conditions. The design will also not attempt to optimize speed as maximum speed is not a primary performance objective and does not directly support the aircraft's main goals of altitude capability, endurance, payload versatility, and recoverability.



\## 2. Purpose



This UAV should demonstrate that a relatively low-cost and simple platform can provide a useful means of conducting research, collecting data, and carrying interchangeable experimental payloads. The project will also provide a practical way to study the tradeoffs between altitude capability, endurance, payload mass, and system complexity. The design is intended to balance accessibility with capability so that the platform remains realistic for small-scale research, educational use, or independent experimentation. This project also intends to determine whether these capabilities can be maintained while operating at significantly higher altitude.



\## 3. Mission Concept



Initially the mission starts with connecting the desired payload module. Then the UAV will take off and climb to operational altitude. From there the UAV will loiter at the desired operational altitude to complete the primary mission objective related to whichever payload module is installed. The UAV will descend after the objective has been completed and land safely at the designated recovery location where the payload can be removed and recovered. Future development can involve automation of certain phases of the mission, including navigation, altitude control, loitering, and recovery procedures.



\## 4. Primary Capabilities



\### 4.1 High-Altitude Operations



The UAV is intended to be able to climb from near sea level to a target operational altitude of 15,000 ft MSL and maintain controlled and effective operation at that altitude. 



\### 4.2 Endurance and Loiter



The UAV should be capable of completing its primary mission objective while maintaining the target operational altitude. The aircraft should also be capable of loitering at or near the target altitude for approximately 30 minutes, with a nominal total mission endurance of approximately 90 minutes.



\### 4.3 Modular Payload Capacity



The payload system should have a convenient modular design with a quick installation and removal process. The mechanical interface should be standardized across payload modules to allow different payload types to be interchanged without modification of the airframe. The initial design objective is a nominal payload mass of approximately 0.75 kg, with a maximum design payload of approximately 1.0 kg.



\### 4.4 Flight Control and Future Autonomy



Initially the UAV will be reliant on manual control inputs, but the aircraft will include provisions for the future integration of a waypoint navigation system and potentially more advanced autonomous flight capabilities.



\### 4.5 Recovery and Reusability



The aircraft and installed payload are intended to be recovered fully intact and operational at the end of each mission, allowing the aircraft and payload system to be reused for subsequent missions.



\### 4.6 Operating Conditions



The UAV will be designed primarily for favorable, non-severe weather conditions and will be designed to support both day and night operations.



\## 5. Design Priorities



The design priorities establish which characteristics should receive preference when engineering tradeoffs are required. The current priorities are listed in approximate order of importance:



1. Safe and stable flight
2. Recovery and reusability
3. High-altitude capability
4. Endurance and loiter capability
5. Modular payload capability
6. Payload capacity
7. Future autonomous integration
8. Simplicity and reasonable cost
9. Maximum speed



These priorities may be revised as preliminary analysis identifies major feasibility constraints or conflicts between design objectives.



\## 6. Project Scope



The project scope defines the areas that will be included in the design and analysis process, as well as areas that are intentionally excluded from the initial project.



\### 6.1 In Scope



\- Fixed-wing electric aircraft configuration

\- High-altitude performance analysis

\- Aerodynamic design and analysis

\- Propulsion and energy-system sizing

\- Endurance and loiter analysis

\- Modular payload interface design

\- Payload mass and center-of-gravity integration

\- Stability and control analysis

\- Manual flight-control architecture

\- Provisions for future autonomous systems

\- CAD development

\- Digital simulation and performance modeling

\- Potential physical prototype development

\- Ground and flight testing where practical and legally permitted



\### 6.2 Out of Scope



\- All-weather operation

\- Flight in severe weather or icing conditions

\- Optimization for maximum speed

\- Full autonomous operation in the initial design

\- Autonomous takeoff and landing in the initial phase

\- Development of custom sensors for every payload

\- Certification as a commercial or production aircraft

\- Human transportation

\- Beyond-line-of-sight operational capability as an initial objective

\- Physical demonstration of the complete 15,000 ft design envelope if legal or practical restrictions prevent it



\## 7. Development Approach



The project will follow a step-by-step engineering process, beginning with defining the project goals and requirements. From there, the UAV will be sized, analyzed, modeled, and tested through simulation before any physical prototype is considered. Results from each stage may lead to changes in earlier decisions, allowing the design to improve as more information becomes available.



\### 7.1 Project and Mission Definition



Define the purpose, mission concept, primary capabilities, design priorities, project scope, and overall development objectives of the UAV.



\### 7.2 Requirements Development



Translate the project objectives and desired capabilities into measurable engineering requirements and constraints. Requirements may be revised as preliminary analysis provides a better understanding of what is technically achievable.



\### 7.3 Preliminary Aircraft Sizing



Develop initial estimates for aircraft mass, wingspan, wing area, wing loading, payload capacity, propulsion requirements, battery capacity, and other major design parameters. Preliminary sizing will be used to establish a feasible starting configuration for further analysis.



\### 7.4 Aerodynamic, Performance, and Stability Analysis



Evaluate the proposed aircraft configuration with respect to aerodynamic efficiency, lift and drag characteristics, stability and control, climb performance, endurance, loiter capability, and operation throughout the intended altitude range.



\### 7.5 Propulsion and Energy Analysis



Evaluate the electric propulsion and energy-storage system required to support the mission profile. This analysis will consider climb energy, cruise and loiter power requirements, high-altitude propulsion performance, battery capacity, energy reserves, and the effects of payload mass on mission endurance.



\### 7.6 Digital Design and Simulation



Develop the aircraft geometry and systems in CAD and use appropriate computational and simulation tools to evaluate aerodynamic, structural, propulsion, flight-performance, and other relevant characteristics. Simulation results will be compared with analytical calculations and established reference data where possible.



\### 7.7 Design Iteration and Refinement



Revise the aircraft configuration as necessary based on analytical results, simulation findings, trade studies, requirement conflicts, and identified design limitations. Iteration may require returning to previous development stages and updating assumptions, requirements, or design parameters.



\### 7.8 Physical Prototype Development



If supported by the results of the digital design and analysis process, develop a physical prototype for component testing, ground testing, and flight testing where practical and legally permitted.



\### 7.9 Verification and Validation



Evaluate whether the final design satisfies the established project requirements. Physical test results, where available, will be compared with analytical and simulation predictions. Where the complete design envelope cannot be physically tested, analytical and simulation-based evidence will be used to evaluate expected performance, with the limitations of those methods clearly documented.



\## 8. Project Success



The project will be considered successful if it produces a technically credible UAV design that demonstrates the feasibility of the primary project goals through analysis, simulation, and, where practical, physical testing.



Project success will include:



\- Development of a stable and recoverable fixed-wing UAV design.

\- Demonstration that the aircraft can reasonably achieve the intended high-altitude mission profile.

\- Demonstration of useful endurance and loiter capability at the target operational altitude.

\- Development of a standardized modular payload system capable of supporting multiple payload types.

\- Demonstration that the aircraft can carry a useful payload without compromising its primary mission objectives.

\- Development of a design that can support future integration of autonomous or waypoint-based flight systems.

\- Completion of sufficient analysis and simulation to justify major design decisions.

\- Clear documentation of design tradeoffs, limitations, and areas requiring further development.

\- Development of a physical prototype if the results of the digital design process support doing so.



