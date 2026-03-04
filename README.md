# Fall Guys (AI Simulation)
> **Former Name:** *Dumb ways not to die*

This project is a 3D simulation built with Unity and ML-Agents to analyze how individuals can survive a fall through physical posturing and impact mitigation.

---

## Prerequisites
Before running the project, ensure your environment meets the following specifications:

| Requirement | Version / Link |
| :--- | :--- |
| **Python** | `3.8` |
| **Unity Editor** | `2022.3.21f1` |
| **ML-Agents** | [Release 20](https://github.com/Unity-Technologies/ml-agents/tree/release_20_post) |
| **Dependencies** | `requirements.txt` |

---

## Overview

### Dummy & Testing Environment
The simulation utilizes a 3D dummy dropped within a controlled environment to test various falling dynamics.

<p align="center">
  <img width="220" height="200" src="https://github.com/lobsterglep/AI_project/assets/156586679/e2c93355-251d-46cc-9868-41e2332ec1d1" alt="Dummy Model">
  <img width="50%" src="https://github.com/lobsterglep/AI_project/assets/156586679/e5a2818c-4252-4d2d-b6fb-f3a892ba6e00" alt="Testing Environment">
</p>

### The Process
The dummy is dropped from the air, and the system assesses potential injury by calculating the **ground impact speed** of each individual body part.

<p align="center">
  <img width="25%" src="https://github.com/lobsterglep/AI_project/assets/156586679/f5f28b3e-a7d7-4cb2-bf2e-09010941b6ec" alt="Process">
</p>

---

## Usage

1. **Install ML-Agents Release 20**: 
   Follow the official [installation guidance](https://github.com/Unity-Technologies/ml-agents/blob/release_20_post/docs/Installation.md).
2. **Setup Unity Editor**: 
   Ensure the ML-Agents package is correctly installed within the Unity Editor.
3. **Run Project**: 
   Open the project files with Unity Editor 2022.3.21f1 and begin the simulation.

---

## Experiment Results

We conducted experiments under different AI behavioral scenarios to observe how the dummy prioritizes protection:

### Scenario: "Trunk Heavy"
**Goal**: The dummy attempts to protect its trunk (torso) during the fall.

<p align="left">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/eb4a4f44-cbce-43c7-a3ce-c391a8a1af99">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/639c4394-b5ae-4b98-89c9-33a7d87a1421">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/8d0500e8-c8ee-402c-ad7e-5443da276bf3">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/9e30af0f-4d24-4c88-a23a-5641175feccf">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/fb1fd48b-304d-40d9-9f73-be7947ccda53">
</p>

### Scenario: "Head and Feet Heavy"
**Goal**: The dummy attempts to prioritize the protection of its head and feet.

<p align="left">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/ff5bb7ca-b463-44f2-b8b7-1465089a0d8b">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/08f4146e-b2e5-4076-aa62-c45dd52c3b27">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/c3ffc78f-559d-4634-a450-c25568487fdc">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/c326a2a7-e30b-402b-9dca-04c96c16219f">
  <img width="18%" src="https://github.com/lobsterglep/AI_project/assets/156586679/bdf8edbe-3349-431f-8a89-8e1d7907769f">
</p>
