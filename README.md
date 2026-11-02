# AeroQuest-AR based Drone Simulation
An Augmented Reality Drone Flight Simulator for Safe, Interactive & Gamified Drone Training.

Built by Team Cipher Seekers | SYNERGY 2026 – 8-Hour Hardware Simulation Hackathon | Fr. CRCE, Mumbai

## 🚀 About AeroQuest

**AeroQuest** is an AR-powered, gamified drone flight simulation application for Android that helps beginners learn to operate a Pluto drone in a safe, virtual environment before handling the actual hardware.

Using **Augmented Reality (AR)**, AeroQuest places a virtual Pluto drone and interactive flight arena onto real-world surfaces through a smartphone camera. It replicates the real drone's Mode 2 controller, allowing users to practise essential flight operations such as throttle, yaw, pitch, roll, hovering, navigation, take-off, and landing.

The application provides a structured learning experience through:

- **Guided Tutorial:** A 7-stage interactive tutorial that teaches users the fundamentals of drone controls and flight operations.
- **Three Interactive Missions:** First Flight, Control Lab, and Checkpoint Run, designed to improve flight control, precision, and navigation skills.
- **Pluto Rescue:** A bonus flood-rescue simulation where users deliver a medical package to a stranded survivor using physics-based drone navigation and package delivery.
- **Realistic Flight Simulation:** Flight physics, movement smoothing, altitude and range restrictions, landing mechanics, collision detection, and optional wind.
- **Interactive Cockpit HUD:** Displays altitude, speed, vertical velocity, objectives, timers, tracking status, and flight warnings.
- **Three Difficulty Levels:** Easy, Normal, and Hard.
- **Offline Experience:** All gameplay, progress, difficulty settings, and best scores are stored locally without requiring an internet connection.

By combining AR technology, physics-based simulation, and game-based learning, AeroQuest aims to make drone training more accessible while reducing the risk of hardware damage, wasted batteries, and unsafe beginner flights.


# PROJECT DEMO VIDEO
video link: https://drive.google.com/file/d/1Dvr-yiouabRmZAkNF3OEU9S2_ScWEzHJ/view?usp=sharing

## 🛠️ Tech Stack

AeroQuest is developed using the following technologies and tools:

### 🎮 Game Development
- **Unity 6 (6000.6.7f1)** – Game engine used for scene management, rendering, gameplay, and simulation.
- **C#** – Primary programming language used for gameplay logic, drone flight mechanics, physics, and UI implementation.

### 🥽 Augmented Reality
- **AR Foundation 6.7.1** – Enables augmented reality functionality, plane detection, raycasting, and surface tracking.
- **Google ARCore XR Plugin 6.7.1** – Provides Android-based AR tracking, surface detection, and anchoring.

### 🎮 Input & Controls
- **Unity Input System 1.20.1** – Handles multi-touch virtual joysticks, keyboard input, and gamepad controls.

### 🧊 3D Models & Physics
- **glTFast 6.1.0** – Used to import and load the Pluto drone 3D model.
- **Unity Physics** – Handles drone movement, Rigidbody simulation, collision detection, and physics-based package delivery.

### 🖥️ User Interface
- **Unity UI (uGUI) 2.6.0** – Used to build the runtime-generated interface, cockpit HUD, menus, virtual controllers, and interactive elements.

### 💾 Data Storage
- **Unity PlayerPrefs** – Stores tutorial progress, selected difficulty levels, and mission best scores locally on the device.

### 📱 Platform & Build Tools
- **Android SDK / ADB** – Used for Android application builds, installation, and real-device testing.
- **ARM64 & IL2CPP** – Used for Android application architecture and scripting backend.
- **Unity Hub** – Used to manage Unity installations and project versions.

### 🔧 Version Control
- **Git** – Version control and source code management.
- **GitHub** – Repository hosting and project collaboration.

### 📲 Platform Information
- **Target Platform:** Android
- **Minimum Android Version:** Android 7.0 (API Level 24)
- **Rendering Pipeline:** Built-in Render Pipeline
- **Application ID:** `com.teampluto.arflightschool`
- **Internet Requirement:** Not required for gameplay

## ⚙️ Installation & Setup

Follow these steps to run AeroQuest locally.

### Prerequisites

Before starting, make sure you have:

- [Unity Hub](https://unity.com/download)
- Unity Editor **6 (6000.6.7f1)**
- Android Build Support module
- Android SDK & NDK
- OpenJDK
- A compatible Android smartphone with ARCore support
- Google Play Services for AR installed on your device

### Step 1: Clone the Repository

```bash
git clone https://github.com/huzy-2006-eng/PlutoAR.git
```

### Step 2: Open the Project

1. Open Unity Hub.
2. Select **Add → Add project from disk**.
3. Navigate to the cloned repository.
4. Open the project using Unity 6 (6000.6.7f1).
5. Allow Unity to import assets and resolve packages.

### Step 3: Configure Android Build Settings

1. Open **File → Build Profiles**.
2. Select Android as the target platform.
3. Switch to Android if required.
4. Ensure the project is configured for ARM64 architecture and IL2CPP.
5. Verify that the minimum Android API level is set to 24 or higher.

### Step 4: Connect Your Android Device

1. Enable Developer Options on your Android smartphone.
2. Enable USB Debugging.
3. Connect your device to your computer.
4. Make sure your device supports ARCore.

### Step 5: Build and Run

1. Open the Android Build Profile.
2. Add the required game scenes to the build configuration.
3. Select Build or Build and Run.
4. Install the generated APK on your Android device.
5. Launch AeroQuest and scan a suitable flat surface to begin.

### Step 6: Start Exploring

- Follow the guided tutorial.
- Practise drone controls.
- Complete the three missions.
- Try the bonus Pluto Rescue scenario.

**Note:** AR functionality requires a compatible device and adequate lighting and surface features for tracking. Unity may take some time to import project assets on the first launch.

## 🎯 Conclusion

AeroQuest demonstrates how Augmented Reality, game development, and physics-based simulation can come together to create a safer and more engaging drone-learning experience.

By allowing beginners to practise drone operations in their own surroundings without risking physical hardware, AeroQuest bridges the gap between theoretical learning and practical drone training.

Developed as part of **SYNERGY 2026**, an 8-hour Hardware Simulation Hackathon organized by the Students' Council at Fr. Conceicao Rodrigues College of Engineering, Mumbai, this project represents our effort to explore innovative, sustainable, and technology-driven engineering solutions.

We believe that the best way to learn flying a drone is to practise, experiment, and improve — without worrying about your first crash.

**Learn. Simulate. Fly. Explore.**

---

### 👥 Developed By

**Team CIPHER SEEKERS**

### 🔗 Project Repository

[GitHub – AeroQuest (PlutoAR)](https://github.com/huzy-2006-eng/PlutoAR)

