# Electronic Fuel Injection and Hybrid Technology

This repository contains diagrams, images, and technical information related to **Electronic Fuel Injection (EFI)** systems and **Hybrid Vehicle Technology**. It has been created as part of the Automobile Technician coursework to support learning and reference on modern vehicle technologies.

---

## 📚 Overview

This repository covers the following key areas:

- 🔋 [Hybrid Vehicle Technology](#-hybrid-technology)
- ⛽ [Electronic Fuel Injection (Petrol & Diesel)](#-electronic-fuel-injection-efi-system)
- 🛠️ [Engine Symptom Diagnosis](#-engine-symptom-diagnosis)
- 🔍 [Sensors and Actuators](#-sensors-and-actuators)
- ⚙️ [Function of EFI and Hybrid Systems](#-function-of-the-system)

The content includes technical explanations and visual diagrams to help understand how modern automotive fuel delivery and hybrid systems operate.

---

## 🔋 Hybrid Technology

Hybrid vehicles combine an internal combustion engine (ICE) and one or more electric motors, along with a battery pack and power management system. These systems work together to optimize fuel usage, reduce emissions, and improve vehicle performance.

### 🔧 Why Hybrid?

- Traditional vehicles waste energy through idling and braking.
- Hybrids recover and reuse that energy.
- They switch intelligently between electric and fuel power.

### 🧠 How It Works (Simplified):

- At low speeds or during light acceleration, the electric motor powers the car.
- During high power demand (under high load conditions), the engine and motor work together.
- Regenerative braking converts braking energy into electricity to charge the battery.
- The ECU (Electronic Control Unit) manages this switching automatically.

- **Boost Converter**
![IMG-20250902-WA0030](https://github.com/user-attachments/assets/8715c8af-8465-4220-9c34-37b99e9d7524)

- **Energy Line**
![IMG-20250902-WA0028](https://github.com/user-attachments/assets/ad3772a0-9976-4d0d-bc8c-146d1083b119)



### 🔀 Types of Hybrid Systems

| Type            | Description                                       | Example                         |
|-----------------|---------------------------------------------------|---------------------------------|
| Parallel Hybrid | Engine and motor both drive the wheels            | Toyota Prius                    |
| Series Hybrid   | Engine charges battery; motor drives wheels only  | BMW i3 (range extender version) |
| Plug-in Hybrid  | Larger battery; charge externally                 | Mitsubishi Outlander PHEV       |

- **Parallel Hybrid System**:
![IMG-20250902-WA0025](https://github.com/user-attachments/assets/3e1c1c48-6de0-4202-853e-653b8b188e77)

- **Series Hybrid System**:
![IMG-20250902-WA0024](https://github.com/user-attachments/assets/6dcb78d1-868c-4cfc-a9e0-40e4f3278d6e)

- **Series/Parallel Hybrid System**:
![series-parellel](https://github.com/user-attachments/assets/2fb6713c-9484-4045-a97e-eaf4a1719c57)

- **Example:** Toyota Prius - parts of the hybrid system
![IMG-20250902-WA0026](https://github.com/user-attachments/assets/d21b8cf1-037c-4733-86c5-7616e6ae5088)


### Key Components

- Internal Combustion Engine (ICE)
- Electric Motor/Generator
- High-Voltage Battery Pack
![WhatsApp Image 2025-09-02 at 15 13 23_00d9b255](https://github.com/user-attachments/assets/3e7c121d-f251-4a5f-9760-ead6e64b4fcf)

- Inverter/Converter
![IMG-20250902-WA0029](https://github.com/user-attachments/assets/3a3d3d5e-8378-41f1-ac5f-8deed5e47ed4)

- Power Control Unit (PCU)
- Transmission
  - **Power Splitter**
    ![IMG-20250902-WA0027](https://github.com/user-attachments/assets/44d6634f-bb19-43c9-9509-95a265cd53fc)


### Benefits

- Improved fuel efficiency (30–50% better)
- Reduced emissions
- Regenerative braking (energy recovery)
- Smoother city driving
  
---

## ⛽ Electronic Fuel Injection (EFI) System

EFI replaces the older carburetor-based system with a more precise, computer-controlled system. It ensures accurate fuel delivery based on engine demands.

### 💡 Why EFI?

- In a carburetor, fuel delivery depends on air pressure differences.
- In EFI, sensors feed data to the ECU, which calculates the exact amount of fuel needed — real-time!

### 🛠️ How EFI Works

1. Air enters through the air filter and throttle body.
2. The **MAF** or **MAP** sensor measures the air.
3. The **ECU** calculates fuel amount and timing.
4. Fuel injectors spray fuel into the intake manifold or directly into the combustion chamber.
5. **Spark plug** ignites the mixture.

- **Rail Pressure Calculation**
<img width="398" height="221" alt="image" src="https://github.com/user-attachments/assets/6bee76b0-9ce4-4f94-b592-ac43b9f122f0" />

### 🧪 Petrol EFI

- Works with spark ignition engines.
- Port Injection: Sprays fuel just before the intake valve.
- Direct Injection: Sprays fuel directly into the combustion chamber — more efficient but complex.

- **Direct Injection:**
![IMG-20250902-WA0018](https://github.com/user-attachments/assets/a0b273ba-1ddc-4ade-adaa-30ba7d1eae56)


### 🔧 Diesel EFI (Common Rail System)

- Diesel injectors use very high pressure (up to 2000+ bar).
- Common rail keeps pressure constant.
- The ECU controls timing, pressure, and duration of each injector.

![IMG-20250902-WA0023](https://github.com/user-attachments/assets/30f7b5e0-bcc6-4bfc-b56c-422fc8746140)

- **EDC System:**
![IMG-20250902-WA0021](https://github.com/user-attachments/assets/8732481c-d08a-45fa-8080-7917ca352f18)

- **Solenoid Valve Control Radial position type pump:**
![IMG-20250902-WA0020](https://github.com/user-attachments/assets/22e0480c-bf80-454a-9ea2-d85fc3a82895)


### Advantages of EFI

| Benefit             | Explanation                                |
|---------------------|--------------------------------------------|
| Fuel Efficiency      | Accurate fuel metering = less waste        |
| Lower Emissions      | Cleaner combustion = fewer pollutants      |
| Performance          | Better throttle response and power         |
| Diagnostics Ready    | Can be easily scanned using OBD tools      |

---

## 🛠️ Engine Symptom Diagnosis

Being able to identify engine problems based on symptoms is a vital technician skill.

### 🔍 Common Engine Symptoms and Possible Causes

| Symptom              | Possible Cause                       | System Affected          |
|----------------------|---------------------------------------|---------------------------|
| Rough idle           | Vacuum leak, dirty IACV              | Air intake, ECU           |
| Poor fuel economy    | Bad O2 sensor, dirty air filter      | EFI, sensors              |
| Engine misfire       | Faulty spark plug or injector        | Ignition, fuel system     |
| Black exhaust smoke  | Too rich fuel mixture                | EFI, fuel pressure system |
| Check engine light   | Faulty sensor, ECU error             | Various systems           |
| Engine hesitation    | TPS malfunction                      | Throttle system           |
| Engine knock         | Wrong fuel, timing issue             | Combustion, ECU           |

### 🧰 Tools for Diagnosis

- **OBD-II Scanner** – Reads fault codes (e.g., P0300- random multiple cylinder misfire)
- **Multimeter** – For checking sensor voltage and resistance
- **Fuel Pressure Gauge** – Verifies pump and injector pressure
- **Smoke Machine** – Finds vacuum leaks in intake system

---

## 🔍 Sensors and Actuators

Modern vehicles rely on dozens of sensors to collect data and actuators to perform actions based on that data.

### 📡 Common Sensors and Their Functions

| Sensor       | Full Name                     | Function                                  |
|--------------|-------------------------------|-------------------------------------------|
| MAF          | Mass Air Flow Sensor          | Measures air entering the engine          |
| MAP          | Manifold Absolute Pressure    | Measures intake pressure                  |
| TPS          | Throttle Position Sensor      | Detects throttle valve angle              |
| ECT          | Engine Coolant Temperature    | Monitors coolant temperature              |
| O₂ Sensor    | Oxygen Sensor (Lambda Sensor) | Measures oxygen level in exhaust gases    |
| CKP          | Crankshaft Position Sensor    | Tracks crank angle and RPM                |
| CMP          | Camshaft Position Sensor      | Synchronizes injector timing              |
| IAT          | Intake Air Temperature        | Affects fuel-air mix in cold/hot weather  |

### ⚙️ Common Actuators and Their Roles

| Actuator           | Function                                 |
|--------------------|------------------------------------------|
| Fuel Injectors     | Deliver precise amount of fuel           |
| Idle Air Control   | Regulates air during engine idle         |
| EGR Valve          | Recirculates exhaust gas to reduce NOx   |
| Throttle Body      | Controls airflow to engine               |
| Purge Valve (EVAP) | Releases fuel vapors from charcoal canister |

#### If a sensor fails, the ECU may enter "limp mode / safe mode", using default values — performance will drop, but the vehicle stays drivable.

--- 

## ⚙️ Function of the System
![IMG-20250902-WA0013](https://github.com/user-attachments/assets/77c2ff7e-18c8-487e-9a3d-5557482e9a0f)


- **System Identification:**
![IMG-20250902-WA0017](https://github.com/user-attachments/assets/32148469-0dd3-4586-940a-81be0398e6df)

- **Air Flow Diagram:**
![IMG-20250902-WA0014](https://github.com/user-attachments/assets/597f2458-dc9c-4f71-a803-2ea363ce3577)


- **Fuel Flow Diagram:**
![IMG-20250902-WA0015](https://github.com/user-attachments/assets/f37d3301-751d-4ef3-8bde-3fb5e47dad76)


- **Electrical Flow Diagram:**
![IMG-20250902-WA0016](https://github.com/user-attachments/assets/03fa29de-3440-4c46-b69e-4779d2d94b4e)


### 🚗 EFI System (Step-by-Step)

1. Air enters through the **air filter and throttle body**.
2. **MAF/MAP sensors** measure incoming air.
3. ECU calculates the correct **fuel-air ratio**.
4. **Fuel injectors** deliver fuel into the manifold or cylinder.
5. **Spark plug** ignites the air-fuel mixture.
6. **O₂ sensor** checks exhaust gas and reports to ECU.
7. ECU makes real-time adjustments (closed-loop control).
8. ECU reads throttle position, air temp, coolant temp.

### ⚡ Hybrid System (Step-by-Step)

1. Vehicle starts in electric-only mode (if battery has enough charge).
2. ECU decides when to start the engine based on speed, load, or battery.
3. Engine and motor may work together during acceleration.
4. During braking or coasting, electric motor becomes a generator.
5. Captured energy is stored in the battery (regenerative braking).
6. All operations are managed by Hybrid Control Module (HCM).




