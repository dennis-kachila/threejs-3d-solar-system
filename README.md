# Three.js 3D Solar System

This project is a realistic 3D solar system visualization built using Three.js, a popular JavaScript 3D library. It displays the sun, all eight planets of our solar system with their names, and a beautiful starfield background.

## Features

- Complete solar system with the Sun and all 8 planets (Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune)
- Planet names displayed as labels next to each planet
- Realistic planetary orbits with different speeds
- Dynamic stars with varying brightness in the background
- Interactive navigation using keyboard controls
- Responsive design that adapts to different screen sizes

## How to Run

Since this project consists of a single `index.html` file, it is recommended to serve it using a local HTTP server to avoid any CORS issues and ensure proper loading of resources.

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

## Dependencies

- Three.js (loaded via CDN in `index.html`)

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
- A debug panel is available in the top-left corner showing initialization progress

## Future Improvements

Potential enhancements for future versions:
- Add planetary rings for Saturn
- Implement moons for planets
- Add textures to planets for more realistic appearance
- Include orbital paths visualization
- Add information panel with planetary facts
