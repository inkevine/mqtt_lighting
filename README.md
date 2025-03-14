# mqtt_lighting
Allow switching on and off of light using mqtt

**Overview**

This project is a web-based light control system that uses MQTT protocol to turn a living room light ON, OFF, or set it to DIM mode. The interface provides a realistic lighting effect and a modern, sleek design for easy interaction.

**Features**

MQTT Integration: Uses MQTT over WebSockets to send commands.

Interactive UI: Buttons for controlling light states with smooth transitions.

Realistic Lamp Effect: Visual feedback for ON, OFF, and DIM states.

Live Status Update: Displays real-time status of the sent commands.

Modern UI Design: Responsive and visually appealing interface.

**Technologies Used**

HTML: Structure of the web page.

CSS: Styling, animations, and responsive design.

JavaScript: Handles MQTT communication and UI interactions.

MQTT.js: Library for MQTT communication.

**How It Works**

The page connects to a public MQTT broker (Mosquitto) via WebSockets.

Users can click buttons to send ON, OFF, or DIM commands.

Commands are published to an MQTT topic: /student_group/light_control.

The UI updates dynamically with lamp effects and status messages.

Setup Instructions

Prerequisites

A web browser (Chrome, Firefox, Edge, etc.).

Internet connection to access the MQTT broker.

**Steps to Run**

Download or copy the provided index.html file.

Open the file in a web browser.

Click on the buttons to control the lamp.

MQTT Configuration

Broker URL: wss://test.mosquitto.org:8081

Topic: /student_group/light_control

**Commands:**

ON: Turns the light on

OFF: Turns the light off

DIM: Sets the light to dim mode

**Future Enhancements**

Integrate with a real IoT smart bulb.

Add user authentication for secure access.

Implement real-time feedback from the MQTT subscriber.

**License**

This project is open-source and free to use for learning and development purposes.
