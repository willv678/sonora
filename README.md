# Sonora 🎵

**Sonora** is a sleek music visualization and playback app that combines cutting-edge technology with an interactive interface. Built using **C++** and **Qt**, Sonora integrates real-time audio visualizations, Spotify playback data, and intuitive hand gesture controls to deliver an immersive music experience.

---

## Features 🚀
- **Dynamic Visualizations**: GPU-accelerated, real-time audio visualizations powered by OpenGL.
- **Spotify Integration**: Displays "Now Playing" info, including album art, track title, artist, and playback progress.
- **Hand Gesture Controls**: Use gestures to control playback, adjust volume, and tweak EQ settings with OpenCV.
- **Customizable UI**: Choose from multiple visualizer styles, themes, and sensitivity settings.
- **Standalone Deployment**: Designed to run on a Raspberry Pi or as a desktop app for a wall-mounted music hub.

---

## Stack 🛠️
- **C++**: Core application logic.
- **Qt**: For building the GUI and integrating OpenGL.
- **OpenGL**: For high-performance, real-time visualizations.
- **OpenCV**: For hand gesture recognition.
- **Spotify Web API**: For retrieving "Now Playing" data.

---

## Getting Started 📦

### Prerequisites
1. Install **Qt Framework**:
   - [Download here](https://www.qt.io/download)
2. Install dependencies:
   - OpenGL
   - OpenCV
   - Spotify API client library (e.g., cURL for HTTP calls)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/willv678/sonora.git
   cd sonora
