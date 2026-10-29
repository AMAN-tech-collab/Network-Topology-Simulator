# NetLab — Advanced Network Topology Simulator

Created by Aman Kumar.

## Features
- Star, Bus, Ring, Mesh, Tree, and Custom topology modes
- Add Computer, Server, Switch, and Router nodes
- Drag devices around the SVG canvas
- Create connections and click links to enable/disable them
- Device configuration: name, IPv4 address, subnet mask, default gateway
- Basic IPv4 validation and duplicate IP detection
- Animated packet/ping simulation using BFS route search
- Delivery statistics and activity log
- Dark/light mode
- Save/load topology JSON and export the diagram as PNG
- Responsive design

## Run
Open `index.html` in a modern browser, or open the folder in VS Code and use Live Server. No installation or backend is required.

## Important limitations
This is an educational simulation. It does not transmit real IP packets, perform actual ICMP ping, or configure physical routers/switches. Subnet checks are intentionally simplified for learning.

## Files
- `index.html` — app structure
- `style.css` — responsive UI and themes
- `script.js` — topology, device, link, validation, route and animation logic
