# 🌐 NetLab — Advanced Network Topology Simulator

An interactive, web-based **Network Topology Simulator** developed using HTML, CSS, and JavaScript. NetLab helps students understand computer networking concepts by creating network topologies, connecting devices, configuring IP addresses, and visually simulating packet transmission.

🔗 **Live Demo:** https://aman-tech-collab.github.io/Network-Topology-Simulator/

## 📌 About the Project

NetLab is an educational project designed to make computer networking easier to understand through interactive visualization. Users can build different network topologies, manage virtual network devices, test connections, and observe simulated packet movement.

The project provides a simple, responsive interface suitable for students learning Computer Networks.

## ✨ Features

- **Multiple Topologies:** Star, Bus, Ring, Mesh, Tree, and Custom topology.
- **Device Management:** Add Computer, Server, Switch, and Router devices.
- **Interactive Network Canvas:** Drag and reposition devices visually.
- **Connection Management:** Create, disable, enable, and remove network links.
- **IP Configuration:** Configure device names, IP addresses, subnet masks, and default gateways.
- **Packet Simulation:** Select source and destination devices and visualize packet movement.
- **Ping Simulation:** Test simulated network reachability.
- **Network Failure Testing:** Disable links and observe how connectivity changes.
- **Live Dashboard:** View device counts, connections, packets sent, and delivery rate.
- **Activity Log:** Track simulation events and network changes.
- **Dark Mode:** Switch between light and dark themes.
- **Save and Load:** Export and restore network configurations using JSON files.
- **Export Diagram:** Download the network diagram as a PNG image.
- **Responsive Design:** Works on desktop and mobile screens.

## 🛠️ Technologies Used

- **HTML5** — Structure of the application.
- **CSS3** — Styling, responsive layout, and dark mode.
- **JavaScript** — Device management, topology logic, validation, routing, and packet animation.
- **SVG (Scalable Vector Graphics)** — Visual representation of network devices and connections.
- **Breadth-First Search (BFS)** — Finding routes through active network connections.
- **GitHub Pages** — Hosting the live website.

## 🖥️ Supported Network Devices

| Device | Purpose |
|---|---|
| Computer (PC) | Represents an end device |
| Server | Represents a service-hosting device |
| Switch | Represents a device connecting nodes in a LAN |
| Router | Represents a device used to connect IP networks |

## 🔄 How to Use

1. Open the [NetLab Live Demo](https://aman-tech-collab.github.io/Network-Topology-Simulator/).
2. Select a network topology.
3. Add computers, servers, switches, or routers.
4. Drag devices to arrange them on the network canvas.
5. Select two devices and create a connection.
6. Select a device to configure its name and IP settings.
7. Choose the source and destination devices.
8. Click **Send Packet** to observe the simulated packet route.
9. Disable a connection to test how network connectivity changes.
10. Save your network as JSON or export the diagram as PNG.

## 📂 Project Structure

```text
Network-Topology-Simulator/
├── index.html
├── style.css
├── script.js
└── README.md
```

- `index.html` — Application structure and interface.
- `style.css` — Styling and responsive design.
- `script.js` — Network simulation and interactive functionality.
- `README.md` — Project documentation.

## 🚀 Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/AMAN-tech-collab/Network-Topology-Simulator.git
   ```

2. Open the project folder:

   ```bash
   cd Network-Topology-Simulator
   ```

3. Open `index.html` in your browser, or use the Live Server extension in Visual Studio Code.

No backend, database, or package installation is required.

## 🧠 Concepts Demonstrated

- Computer network topologies
- Network nodes and links
- IPv4 address configuration
- Graph representation of networks
- Breadth-First Search (BFS)
- Source-to-destination routing
- Network connectivity and failure testing
- Interactive SVG visualization

## ⚠️ Limitations

This project is an educational frontend simulation. It does not transmit actual network packets, perform real ICMP ping operations, or configure physical routers and switches. Routing and connectivity results are calculated within the browser using simplified simulation logic.

## 🔮 Future Enhancements

- More advanced subnetting and IP validation
- Improved router and gateway simulation
- Step-by-step packet inspection
- Additional networking protocol demonstrations
- Custom topology templates
- Enhanced network diagnostics and reports

## 👨‍💻 Author

**Aman Kumar**

Computer Science and Technology Student

GitHub: [AMAN-tech-collab](https://github.com/AMAN-tech-collab)

## 📄 License

This project is intended for educational and learning purposes. Add an open-source license if you want others to reuse and distribute the code under defined terms.

---

⭐ If you find this project useful, consider giving the repository a star!
