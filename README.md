# Three.js 3D Solar System

This project is a realistic 3D solar system visualization built using Three.js, a popular JavaScript 3D library. It displays the sun, all eight planets of our solar system with their names, and a beautiful starfield background.

## Features

- Complete solar system with the Sun and all 8 planets (Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune)
- High-resolution texture maps for all celestial bodies
- Detailed Saturn rings with realistic transparency effects
- Planet names displayed as labels next to each planet
- Realistic planetary orbits with different speeds
- Stunning Milky Way galaxy background
- Dynamic stars with varying brightness
- Interactive navigation using keyboard controls
- Responsive design that adapts to different screen sizes
- Advanced debug logging with file export capability

## How to Run

Since this project consists of a single `index.html` file and texture resources, it is recommended to serve it using a local HTTP server to avoid any CORS issues and ensure proper loading of resources.

### Using Python 3

If you have Python 3 installed, you can run a simple HTTP server with the following command in the project directory:

```bash
python3 -m http.server 8000
```

This will start a local server at [http://localhost:8000](http://localhost:8000).

### Viewing the Project

Open your web browser and navigate to:

```
http://localhost:8000
```

You should see the 3D solar system rendered in the browser.

## Controls

The solar system can be navigated using keyboard controls:

- **Arrow Left/Right**: Rotate the camera around the solar system
- **Arrow Up/Down**: Adjust the camera height (move up and down)
- **+ / -**: Zoom in and out

## Technical Details

- Built with Three.js version 0.153.0
- Uses HTML5 and CSS3 for layout and styling
- Implements custom keyboard navigation controls
- Dynamically positions planet labels in 3D space
- Features over 3000 stars with randomized brightness
- Realistic textures for all planets and the sun
- Auto-scrolling debug console with timestamp and log levels
- Saturn with textured ring system showing proper transparency
- Earth with proper 23.5° axial tilt

## Debugging Features

- Real-time debug panel with auto-scrolling capability
- Color-coded log messages (errors in red, warnings in yellow)
- Timestamped logs for easier troubleshooting
- Log export functionality to save debugging information
- Clear logs button to reset the debug panel
- Debug controls accessible from the interface

## Dependencies

- Three.js (loaded via CDN in `index.html`)

## Project Structure

```
index.html                       # Main application file
README.md                        # Project documentation
solar-system-log-[timestamp].txt # Auto-generated debug logs
textures/                        # Texture maps for celestial bodies
    2k_earth_daymap.jpg          # Earth texture
    2k_jupiter.jpg               # Jupiter texture
    2k_mars.jpg                  # Mars texture
    2k_neptune.jpg               # Neptune texture
    2k_saturn_ring_alpha.png     # Saturn rings texture with transparency
    2k_saturn.jpg                # Saturn texture
    2k_uranus.jpg                # Uranus texture
    2k_venus_surface.jpg         # Venus texture
    8k_mercury.jpg               # Mercury texture
    8k_stars_milky_way.jpg       # Milky Way background
    8k_sun.jpg                   # Sun texture
```

## Browser Compatibility

This project should work in all modern browsers that support WebGL, including:
- Chrome
- Firefox
- Safari
- Edge

## Notes

- If you encounter a blank screen, check your browser's JavaScript console for errors
- Make sure you are running the project through a local server and not directly opening the HTML file in the browser
- If OrbitControls don't load properly, the application will fall back to keyboard controls
- The debug panel in the top-left corner shows initialization progress and can be exported for troubleshooting

## Future Improvements

Potential enhancements for future versions:
- Add planetary moons, especially for Jupiter and Saturn
- Add cloud layers for planets with atmospheres
- Implement day/night cycles for Earth
- Add orbital path visualization
- Include information panel with planetary facts
- Add asteroid belt between Mars and Jupiter
