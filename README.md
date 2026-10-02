# Predictive-Logistics-Command-system
Autonomous supply chain forecasting and dynamic convoy rerouting platform built for Indian Army high altitude forward posts.

This platform addresses high-altitude logistics challenges by integrating IoT telemetry, GIS spatial mapping, and predictive demand analytics to give command centers real-time supply visibility and automated rerouting alerts.

## Key Features
- **AI Demand forecasting engine:** 14-day supply depletion predictions across Ammunition, Fuel, and Rations.
- **IoT Forward Post Depot Telemetry:** Stock level, reserve days and temperature tracking per post.
- **Tactical GIS Route Map:** Interactive supply route mapping with status indicators using geographic information system Route map.
- **Dynamic Convoy Dispatcher:** weather blockage detection with automated aerial drop protocols.

## Tech Stack
- **UI Framework:** HTML5, CSS3, Tailwind CSS
- **Interactive Mapping:** Leaflet.js
- **Data Analytics & Charts:** Chart.js
- **Iconography:** FontAwesome 6

**Live demo:** [https://elaborate-frangipane-755427.netlify.app/](https://elaborate-frangipane-755427.netlify.app/)

**Note:** This is a prototype. All stock levels, sensor readings and alerts are simulated to demonstrate the workflow.

## Future Scope

- Real sensor and weather API integration
- Trained ML forecasting model
- Convoy GPS live tracking
- Offline / low-bandwidth mode

### How access would work in real deployment

If this system is developed fully the following will be created,for now this platform is just a prototype to show our idea.

- **Role-based access:** for example, a Command Officer with full control, supply officers with their own sector, and read-only viewers for senior staff. The prototype's single "Maj. A. Sharma" operator card represents one such user.
- **Server-side authentication:** secure login (with multi-factor authentication) handled by a backend, not by page code.
- **Approval workflow:** actions such as Reroute / Air Drop would be sent as requests to be approved by an authorised officer, not carried out instantly.
- **Audit trail:** every action recorded with the user's identity and time, extending the current Operations Log.
- **Secure hosting:** deployment on a government-controlled or approved network, with encrypted communication and no public internet exposure.
- **Data integration:** real feeds from depot sensors, weather and road services, and convoy tracking, all kept inside the secure environment.

