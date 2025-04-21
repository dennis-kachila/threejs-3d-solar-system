# Three.js 3D Solar System

This project is a simple 3D solar system visualization built using Three.js, a popular JavaScript 3D library. It displays the sun, planets, and their orbits in a web browser.

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

## Dependencies

- Three.js (included via CDN or local files in `index.html`)

## Notes

- If you encounter any issues with loading resources, make sure you are running the project through a local server and not directly opening the HTML file in the browser.
