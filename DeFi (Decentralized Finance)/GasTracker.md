# GasTracker: Real-Time Gas Price Widget

## Project Description
GasTracker is a lightweight widget designed to track and display real-time Ethereum gas prices. The widget can be integrated into a web application or used as a browser extension, providing users with up-to-date gas price information to help them make informed transaction decisions.

## Features
- **Real-Time Gas Prices**: Continuously retrieves and displays the current gas prices on the Ethereum network.
- **Web Application Integration**: Easily integrates into any web application to provide gas price data.
- **Browser Extension**: Can be used as a browser extension for quick access to gas prices.
- **User-Friendly Interface**: Simple and intuitive design for ease of use.

## Skills Demonstrated
- **Data Retrieval from APIs**: Fetching real-time data from gas price APIs.
- **Front-End Development**: Developing a user-friendly interface to display the gas prices.
- **Real-Time Updates**: Implementing real-time updates to ensure the data is always current.
- **Browser Extension Development**: Creating a browser extension for quick and easy access to gas prices.

## Security Focus
GasTracker emphasizes the importance of securely integrating with APIs and ensuring the integrity and accuracy of real-time data. Key security considerations include:
- **Secure API Integration**: Safeguarding API keys and ensuring secure communication with gas price APIs.
- **Data Integrity**: Ensuring the accuracy and integrity of the gas price data displayed to users.
- **Preventing Data Manipulation**: Implementing measures to prevent potential data manipulation or injection threats.

## Technology Stack
- **Front-End**: HTML, CSS, JavaScript, React
- **APIs**: Ethereum gas price APIs (e.g., EthGasStation, GasNow)
- **Browser Extension Development**: Chrome Extension API, Firefox Add-ons

## Getting Started
### Prerequisites
- Node.js
- npm or yarn
- Browser (Chrome or Firefox) for extension

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/gastracker.git
    cd gastracker
    ```
2. Install dependencies:
    ```bash
    npm install
    ```

### Running the Web Application
1. Start the development server:
    ```bash
    npm start
    ```
2. Open your browser and navigate to `http://localhost:3000`.

### Installing the Browser Extension
1. Build the extension:
    ```bash
    npm run build
    ```
2. Open your browser's extension management page:
    - **Chrome**: Go to `chrome://extensions/` and enable "Developer mode".
    - **Firefox**: Go to `about:debugging` and click on "This Firefox" or "This Nightly".
3. Load the extension:
    - **Chrome**: Click "Load unpacked" and select the `build` folder.
    - **Firefox**: Click "Load Temporary Add-on" and select the `build` folder.

## Usage
1. For the web application, visit the provided URL and view the real-time gas prices.
2. For the browser extension, click on the extension icon in your browser to view the gas prices.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, please contact [your email](mailto:youremail@example.com).

---

### Disclaimer
GasTracker is a project for educational and demonstration purposes. It is not intended for use in production environments. Always conduct your own research and consult with a professional before making any financial decisions.
