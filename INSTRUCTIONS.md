# GaussianSplats3D Viewer Instructions

## Running the Viewer
1. Navigate to the GaussianSplats3D directory:
   ```
   cd C:\!Experiments\!splat2\GaussianSplats3D
   ```

2. Start the demo server:
   ```
   npm run demo
   ```

3. Open a web browser and go to:
   ```
   http://127.0.0.1:8080/index.html
   ```

## Controls
### Mouse
- Left click to set the focal point
- Left click and drag to orbit around the focal point
- Right click and drag to pan the camera and focal point

### Keyboard
- `C` - Toggles the mesh cursor, showing the intersection point of a mouse-projected ray and the splat mesh
- `I` - Toggles an info panel showing debugging info (camera position, FPS, etc.)
- `U` - Toggles a debug object showing the orientation of the camera controls
- `Left/Right arrow` - Rotate the camera's up vector
- `P` - Toggle point-cloud mode, where each splat is rendered as a filled circle
- `=` - Increase splat scale
- `-` - Decrease splat scale
- `O` - Toggle orthographic mode

## Available Demo Scenes
- Bonsai
- Garden
- Stump 
- Truck

## Troubleshooting
If you encounter issues:
1. Make sure you're running the commands from the GaussianSplats3D directory
2. Ensure all sample data files are extracted to `build/demo/assets/data`
3. Check that the server is running (you should see output in the terminal) 