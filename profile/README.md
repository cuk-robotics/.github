# CUK Robotics

**CUK Robotics** is a student robotics team at CUK working on  
**Vision-Language-Action (VLA)** models and **bimanual robotic manipulation**.

We are currently developing a dual-arm robotic manipulation system as part of our **2026 Capstone Design Project**.

---

## 🤖 Current Project

### Bimanual Manipulation with SmolVLA

Our project explores a bimanual robotic system using **two SO-101 robot arms** and **SmolVLA**.

The system receives natural-language instructions and multimodal observations to perform multi-step manipulation tasks.

Our current task is beverage preparation, which requires the robot to:

1. Pick up a cup
2. Select the requested powder
3. Pour the powder into the cup
4. Pick up a beaker and pour water
5. Pick up a muddler and stir the beverage
6. Return the objects and robot arms to their original positions

---

## 🦾 Hardware

- 2× SO-101 robot arms
- 2× modified grippers
- 2× wrist/gripper cameras
- 1× top-view camera

---

## 👁️ Multimodal Inputs

The VLA policy receives:

- Speech-recognized natural-language instructions
- Left wrist camera image
- Right wrist camera image
- Top-view camera image
- Left robot arm state
- Right robot arm state
- Gripper states

The overall system can be summarized as:

> **Text Instruction + 3-Camera Vision + Dual-Arm Robot State → SmolVLA → Bimanual Robot Actions**

---

## 🧠 Robot Learning

We use **SmolVLA** as the Vision-Language-Action policy for learning manipulation behaviors from demonstrations.

The project focuses on:

- Bimanual robotic manipulation
- Vision-Language-Action models
- Multimodal robot learning
- Imitation learning
- Multi-view visual observations
- Language-conditioned manipulation
- Long-horizon manipulation tasks

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face LeRobot
- SmolVLA
- SO-101
- Multi-camera vision
- Speech recognition

---

## 🎯 Project Goals

Our main goals are to:

- Build a reliable dual-arm manipulation system using two SO-101 robots
- Integrate language, visual observations, and robot states into a VLA pipeline
- Collect multimodal demonstrations for bimanual manipulation
- Train and evaluate SmolVLA on multi-step manipulation tasks
- Analyze task-level and subtask-level success rates
- Develop a reproducible pipeline from data collection to model deployment

---

## 📂 Project Structure

Our repositories will contain code and documentation for:

- Robot control
- Teleoperation and demonstration collection
- Multi-camera data acquisition
- Speech instruction processing
- Dataset management
- SmolVLA training
- Inference and deployment
- Task evaluation and experiments

---

## 📊 Evaluation

The system will be evaluated using both overall task success and individual subtask success rates.

Example subtasks include:

- Correct powder selection
- Powder pouring
- Water pouring
- Stirring
- Object return
- Full-task completion

---

**2026 Capstone Design Project · CUK Robotics**
