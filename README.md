<div align="center">
        
## 3D Printed Modular Gearbox ⚙️
</div>

<br>

<p align="center">
        <img width="80%" alt="Title_Light" src="https://github.com/user-attachments/assets/31b918f9-25d2-4012-86c7-cd4ae6839da4#gh-light-mode-only" />
        <img width="80%" alt="Title_Dark" src="https://github.com/user-attachments/assets/d6699bf1-acf1-4c29-a087-e45d440a396a#gh-dark-mode-only" />
</p>

<div align="center">
        
A 3D-printable, high-torque modular planetary gearbox system designed for **robotics and DIY automation.**

Compatible with **NEMA 23** motors.

</div>

<br>

<p align="left">
        <img width="40%" alt="Horizontal_5_Light" src="https://github.com/user-attachments/assets/7f29734f-ee41-4fc3-a1ee-f25785372f8d#gh-light-mode-only" />
        <img width="40%" alt="Horizontal_5_Dark" src="https://github.com/user-attachments/assets/104e5f26-e96c-4d71-a37e-31f981c40824#gh-dark-mode-only" />
</p>

<p align="center">
        <img width="100%" alt="Horizontal_6_Light" src="https://github.com/user-attachments/assets/8a9b716f-0b3a-43e7-83e5-450f1d8375a7#gh-light-mode-only" />
        <img width="100%" alt="Horizontal_6_Dark" src="https://github.com/user-attachments/assets/aa6ea96e-393b-4384-b037-9c602d49d27b#gh-dark-mode-only" />

</p>

<br>

### Table of contents:
- [Introduction](#introduction)
- [How does it work?](#how_does_it_work?)
  - [Gear design](#gear_design)
- [Gearbox breakdown](#gearbox_breakdown)

---

## Introduction

Built as a fun engineering project, this **modular gearbox** was designed to test the **capability of modular stages** of different architectures.

<br>

## How does it work?

This modular gearbox consists of **3 main parts:**  
<sub>*=required</sub>

- **Base stage***
- **Modular stage**
- **Output stage***

Where each stage applies a **4.615:1 ratio**

<div align="center">

### Gear design

| | Teeth | Amount |
| --- | --- | --- |
| **Internal** | 47 |  |
| **Sun** | 13 |  |
| **Planet** | 17 | 3 |
| | | |
| **Module Number** |  | **0.93** |
| **Ratio (Per stage)** | | **4.615:1** |

</div>

> [!NOTE]
> I plan on implementing a **Cyloidal drive** system soon.

<br>

## Specifications

<div align="center">

### Printing

| | Configuration |
| --- | --- |
| **Printed Material** | ABS |
| **Printer** | Bambu Lab X1C |
| **Nozzle Diameter** | 0.4mm |

</div>

<div align="center">

### Electronics

| Part | Image | Function | Configuration |
| --- | --- | --- | --- |
| **TB6600** | <img width="100" alt="TB6600-Stepper-Motor-Driver-1-2366261077" src="https://github.com/user-attachments/assets/00fd8804-89b6-48a5-8197-880d0544e630" /> | Motor Driver | Micro step setting: **2**<br>Current: **2.5A**<br>Voltage: **24V** |
| **ESP32-WROOM-32D** | <img width="100" alt="ESP32WROOM32D" src="https://github.com/user-attachments/assets/58cc57ed-a39e-4660-9ab9-adc7b6bc89e2" /> | Micro Controller | |
| **NEMA 23 Stepper Motor** | <img width="100" alt="nema-23-stepper-motor" src="https://github.com/user-attachments/assets/9ac2278d-cf41-489c-8d5a-76f08e49ae8c" /> | Motor | Shaft OD: **8mm**<br>Shaft length: **27mm** |

</div>

## Print configuration WIP
