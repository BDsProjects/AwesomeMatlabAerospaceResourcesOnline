# AwesomeMatlabAerospaceResourcesOnline
Awesome MATLAB Aerospace Resources Online (AMARO)

AwesomeMatlabAerospaceResourcesOnline (AMARO)

This is a list of Aerospace Engineering, System Modeling, related resources, projects, and some models for MATLAB that I’ve found. I put this list together to create a comprehensive list for attitude determination control systems (ADCS), flight dynamics, and similar modeling processes to use in MATLAB and Simulink.

I haven’t actually used all the libraries on this list, so I can’t vouch for their quality. I’m just noting their existence.

Submissions to this list are welcome. Make a Pull Request with them.

# Awesome MATLAB Aerospace Resources Online

Resources for all topics
- [Dr. Shane Ross's Youtube Channel](https://www.youtube.com/@ProfessorRoss) - Has videos, some including MATLAB examples on: Kalman filters, space vehicle dynamics, nonlinear dynamics and chaos,  orbital mechanics/dynamics, and many more advanced topics in high quality
- [Ben Dickinson](https://www.youtube.com/@LearnGandC/videos) - Covers undergraduate and graduate level courses on many topics of Guidance, Navigation, and Controls (GNC) for aircraft, spacecraft, control systems, and much more. 

## Intro Simulink and MATLAB Courses
- - [Control System Design with MATLAB and Simulink](https://matlabacademy.mathworks.com/details/control-system-design-with-matlab-and-simulink/lpmlslcsd) - linear/non-linear control systems, linearization of nonlinear systems
  - [MATLAB Skills for Simulink Modeling](https://matlabacademy.mathworks.com/details/matlab-skills-for-simulink-modeling/lpmlssm) - Effective MATLAB programming skills

## Spacecraft Modeling
- - [Spacecraft Simulation](https://www.mathworks.com/help/aeroblks/spacecraft.html?s_tid=CRUX_lftnav) - MathWorks' featured example and topic page to direct you to topics like Orbit Propagation Methods, Constellation Modeling, Spacecraft Dynamics and more
  - [NAIF ]() - Navigation and Ancillary Information Facility Spacecraft, Planet, Instrument, C-matrix, Events which can be used to mimmick previous spacecraft flights and events like Voyager planetary flybys, planetary movements, solar system events, etc. 
  - - [About Spice](https://naif.jpl.nasa.gov/naif/aboutspice.html) - What Spice is, its history, missions currently using it and m0re  
    - [About NAIF](https://naif.jpl.nasa.gov/naif/about.html) - What NAIF is and why it was created
    - [JSC Simulation & Modeling](https://www.nasa.gov/reference/jsc-simulation-modeling/) - NASA Johnson Space Center (JSC) modeling, simulation, visualization, and associated environments in multiple coding languages
    - [Reliability Approach to Optimal Thruster Configuration Design for Spacecraft Attitude Control Subsystem](https://doi.org/10.5028/jatm.v12.1112) - Very useful paper and one of few resources found for determinging the amount of thrusters for specified thrust(s) needed to ensure proper reliabilty and redundancy are possible.
    - - Ghobadi M; Shafaee M; Nadoushan Jafari M; (2020) Reliability Approach to Optimal Thruster Configuration Design for Spacecraft Attitude Control Subsystem. J Aerosp Technol Manag, 12: e2320. https://doi.org/10.5028/jatm.v12.1112
- - [Spacecraft Automated Landing System](https://www.mathworks.com/videos/spacecraft-automated-landing-system-68869.html?s_tid=srchtitle_videos_main_1_spacecraft) - "Model the fault management system of an automatic landing system for the HL-20, a spacecraft based on a specification from NASA."

### Spacecraft Modeling Repos
- - [Spacecraft Dynamics and Control](https://github.com/a-shakouri/Spacecraft-dynamics-and-control) - 

### Spacecraft Modeling Papers and Textbooks
- - [Spaceflight Dynamics: Third Edition 3rd ed. Edition](https://a.co/d/4di37rW) - Spaceflight Dynamics: 3rd Edition by William E. Wiesel is likely the most easy to read textbook I have ever had in my undergrad and graduate studies. Covers mainly orbital mechanics and dynamics instead of control systems or ADCS, but it helped me to understand the orbital environment well.
  - [Spacecraft Modeling, Attitude Determination, and Control: Quaternion-Based Approach by Yaguang Yang](https://ntrs.nasa.gov/api/citations/20240009554/downloads/Space%20Attitude%20Development%20Control.pdf) - NASA Technical Reports Server listed, Quaternion based attitude determination and control textbook with the best explanations of quaternion theory, use, and integration I have come across.
  - [A Model-Based Design & Testing Approach for Orion GN&C Flight Software Development by Joel Henry NASA-JSC](https://www.nasa.gov/wp-content/uploads/2016/10/01-03_orion_cre_exploration_vehicle_model_0.pdf) - A presentation on the MBSE process for the Artemis Mission Capsule, Orion's flight software development.
  - [MIT Open courseware - Lecture L17 - Orbit Transfers and Interplanetary Trajectories](https://ocw.mit.edu/courses/16-07-dynamics-fall-2009/e6393974ce4ed22b095f2e1d1a6a8e81_MIT16_07F09_Lec17.pdf) - Transfers from one orbit to another and the construction of interplanetary trajectories
  - [Introduction to Astrodynamic Reentry](https://apps.dtic.mil/sti/tr/pdf/ADA505342.pdf) - A free textbook that serves as an introduction to analytical re-entry problem and there solutions. This book has the approach: "How little can I know about the vehicle and still study its atmospheric entry?" - (I had this professor for an orbital class and it was electric in person)



## Aircraft Modeling

- - [aircraft-design](https://github.com/topics/aircraft-design) - Aircraft design tag on GitHub topics

### Aircraft Modeling Repos
- - [Flight-Dynamics-and-Control-UAVs](https://github.com/lamfur07/Flight-Dynamics-and-Control-UAVs) - Flight control systems, trajectory following, low level autopilot design
 
### Aircraft Modeling Papers and Textbooks
- - [M&AE 5070 -- Dynamics of Flight Vehicles](https://courses.cit.cornell.edu/mae5070/) - introduction to the engineering science of flight dynamics
- - [Chapter 4 Dynamical Equations for Flight Vehicles](https://courses.cit.cornell.edu/mae5070/DynamicEquations.pdf) - Derivation of the equations of motion, their linearization, intro of dimensionless stability derivatives and aerodynamic coefficients, and principal contributions to stability derivatives for vehicles with left/right symmetry
- 

### Aircraft Modeling Videos
  - [Modeling, Simulation, and Flight Control Design of an Aircraft with Simulink](https://youtu.be/LzQPJRt00Ng?si=n-NLDD2Dqj_THQeJ) - Video from the official MATLAB Youtube channel

## Missile Modeling
- - [MissileSimulation](https://github.com/JohannesAutenrieb/MissileSimulation) - Transsonic Missle System Model

### Missile Modeling Papers and Textbooks
- - [JOHNS HOPKINS APL TECHNICAL DIGEST, VOLUME 29, NUMBER 1 (2010)](https://secwww.jhuapl.edu/techdigest/Home/Detail?Journal=J&VolumeID=29&IssueID=1) - Missile flight control system modeling, homing missile guidance and its mathematical background, missile guidance filter techniques, GNC for 6 DoF simulations, and advanced missile guidance and control algorithms/adjustments - This technical digest from Johns Hopkins APL covers the processes for guided missiles making adjustments based on the data of the target and how the data changes. 
