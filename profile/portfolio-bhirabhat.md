<div align="center">
  
### <a href="README.md">Home</a> &nbsp; | &nbsp; <a href="portfolio-bhirabhat.md">Pae's Port</a> &nbsp; | &nbsp; <a href="portfolio-songpol.md">Leng's Port</a> &nbsp; | &nbsp; <a href="portfolio-theeranon.md">Pond's Port</a> &nbsp; | &nbsp; <a href="portfolio-warakorn.md">Big's Port</a> &nbsp; | &nbsp; <a href="portfolio-warawich.md">Nook's Port</a>

<br>

<img src="assets/bhirabhat/avatar-bhirabhat.jpg" width="120" style="border-radius:50%;"/>

<h1 align="center">Bhirabhat Klomjit (Pae)</h1>
<h3 align="center">Robotics & Automation Engineering Student</h3>
<p align="center">Systems Integration · Industrial Automation · Embedded Systems</p>
<p align="center">FIBO, KMUTT · 3rd Year</p>

<p align="center">
  <a href="mailto:bhirabhat.klom@mail.kmutt.ac.th"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Peaxtt"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.instagram.com/_bhirabhat_/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</p>

</div>

---

### About

Undergraduate Robotics & Automation Engineering student at **KMUTT's Institute of Field Robotics (FIBO)** with hands-on experience across robotics software, embedded control, industrial systems, networking, and field integration. I currently work part-time on applied robotics and industrial engineering projects at FIBO, with a focus on connecting subsystems, defining interfaces and operational requirements, deploying systems, and validating them on real hardware.

| | |
|---|---|
| **Degree** | B.Eng. Robotics & Automation · FIBO, KMUTT |
| **Year** | 3rd Year |
| **Focus** | Robotics System Integration · Industrial Automation · Embedded Systems |
| **Current Work** | Part-time robotics & industrial engineering projects at FIBO |

---

### Selected Professional Experience

#### Yokogawa — Pile Monitoring & Industrial Station Integration

Worked on the station-side database, monitoring, and integration layer of a warehouse pile-monitoring system that consumes processed data from a team-owned **8× Livox Mid-360 LiDAR** pipeline.

- Defined database/state requirements from real warehouse operating scenarios and coordinated interfaces with the LiDAR, robot, and decision-system teams.
- Integrated processed LiDAR output into the database/backend workflow and downstream read-only interfaces.
- Deployed the database, API, and dashboard stack on the actual Windows station.
- Conceived and developed the **FIBO Station Monitor** to consolidate station, VM, LiDAR, network, robot, and service health into a single operational view.
- Investigated AGV Wi-Fi and roaming issues using Aruba controller data, API/PowerShell diagnostics, ping/bandwidth tests, and real robot movement tests; supported on-site validation while the Aruba vendor performed final remote tuning.

> <img src="assets/bhirabhat/Yokogawa-PointCloud.jpg" height="220"/> <img src="assets/bhirabhat/Yokogawa-Dashboard.jpg" height="220"/>
> <br><br> <img src="assets/bhirabhat/Yokogawa-SlotStateMachine.png" width="600"/>

---

#### FACOBOT AMR — Operator Interface & ROS 2 Integration

Responsible for the operator-interface and ROS 2 bridge integration layer of a warehouse AMR forklift.

- Developed and integrated the touch-based operator interface with ROS 2 actions and robot state.
- Worked on velocity jogging, mission execution, actuator controls, telemetry, and fleet/order views.
- Added software-safety behavior including safe-state handling, watchdog logic, and dead-man control.
- Debugged and integrated navigation-related features with the rest of the robot system; the core navigation algorithms were developed by other team members.

> <img src="assets/bhirabhat/Facobot-Robot.jpg" height="220"/> <img src="assets/bhirabhat/facobot-manual-ui.jpg" height="220"/>

---

#### BGC — Industrial Inspection System Audit & PLC Validation

Audited an existing industrial inspection system and took responsibility for the **Core/Backend** scope.

- Mapped reported system symptoms to likely causes and separated issues by team ownership.
- Reviewed and corrected Core/Backend behavior while preserving existing system boundaries.
- Tested command/response behavior and validated the latest fixes with the real PLC/hardware setup.

<!-- Add BGC project image here when available:
> <img src="assets/bhirabhat/BGC-....jpg" height="220"/>
-->

---

#### Carver — ROS 2 Migration & SLAM

Responsible for the **SLAM/localization subsystem** in a team project migrating a conventional PLC-based system toward ROS 2.

- Generated maps and tuned localization behavior.
- Integrated LiDAR, TF, odometry, and ROS 2 topic flow for the SLAM subsystem.
- Connected the SLAM/localization work with the rest of the team's simulation.
- The team completed the project at the **simulation level**; this was not presented as a full machine deployment.

