# STM_and_Sensors


## **Objective**  
To build foundational knowledge on STM microcontrollers and essential sensors, set up PlatformIO for embedded development, and create a comprehensive report on perception sensors and motors, including their integration with ROS.  

---

## **Task Breakdown**  

### ✅ 1. Learn about STM Microcontrollers (STMs)  
- Understand what **STM microcontrollers** are, including architecture and common series (e.g., **STM32**).  
- Study their applications in **robotics, automation, and embedded systems**.  
- Learn about **GPIO, I2C, SPI, UART** and how STMs interface with peripherals.  

---

### ✅ 2. Install and Set Up PlatformIO on VS Code  
- Install **Visual Studio Code (VS Code)** if not already installed.  
- Install the **PlatformIO extension** for embedded system development.  
- Verify installation by creating and running a **sample STM32 project**.  
- Understand how **PlatformIO manages libraries and toolchains** for STM32 development.  

---

### ✅ 3. Research & Report: Perception Sensors and ROS Integration  
Prepare a detailed report on the following sensors and focus on **how ROS (Robot Operating System)** is used with them:  

#### 🔹 IMU (Inertial Measurement Unit)  
- Role in **orientation, localization, balancing**.  
- ROS packages commonly used (e.g., `imu_filter_madgwick`, `robot_localization`).  

#### 🔹 LiDAR (Light Detection and Ranging)  
- Applications in **SLAM, obstacle detection, mapping**.  
- ROS drivers and processing pipelines (e.g., `rplidar_ros`, `velodyne`).  

#### 🔹 Stereo Cameras  
- Used for **depth estimation, visual odometry, 3D mapping**.  
- Relevant ROS packages (e.g., `stereo_image_proc`, `zed_ros`).  

#### 🔹 GPS (Global Positioning System)  
- Role in **outdoor navigation, localization**.  
- How **GPS data fusion** works in ROS (e.g., `nmea_navsat_driver`).  

##### **Key Points to Cover in Report**:  
- Overview and working principle of each sensor.  
- ROS integration: packages, nodes, and message types.  
- Example use cases in robotics.  

---

### ✅ 4. Study & Document: Basic Sensors, Motors, and Drivers  

#### 🔹 Sensors  
- **HC-SR04 Ultrasonic Sensor**: Distance measurement, interfacing, typical use cases.  
- **LSA08 Line Sensor Array**: Line-following robotics, interfacing, output format.  
- **IR Sensors**: Obstacle detection, proximity sensing, interfacing basics.  

#### 🔹 Motors and Actuators  
- **Servo Motors**: Working principle, control signals, applications.  
- **DC Motors**: Operation, control circuits, use cases.  
- **Brushed vs Brushless Motors**: Comparison, pros/cons, when to use each.  

#### 🔹 Motor Driver: **MDD10A**  
- Read and summarize **MDD10A datasheet**.  
- Focus on:  
  - **Voltage/current ratings**.  
  - **Control interfaces (PWM, DIR)**.  
  - Application circuits and usage examples.  

---

## **Deliverables**  

- 📄 **Detailed report** (PDF/Docx) covering:  
  - IMU, LiDAR, Stereo Cameras, GPS with ROS integration.  
  - Basic sensors and motor driver analysis.  
- 📑 Optional: Short summary on **STM32 basics**.  
- 📷 **Screenshots** showing PlatformIO setup and running STM32 project.  

---

## **Bonus (Optional)**  
- Create a **GitHub repository** to upload your PlatformIO test project and final report.  

---

