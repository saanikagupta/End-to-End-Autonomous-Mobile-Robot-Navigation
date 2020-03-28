## End-to-End-Autonomous-Mobile-Robot-Navigation
- Developed a 1D CNN model for end-to-end autonomous mobile robot navigation.
- Keras functional API was used for building this non-sequential model
- Achieved an accuracy of 88.3%.
- The model predicted steering commands (left, right, front) from laser sensor data (received from LiDAR) and goal information.
- The dataset was manually generated using Gazebo simulator.
- Performed oversampling for handling class imbalance problem.

### Prerequisites
- Python 3
- Keras 2.2.4
- Tensorflow 1.14.0
- Numpy 1.16.4
- Pandas 0.24.2

### Reference
Mark Pfeiffer, Michael Schaeuble, Juan Nieto, Roland Siegwart, Cesar Cadena. [From Perception to Decision: A Data-driven Approach to End-to-end Motion Planning for Autonomous Ground Robots](https://arxiv.org/abs/1609.07910)
