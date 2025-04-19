# CNN_Video_Surveillance

A deep learning-based system for detecting abnormal events (violence, theft, etc.) in surveillance videos using 3D convolutional autoencoders.

## 📌 Table of Contents
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Dataset](#-dataset)
- [Model Architecture](#-model-architecture)
- [Results](#-results)
- [Contributing](#-contributing)
- [License](#-license)
- [Citation](#-citation)

## ✨ Features
- Real-time anomaly detection in video streams
- 3D CNN autoencoder for spatio-temporal feature learning
- Customizable detection threshold
- Supports CUHK Avenue and UCSD Pedestrian datasets
- GPU acceleration support

## 🛠 Installation

```bash
# Clone repository
git clone https://github.com/yourusername/video-surveillance-anomaly-detection.git
cd video-surveillance-anomaly-detection

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/MacOS
venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt
