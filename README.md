AgroBot-AI
Autonomous agricultural robot using AI to detect plant disease and optimize watering.
📖 Project Overview
AgroBot AI is an autonomous robot designed for smart farming. It combines computer vision, AI reasoning, and robotic control to monitor crop health, detect plant diseases, and water plants automatically.
The robot is intended for real-world farm environments and runs AI models on edge hardware, ensuring low latency, safety, and efficient irrigation. AgroBot helps farmers:
Increase crop yield
Reduce water waste
Detect plant disease early
Automate tedious farm tasks
⚙️ Features
Vision-Based Plant Monitoring: Uses camera and AI to identify diseased or unhealthy plants.
AI Decision Making: Determines which plants need attention using edge inference.
Automated Watering: Activates robot arm to water soil based on detected moisture levels.
Edge AI Pipeline: All processing happens locally on the robot for fast and reliable operation.
Hardware Verification: Supports real hardware demos using Raspberry Pi, sensors, and robotic arms.
🛠 Tech Stack
Hardware:
Raspberry Pi / Jetson Nano (edge AI)
Camera module
Robotic arm
Soil moisture sensor
Robot car chassis / mobile robot base
Software / AI:
ROS – Robot control framework
OpenCV – Image processing and detection
PyTorch – AI model training and inference
YOLOv8 – Real-time object detection
Vision-Language models – Interpreting commands (optional)
Development Tools:
Visual Studio Code
Ubuntu / Linux OS
GitHub for version control
📂 Repository Structure
Bash
AgroBot-AI/
│
├── perception/
│   └── plant_detection.py       # AI vision pipeline
├── reasoning/
│   └── command_interpreter.py   # Decision-making system
├── control/
│   └── robot_controller.py      # Robot arm & movement control
├── hardware/
│   └── sensor_interface.py      # Soil moisture & sensors
├── demo/
│   └── demo_video.mp4           # Prototype / concept demo
├── docs/
│   └── system_architecture.md   # Architecture diagram and explanations
└── README.md                    # This file
🎥 Demo
Prototype Video:
Even without physical hardware, you can create a simulation or concept demo showing:
Robot detecting diseased leaves
AI decision-making pipeline
Robot watering plants
Soil moisture confirmation
Example overlay text: “Disease Detected: Tomato Blight” and “Moisture Level: Optimal.”
📊 Evaluation Metrics
Metric
Target
Disease detection accuracy
≥ 90%
Task completion rate
≥ 85%
Response time
< 2 seconds
Water efficiency
Optimized based on soil moisture
🏗 System Architecture
Pipeline Overview:
Text
Camera → OpenCV → AI Detection (YOLO/PyTorch) → Decision Engine → Robot Controller → Watering / Action
Perception Layer: Camera + sensors detect plant health
Reasoning Layer: AI interprets commands and decides actions
Action Layer: Robot moves or waters plants
📌 How to Run (Prototype)
Clone the repo:
Bash
git clone https://github.com/ryan-del-lab
/AgroBot-AI.git
cd AgroBot-AI
Install dependencies:
Bash
pip install -r requirements.txt
Run AI detection (simulation):
Bash
python perception/plant_detection.py
Run control pipeline:
Bash
python control/robot_controller.py
📷 Hardware Verification
Include:
Photos of robot hardware (optional if simulated)
Video of prototype or simulation running
Wiring diagram for sensors and robot arm
🏆 Contribution / Submission Notes
This project is a prototype demonstration. Hardware implementation is planned using embedded robotics hardware. The demo shows AI pipeline and robot actions in a simulated or concept environment.
🔗 Links
GitHub: https://github.com/ryan-del-lab/AgroBot-AI⁠�
Demo Video: https://www.reddit.com/r/agi/s/B258UnBpdz
