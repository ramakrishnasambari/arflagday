# Gandhi AR Experience

An interactive augmented reality experience featuring Mahatma Gandhi using Google Model Viewer.

## Features

- **3D Model Viewer**: Interactive 3D model of Mahatma Gandhi
- **AR Support**: View the model in your real-world space
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Beautiful, intuitive interface
- **Educational Content**: Information about Gandhi's legacy

## How to Use

### Desktop Experience
1. Open `index.html` in a modern web browser
2. Use mouse to rotate and zoom the 3D model
3. The model will auto-rotate for better viewing

### Mobile AR Experience
1. Open the webpage on an AR-capable mobile device
2. Click the "👁️ View in AR" button
3. Point your camera at a flat surface
4. Tap to place the Gandhi model in your space
5. Walk around and interact with the 3D model

## Technical Requirements

- **Browser**: Chrome, Safari, Firefox, or Edge (latest versions)
- **Mobile**: iOS 12+ or Android 8+ with ARCore support
- **Internet**: Required for loading Google Model Viewer library

## AR Compatibility

### iOS Devices
- iPhone 6s and newer
- iPad (5th generation) and newer
- Requires iOS 12 or later

### Android Devices
- ARCore supported devices
- Android 8.0 or later
- Google Play Services for AR

## File Structure

```
flagday/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── gandhi.glb          # 3D model file
└── README.md           # This file
```

## Features Explained

### Model Viewer Attributes
- `ar`: Enables AR functionality
- `ar-modes`: Supports WebXR, Scene Viewer, and Quick Look
- `camera-controls`: Allows user interaction
- `auto-rotate`: Automatic model rotation
- `shadow-intensity`: Adds realistic shadows
- `ar-placement="floor"`: Places model on detected surfaces

### AR Modes
- **WebXR**: Modern web-based AR (Chrome, Firefox)
- **Scene Viewer**: Android AR experience
- **Quick Look**: iOS AR experience

## Troubleshooting

### Model Not Loading
- Ensure `gandhi.glb` file is in the same directory as `index.html`
- Check internet connection for Model Viewer library
- Try refreshing the page

### AR Not Working
- Verify device compatibility
- Ensure camera permissions are granted
- Try on a different surface or location
- Check if AR services are enabled on your device

### Performance Issues
- Close other applications to free up memory
- Ensure good lighting conditions for AR
- Try on a device with better specifications

## Development

This project uses:
- **Google Model Viewer**: For 3D model rendering and AR
- **HTML5**: For structure
- **CSS3**: For styling and responsive design
- **GLB Format**: For 3D model (efficient binary format)

## Browser Support

- ✅ Chrome 79+
- ✅ Safari 13.1+
- ✅ Firefox 79+
- ✅ Edge 79+

## License

This project is for educational and demonstration purposes.

---

*Experience the legacy of peace and non-violence through modern AR technology.*
