# AutoSteer

AutoSteer is an advanced autonomous vehicle steering control system designed to ensure precise lane positioning on highways. By leveraging state-of-the-art computer vision techniques and robust control algorithms, AutoSteer dynamically adjusts the vehicle's steering to maintain safe and efficient lane keeping.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview

AutoSteer is designed for developers and researchers in the field of autonomous driving who are interested in implementing a reliable lane-keeping assist system. The system processes real-time video inputs to detect lane markings and computes the optimal steering angle to keep the vehicle centered in its lane. AutoSteer is modular and can be integrated with other autonomous driving systems.

## Key Features

- **Accurate Lane Detection**: Utilizes advanced computer vision algorithms to detect and track lane markings under various lighting and weather conditions.
- **Real-time Steering Control**: Continuously calculates and adjusts the steering angle based on lane position, ensuring smooth and stable driving.
- **Adaptability**: Easily configurable to work with different types of vehicles and environments, with customizable parameters for fine-tuning.
- **Extensible Framework**: Designed with modularity in mind, allowing for easy integration of additional sensors and control systems.

## Installation

Follow these steps to set up and run AutoSteer:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Shubhisingh921/AutoSteer.git
   cd AutoSteer
   ```

2. **Set Up the Environment**:
   Ensure that you have Python 3.x installed. It is recommended to create a virtual environment:
   ```bash
   python -m venv autosteer-env
   source autosteer-env/bin/activate   # On Windows, use `autosteer-env\Scripts\activate`
   ```

3. **Install Dependencies**:
   Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Quick Start

To quickly get started with AutoSteer:

1. **Run the Main Script**:
   Start the AutoSteer system by running:
   ```bash
   python main.py
   ```

2. **Feed Video Input**:
   Ensure your video feed is connected. AutoSteer will begin processing the input to detect lanes and adjust steering in real time.

3. **View Outputs**:
   Watch as the system detects lanes and outputs the calculated steering angles. You can visualize the results in real-time or review saved logs for analysis.

## Configuration

AutoSteer comes with a configuration file (`config.yaml`) that allows you to customize various aspects of the system:

- **Lane Detection Sensitivity**: Adjust the sensitivity of the lane detection algorithm.
- **Steering Control Parameters**: Fine-tune the PID controller parameters for steering.
- **Video Input Settings**: Configure the source and resolution of the video input.

To modify these settings, open the `config.yaml` file in a text editor and adjust the parameters as needed.

## Dependencies

AutoSteer relies on the following libraries:

- [Python 3.x](https://www.python.org/downloads/)
- [OpenCV](https://opencv.org/) - For video processing and computer vision tasks.
- [NumPy](https://numpy.org/) - For numerical computations.
- [Matplotlib](https://matplotlib.org/) - For plotting and visualization.
- [SciPy](https://www.scipy.org/) - For scientific computing.
- Other dependencies specified in the `requirements.txt`.

## Contributing

We welcome contributions to improve AutoSteer! Whether you're fixing bugs, adding new features, or improving documentation, your help is appreciated. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push your branch to your forked repository.
4. Submit a pull request to the main repository.

For more detailed guidelines, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

