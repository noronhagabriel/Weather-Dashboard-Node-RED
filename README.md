# Weather-Dashboard-Node-RED

This project creates an interactive dashboard in Node-RED where users type a city name and click Search to view the current weather, temperature, and humidity, using data from the public OpenWeatherMap API.

🚀 Technologies Used
Node-RED

node-red-dashboard

OpenWeatherMap API

🧰 Requirements
Node.js installed

Node-RED installed

Free account at OpenWeatherMap to get an API key

⚙️ Installation and Usage
1. Clone the repository:

git clone https://github.com/noronhagabriel/Weather-Dashboard-Node-RED.git
cd your-repository


2. Install and start Node-RED:

npm install -g node-red
node-red
Open your browser and go to: http://localhost:1880


3. Install the Dashboard nodes in Node-RED
In the Node-RED menu:

☰ Menu > Manage palette > Install
Search for: node-red-dashboard and click Install


4. Import the flow
Click on the menu:

☰ Menu > Import > Clipboard
Paste the flow JSON (provided in this repo or from the example)

Click Import

Open the function node named "Build URL" or "Prepare URL" and replace 'YOUR_API_KEY_HERE' with your actual OpenWeatherMap API key

Click Deploy


5. Use the Dashboard
Open your browser to:

http://localhost:1880/ui
Type the city name in the input box, click the Search button, and the weather info will appear below.