<!-- Add Carver project image here when available:
> <img src="assets/bhirabhat/Carver-....jpg" height="220"/>
-->

---

#### Peplink GPS–Odometry Alignment

Worked on a ROS 2 pipeline for aligning outdoor GPS measurements with robot odometry and tested it with real equipment.

- Parsed positioning data and converted it into the robot-local coordinate workflow.
- Worked with covariance handling, frame alignment, and GPS-to-odometry transformation.
- Integrated the result into the ROS 2 visualization/localization workflow for testing and debugging.

---

#### B2 Web RViz — Simulation-Focused Visualization Prototype

Extended a browser-based robot-visualization prototype for a Unitree B2 workflow.

- Worked with live/simulated point-cloud visualization, occupancy-map display, camera streaming, and waypoint interaction.
- Development and validation were primarily based on rosbag, dummy data, and simulation rather than full real-robot acceptance testing.

> <img src="assets/bhirabhat/b2-pointcloud-rviz.jpg" height="220"/>

---

### Coursework & Robotics Projects

#### FRA161 — Squash Ball Hitting Machine

Designed and built the control system using **555 timers, relays, and discrete logic without a microcontroller**.

- Designed the logic-control circuit, PCB/power-supply portions, and joystick interface.
- Assembled, soldered, wired, tuned, and tested the physical machine.

> <img src="assets/bhirabhat/Shooter-Joy.jpg" height="220"/> <img src="assets/bhirabhat/Prototype-Shooter-LogicControl.jpg" height="220"/> <img src="assets/bhirabhat/Shooter-Y1-2.jpg" height="220"/>

---

#### LiftEase — Patient Transfer Bed

Team project for a bed-to-bed patient-transfer prototype.

- Co-designed the mechanical structure, conveyor/motor system, electrical controls, and control workflow.
- Worked on motor-control firmware and the directional control interface.
- Participated in assembly and physical prototype testing.

> <img src="assets/bhirabhat/Auto-Flip-Bed.jpg" height="220"/>

---

#### 1-DOF Pick-and-Place Arm

Focused on the electrical/control side of a 1-DOF pick-and-place system.

- Designed the control-box electrical system and selected control components.
- Assembled and wired the control box.
- Worked on STM32 firmware, safety circuits, and proximity-sensor integration.
- Tested and debugged the system on the physical arm.

> <img src="assets/bhirabhat/1Dof-Pick-Place.jpg" height="220"/> <img src="assets/bhirabhat/1Dof-Electrical-Box.jpg" height="220"/>

---

#### Grease Separator / Oil Skimmer

Worked on the control and sensing portion of a grease-separation prototype.

- Developed the control electronics and Raspberry Pi Pico firmware.
- Integrated pH sensing, LCD/status indication, and automatic operating logic.
- Participated in assembly and physical testing with the prototype.

> <img src="assets/bhirabhat/Oil-Skimmer.jpg" height="220"/> <img src="assets/bhirabhat/Oil-Skimmer-Scraper.jpg" height="220"/>

---

#### ABU Robocon — Meihua

Contributed to the mobile-base software for a competition robot.

- Worked with ROS 2 / micro-ROS movement software and team integration.
- Integrated software from multiple team members and debugged system behavior on the real robot.
- Participated in real-robot testing, tuning, and competition-team support.

> <img src="assets/bhirabhat/ABU.jpg" height="220"/>

---

#### FRA361/362 — Innovation for Sustainability *(Ongoing)*

Current coursework focused on systems thinking and technology feasibility for improving healthcare access in Thailand.

- Researched telemedicine, rural healthcare workflows, medicine last-mile delivery, and medical-drone feasibility.
- Built causal-loop hypotheses and explored leverage points using evidence from Thai healthcare studies and current public-sector programs.
- Current stage: research and proposal development; no final prototype is claimed yet.

---

### Technologies & Tools I've Worked With

These are technologies I have used across projects; the list is **not intended as a proficiency ranking**.

**Robotics & Integration**  
`ROS 2` · `micro-ROS` · `TF2` · `Nav2` · `SLAM / Localization` · `MQTT` · `WebSocket` · `HTTP / REST`

**Embedded & Hardware**  
`STM32` · `Raspberry Pi Pico` · `Arduino` · `555 / Relay Logic` · `Sensor & Motor Integration` · `Electrical Wiring`

**Software & Data**  
`Python` · `C / C++` · `FastAPI` · `PostgreSQL / Supabase` · `React` · `Git` · `Docker`

**Deployment & Field Engineering**  
`Linux` · `Windows` · `PowerShell` · `Task Scheduler` · `Grafana / InfluxDB / Loki` · `PLC Integration & Testing` · `Industrial WLAN Diagnostics`

---

<p align="center"><sub>Portfolio updated for internship / CV use · September 2026</sub></p>
