# Elisa-3 Autonomous Navigation & Control

## Project Overview
An embedded systems course project focused on autonomous navigation using the **Elisa-3** micro-robot. The project involved implementing boundary detection, dynamic obstacle avoidance, PID wall-distance control, and state-machine-based corridor navigation.

### Tech Stack
*   **Languages:** C / C++
*   **Platform:** Elisa-3 Micro-robot
*   **Sensors:** Ground sensors, Proximity sensors
*   **Control:** PWM motor control, PID algorithms, State machines

---

## My Core Contributions
*   **Autonomous Navigation:** Independently programmed boundary detection and dynamic obstacle avoidance using ground/proximity sensors, PWM motor control, and randomized turning algorithms.
*   **PID Wall-Distance Control:** Analyzed sensor measurement errors and tuned control parameters to maintain a stable following distance from the wall.
*   **State-Machine Navigation:** Co-developed line-following and corridor navigation logic using sensor inputs, route counters, and state flags to track the robot's status.

---

## Engineering Troubleshooting
*Real engineering is about solving unexpected problems.*

*   **Sensor Measurement Inaccuracies:** Attempted to fit proximity sensor readings to actual distances, but the fit was distorted over certain ranges. Due to limited lab time, we optimized the system by using raw sensor readings at target distances, which achieved a reasonably steady wall-following behavior.
*   **Finish-Point Reliability:** The robot could enter the corridor but did not stop at the designated endpoint reliably. We analyzed the limitations of the stopping condition in our final report, documenting it as a basis for future sensor-fusion improvements.

---

## Results & Achievements
*   Successfully met the first challenge's requirements (boundary detection and obstacle avoidance) in laboratory testing.
*   Documented the system's control logic and physical constraints, providing a solid foundation for future real-time embedded control projects.

---

## Acknowledgements
*   **Course Instructors:** [填写老师名字] at [ZJSU], for providing the hardware platform and lab testing environment.
*   **Project Teammates:** [填写队友名字], for their collaboration in testing and debugging.

---
*Maintained by FishInCode.*
