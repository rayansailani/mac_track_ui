# Mac Trackpad Remote Client

This is a simple web-based client that allows you to use your phone or tablet as a remote trackpad for your Mac. It connects to a WebSocket server running on your Mac and sends touch gestures (move, click, right-click, scroll) to control the mouse remotely.

## Features

- Connect to your Mac via WebSocket (e.g., `ws://your-mac-ip:9000`)
- Use your device's touchscreen as a trackpad
- Single-finger move and tap for left-click
- Two-finger tap for right-click
- Two-finger scroll

## Usage

1. Make sure your Mac is running a compatible WebSocket server that can receive and interpret the gesture commands.
2. Open `index.html` on your phone or tablet (you can serve it locally or open directly).
3. Enter your Mac's IP address and port (e.g., `ws://192.168.1.10:9000`) in the input field.
4. Tap **Connect**.
5. Use the large area as a trackpad to control your Mac.

**Note:** Your Mac and your device must be on the same Wi-Fi network.

## License

MIT License
