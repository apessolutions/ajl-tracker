# Device Information - Web Sample

This is a standalone HTML page that retrieves and displays the same device information parameters as the mobile app.

## Features

The page displays the following device information:

- **IP Address** - Fetched from ipify.org API
- **Screen Width** - Browser window width in pixels
- **Screen Height** - Browser window height in pixels
- **Pixel Ratio** - Device pixel ratio (retina/high-DPI displays)
- **Device Model** - Detected from user agent
- **Device Manufacturer** - Detected from user agent
- **OS Type** - Operating system type (Windows, macOS, iOS, Android, Linux)
- **OS Version** - Operating system version
- **Timezone** - User's timezone
- **Language** - Primary language code
- **Locale** - Full locale identifier
- **Memory** - Device memory (if available via navigator.deviceMemory API)

## Usage

1. Open `index.html` in any modern web browser
2. The page will automatically detect and display all device information
3. Screen dimensions update automatically when the browser window is resized

## Browser Compatibility

- Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- Memory information requires Chrome 63+ or browsers that support the Device Memory API
- IP address fetching requires an active internet connection

## Notes

- Device model and manufacturer detection is based on user agent parsing and may not be 100% accurate
- Memory information may show "N/A" in browsers that don't support the Device Memory API
- The page uses the same styling approach as the mobile app for consistency