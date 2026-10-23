# Cassette Futurism System Operator UI Template

A responsive, offline browser UI template for the Cassette Futurism 'System Operator' interface with interactive controls and retro-futuristic design.

## Features

- **Responsive Design**: Works on both desktop and mobile devices
- **Interactive Controls**: Sliders, dropdowns, and buttons with real-time feedback
- **Offline SVG Artwork**: All graphics are inline SVG, no external dependencies
- **Retro-Futuristic Aesthetic**: Neon color scheme with scanline effect
- **Complete System Interface**: Power controls, frequency settings, and status monitoring

## Usage Instructions

1. Save the `index.html` file to your local machine
2. Open the file directly in any modern web browser (no server required)
3. Interact with the system controls:
   - Adjust power level using the slider
   - Select system mode from the dropdown
   - Click "ACTIVATE SYSTEM" to start the system
   - Adjust frequency and modulation settings
   - Use "CALIBRATE" to calibrate the system
   - Use "RESET SYSTEM" to return to default settings

## Testing

This template includes automated browser tests that verify core functionality:

1. **System Activation Test**: Clicks the activate button and verifies system status changes to "ACTIVE"
2. **Calibration Test**: Clicks the calibrate button and verifies system status changes to "CALIBRATING"

To run tests:
1. Open `index.html` in a browser that supports automated testing
2. The test runner will automatically execute the defined interaction scenarios
3. Verify all tests pass to confirm proper functionality

## Design Elements

- **Color Scheme**: Neon cyan (#00ffff), magenta (#ff00ff), yellow (#ffff00) on dark background
- **Typography**: Monospace font for authentic retro-futuristic feel
- **Animations**: Pulsing status lights and scanning effect
- **Layout**: Grid-based responsive panels that adapt to screen size

## Offline Compatibility

All assets are embedded within the single HTML file:
- CSS styles are inline
- SVG artwork is embedded directly in the HTML
- JavaScript is contained within the page
- No external resources or network requests required

The interface will function completely offline once saved locally.

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 10+
- Edge 16+

Works on both desktop and mobile browsers with touch support.

## Customization

To modify the interface:
1. Edit CSS variables in the `:root` section to change color scheme
2. Modify SVG elements directly for visual changes
3. Update JavaScript event handlers for additional functionality
4. Adjust grid layout in `.system-grid` for different panel arrangements

All modifications should be made within the single HTML file for offline compatibility.
