# Project Portfolio
Showcasing technical projects in Aerospace Engineering

## About Me
Hi, I'm Aurian Malhotra, a graduating Aerospace Engineering student at UC Davis. I have a strong background in structural design and analysis, stability analysis, and dynamic simulations, with hands-on experience in GNC and attitude control systems. I'm actively seeking roles in GNC, aerodynamics/CFD, and propulsion. This repository showcases my engineering projects, including MATLAB simulations, CAD models, circuit designs, and experimental results.

### 🔹 Industry Projects

**Fixture Assembly for Drone Charging Station as  an Asylon Robotics Intern**

*Overview*
- Designed and modeled a heavy-duty fixture assembly in CATIA V6 to support a 600 lb payload (1000 lb tested) for Asylon's autonomous drone chargin station, enabling 360° rotation and 4ft vertical lift
- Engineered custom components, including mounting plates, shafts, and bearing assemblies, and performed structural and deformation analyses to ensure strength, stability, and manufacturability
- Resolved key design challenges involving center of gravity, load distribution, fastening methods, and tipping prevention, supported by extensive independent research and collaboration with engineers and suppliers

📂 **Files:** [[For a full technical breakdown of the design process, challenges, and CAD images, see detailed report]](https://github.com/aurian-malhotra/Project_Porfolio/blob/main/Fixture%20Assembly%20Description.docx)

### 🔹 UC Davis Projects

**EAE 143A - Space Mission Design**

*Overview*

Our team reverse-engineered NASA's CPOD (CubeSat Proximity Operations Demonstrator) and developed a proposed redesign redefining the mission as a proximity inspection demonstrator near the ISS. The project culminated in a Critical Design Review (CDR) covering all subsystems with supporting engineering analysis.

My role was GNC/ADCS lead. My contributions include:
- Designed an LVLH-frame inspection circuit using Clohessy-Wiltshire trajectory families (along-track drift, ellipse, cusp final approach) and performed delta-V budget analysis to verify feasibility against the propulsion system
- Conducted subsystem trade study on desaturation architecture, recommending a dedicated magnetorquer over a thruster-based approach to preserve the full translational delta-V budget for inspection maneuvers
- Modeled all four environmental disturbance torques (gravity gradient, aerodynamic drag, solar radiation pressure, magnetic) including eclipse and sun geometry for SRP; estimated momentum accumulation and total impulse requirements to size the desaturation system
- Developed a MATLAB rigid-body ADCS simulation: quaternion attitude propagation (RK4), PD reaction wheel control, disturbance torque injection, gyro and star tracker noise modeling, and SGP4 orbit propagation with ISS TLE data. Quaternion dynamics and momentum accumulation behavior are validated; desaturation logic is the active extension.
- Developed independent MATLAB astrodynamics simulations covering SGP4 orbit propagation, ECI/ECEF/LVLH frame transforms, ground station access analysis, and spacecraft power and mode management across multi-day mission timelines

📂 **Files:**[[Reports and Posters]](https://drive.google.com/drive/folders/1nApysK6UlAGnysXohgcYhqiRjGhMnylp?usp=drive_link)

**EAE 198 - Compressible Aerodynamics: Oblique Shock Wave Analysis Over a Supersonic Wedge**

*Overview*
- Solved the theta-beta-M relation numerically in MATLAB to predict oblique shock wave angles over a two-dimensional wedge across nine flow conditions (M = 2, 2.5, 3; theta = 5°, 10°, 15°)
- Simulated supersonic flow using ANSYS Fluent with a density-based solver and second-order upwind scheme, extracting shock angles from Mach number contour plots for comparison against theory
- Extracted quantitative shock angle measurements from Schlieren photography of supersonic wind tunnel experiments using a pixel-coordinate method, achieving agreement within 2° of analytical values across most conditions
- Co-plotted all three methods on a theta-beta-M diagram and performed qualitative comparison of Schlieren images against CFD Mach contours across all nine cases, validating both computational setup and measurement technique

📂 **Files:**[[Project Report]](https://github.com/aurian-malhotra/Project_Porfolio/blob/main/EAE%20198%20Project.docx)

**EAE 133 - Finite Element Methods in Aerospace Structures**

*Overview*
- Performed linear static and bending anlyses using MSC Patran/Nastran, indlucidng model setup, meshing strategy selection, boundary condition definition, and load case development.
- Validated FEA results against analytical beam theory (Euler-Bernoulli) to evaluate stress distributions, deflections, and structural safety margins.
- Investigated mesh convergence, element type selection, and modeling assumptions to assess numerical accuracy and structure failure predictions

📂 **Files:**[[Lab Reports Throughout the Course]](https://drive.google.com/drive/folders/1_NZoNjp8xKMigvYpjC9reBfsTeTsnt6c)

**EME 165 - Heat Transfer: 2D Numerical Conduction Analysis of a Lightsaber Thermal System**

*Overview*
- Built a 2D steady-state numerical conduction model in MATLAB to analyze heat transfer within a composite lightsaber system
- Derived and solved nodal energy balance equations to map temperature distribution across the core and handle
- Visualized thermal gradients with contour plots and evaluated heat transfer to the user under varying convection conditions

📂 **Files:** [[Contains derivations, numerical solutions, and final results of the 2D conduction analysis]](https://github.com/aurian-malhotra/Project_Porfolio/blob/main/Project%20(1).pdf)

**EAE 129 - Stability and Control of Aerospace Vehicles: Simulation and Analysis of Aircraft Dynamic Characteristics**

*Overview:*
- Simulated dynamic motion response of an aerospace system using MATLAB.
- Assessed stability margins, damping ratios, and eigenvalue analysis.
- Developed visualizations of system response to various input conditions.

📂 **Files:** [[MATLAB scripts, simulation results, stability analysis report.]](https://github.com/aurian-malhotra/Project_Porfolio/raw/refs/heads/main/EAE%20129%20Final%20Project%20Report.docx) 

**EAE 129 - Stability and Control of Aerospace Vehicles: Static Stability Analysis of a UAV**

*Overview:*
- Conducted wind tunnel data analysis to estimate aerodynamic and stability derivatives.
- Generated and analyzed plots of lift coefficient, moment coefficient, and stability margins.
- Simulated UAV dynamic response using MATLAB to assess damping ratios, natural frequencies, and stability modes.
  
📂 **Files:** [MATLAB scripts, Aerodynamic Data, and stability calculations.](https://github.com/aurian-malhotra/Project_Porfolio/raw/refs/heads/main/EAE%20129%20Midterm%20Report.docx)

**ENG 003 - Intro to Engineering Design: Soil Moisture Sensor**

*Overview:*
- Modeled and designed a soil moisture sensor using 3D CAD Modeling (Onshape).
- Developed a circuit layout for environmental monitoring.
- Analyzed sensor response to varying moisture levels.

📂 **Files:** [3D models, circuit designs, sensor analysis report.](https://github.com/aurian-malhotra/Project_Porfolio/raw/refs/heads/main/ENG%203%20Poster.pptx)

**ENG 004 - Engineering Graphics in Design: Desk Lamp CAD Modeling**

*Overview:*
- Designed a detailed 3D model of a desk lamp using SolidWorks.
- Created and assembled multiple components, including an immovable on/off switch.
- Applied engineering design principles to ensure realistic functionality and manufacturability.

📂 **Files:** [Project Report.](https://github.com/aurian-malhotra/Project_Porfolio/raw/refs/heads/main/ENG%204%20Final%20Report%20-%20Desk%20Lamp.docx)

**Electronic Circuits and Systems (Circuits II)**
In ENG 100, I gained hands-on experience with analog and digital circuits, focusing on both signal processing and circuit design. A key component of the course was learning how to use important electrical engineering equipment such as the digital multimeter, waveform function generator, and oscilloscope. These tools were essential for analyzing and testing various circuits throughout the course.

*Key Labs*

Band-Pass Filter Design:
The objective of this lab was to create a band-pass filter and analyze its effect on an input signal. This involved configuring multiple op-amps and capacitors to form a combination of low-pass and high-pass filters, allowing the circuit to pass a range of frequencies while filtering out those outside this range. Measurements of the output voltage, gain, time delay, and phase were made across various frequencies, and we confirmed that the filter successfully passed the desired frequencies while attenuating others. A significant part of the process involved troubleshooting the multi-stage filter design to ensure proper performance for both the low-pass and high-pass components before combining them.

Lightmeter System:
I designed and implemented a lightmeter system using a Raspberry Pi Pico and associated components. The system integrated a Wheatstone bridge and an RC low-pass filter to measure light intensity, providing real-time data on a 7-segment display.

📂 **Files:** [Lab Reports.](https://drive.google.com/drive/folders/1OLIxaxhgJKH4SrdHeABY9mvpxBQZqFdm?usp=drive_link)

## How to Use This Portfolio
- Click on each project folder to explore code, reports, and designs.
- View simulation results and documentation in related sections.
- Contact me via [[LinkedIn](https://www.linkedin.com/in/aurian-malhotra-77371a231/)] for inquiries.
