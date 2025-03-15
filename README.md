# Sign Language Tracking Project

This project uses MediaPipe for hand tracking and sign language recognition.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Run the application using one of the following methods:

### Method 1: Using Vite (Recommended)
```bash
npm run dev
```
Then open your browser and navigate to http://localhost:3001

### Method 2: Using Express Server
```bash
npm run express
```
Then open your browser and navigate to http://localhost:3001

## Project Structure

- `front.html`: The main application interface with hand tracking functionality
- `index.html`: Redirects to front.html
- `vite.config.js`: Configuration for the Vite development server
- `server.js`: Simple Express server for serving the application
- `opencvtest.py` and `opencvhandtest.py`: Python scripts for hand tracking using OpenCV

## Troubleshooting

If you encounter issues with the local server:

1. Make sure all dependencies are installed:
```bash
npm install
```

2. Check if port 3001 is already in use by another application. If so, you can change the port in both `vite.config.js` and `server.js`.

3. Try running the application using the alternative method (Vite or Express).

4. Check the browser console for any JavaScript errors.
