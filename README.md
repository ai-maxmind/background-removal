# Real-time Background Removal & Replacement

A web application that uses MediaPipe Selfie Segmentation to remove and replace video backgrounds in real-time, similar to Zoom/Meet virtual backgrounds.

## Features

- 🎥 Real-time background segmentation
- 🌫️ Background blur effect
- 🖼️ Custom image background
- 🎬 Custom video background
- 📱 Mobile-friendly design
- ⚡ Low latency processing

## Technologies

- JavaScript (Vanilla)
- MediaPipe Selfie Segmentation
- HTML5 Canvas API
- WebRTC getUserMedia API

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/background-removal.git
cd background-removal
```

2. Open `index.html` in a web browser
   - Must be served from a web server (local or hosted)
   - HTTPS required for camera access

## Usage

1. Allow camera access when prompted
2. Use the control buttons to switch between modes:
   - Original: Shows unmodified camera feed
   - Blur: Applies background blur effect
   - Image: Uses custom image as background
   - Video: Uses custom video as background
3. Upload custom backgrounds using the file inputs

## Requirements

- Modern web browser with WebGL2 support
- Camera/webcam access
- Stable internet connection (for MediaPipe CDN)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
