---

# Dynamic Traffic Signal Optimization Utilizing Real-Time Lane Analysis with YOLO

## Project Overview
This project addresses urban traffic congestion through an **Intelligent Traffic Regulation System** that dynamically optimizes traffic signals based on real-time lane-specific vehicle density analysis. The system leverages the **YOLO (You Only Look Once)** object detection framework to monitor traffic and adjust signal durations at intersections, enhancing overall traffic flow, reducing congestion, and improving road safety.

## Objectives
- Real-time traffic monitoring and vehicle density estimation at intersections using YOLO.
- Dynamic adjustment of traffic signal durations based on lane-specific vehicle density.
- Reduction in congestion and delays at urban intersections.
- Enhanced fuel efficiency and reduction in emissions through optimized traffic flow.
- Prioritization of emergency vehicles to ensure timely response.

## Key Features
- **YOLO Framework**: Real-time object detection and classification of vehicles (cars, buses, bicycles, etc.).
- **Dynamic Signal Control**: Adaptive adjustment of signal durations based on live traffic conditions.
- **Traffic Flow Analysis**: Continuous analysis of traffic patterns to improve efficiency.
- **Emergency Vehicle Detection**: Prioritization of emergency vehicles by granting them immediate right of way.
  
## Methodology
1. **Data Collection**: Real-time traffic data is captured using CCTV cameras at intersections.
2. **Vehicle Detection**: YOLO is used for lane-specific vehicle detection and counting.
3. **Signal Optimization**: The traffic signal timing is dynamically adjusted based on vehicle density, reducing congestion.
4. **Simulation**: The system is tested using real-time video feeds and traffic simulation models.

## Technologies Used
- **YOLOv4**: Used for real-time vehicle detection.
- **Python**: Main programming language for algorithm implementation.
- **Pygame**: Used for creating a traffic simulation environment.
- **Google Colab**: For model training and evaluation.
- **Datasets**: The project uses real-time video feeds for vehicle detection and traffic simulation.

## Results
- **Precision**: 92% accuracy in vehicle detection and classification.
- **Congestion Reduction**: Significant reduction in congestion and travel delays.
- **Emergency Response**: Improved response times for emergency vehicles by dynamically adjusting signals.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/dynamic-traffic-optimization.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the simulation:
   ```bash
   python traffic_simulation.py
   ```

## Usage
- Run the YOLO model for vehicle detection.
- Integrate real-time video feeds for traffic analysis.
- Adjust traffic signal durations dynamically using the optimization algorithm.

## Contributors
- **Aman Kumar**
- **Naman Chauhan**
- Project supervised by **Dr. Sindhu Ravindran**

## License
This project is licensed under the MIT License.

---
