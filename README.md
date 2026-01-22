# 🚗 Uber Clone - Frontend Clone Project

A modern, responsive, and interactive **Uber UI Clone** built using pure web technologies. This project focuses on replicating the core user experience of the Uber web/mobile interface, including location searching and car selection.

---

## 🌟 Features

* **Responsive Design:** Fully optimized for mobile, tablet, and desktop screens.
* **Interactive Maps:** Integrated Google Maps API to provide a real-time map view.
* **Location Autocomplete:** Uses Google Places API for real-time pickup and drop-off suggestions.
* **Dynamic Fare Calculation:** Simulated logic to calculate estimated fares based on ride types (UberX, UberXL, etc.).
* **Sleek UI/UX:** Clean CSS animations and transitions for a premium look and feel.

## 🛠 Tech Stack

* **HTML5:** For semantic structure and layout.
* **CSS3:** Custom styling, Flexbox, and Grid for a responsive layout.
* **JavaScript (ES6):** For DOM manipulation, API integration, and event handling.
* **Google Maps API:** For map rendering and place search functionality.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites
* A modern web browser (Chrome, Firefox, Edge).
* A text editor (VS Code is recommended).
* A Google Cloud API Key (Optional, for the Map features to work).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/uber-clone.git](https://github.com/your-username/uber-clone.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd uber-clone
    ```

3.  **Setup your API Key:**
    Open `index.html` and find the script tag for Google Maps. Replace `YOUR_API_KEY` with your actual key:
    ```html
    <script src="[https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places](https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places)"></script>
    ```

4.  **Run the project:**
    Simply open `index.html` in your browser, or use the **Live Server** extension in VS Code.

## 📂 Folder Structure
```text
├── index.html       # The main entry point
├── style.css        # All styling and layouts
├── script.js        # Logic for Maps and UI interactions
└── assets/          # Images, car icons, and logos
