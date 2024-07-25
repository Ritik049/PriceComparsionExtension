# Product Comparison Chrome Extension

## Overview
The Product Search Chrome Extension allows users to search for products on Amazon, Flipkart, and eBay directly from their browser. It fetches real-time product data from these e-commerce sites and displays them in a popup window within the extension.

## Features
- **Multi-Site Search**: Search for products simultaneously on Amazon, Flipkart, and eBay.
- **Real-Time Data**: Fetches product information dynamically using web scraping techniques.
- **User Interface**: Provides a simple and intuitive UI within the extension popup for entering search queries and viewing results.

## Installation
To install the extension, follow these steps:
1. Download or clone the repository to your local machine.
2. Open Chrome browser and navigate to `chrome://extensions/`.
3. Enable Developer Mode by toggling the switch in the top right corner.
4. Click on "Load unpacked" and select the directory where you cloned/downloaded the extension.

## Usage
1. Click on the extension icon in the Chrome toolbar to open the popup.
2. Enter a product name in the search box and press Enter or click the Search button.
3. Results from Amazon, Flipkart, and eBay will be displayed in separate sections within the popup.

## How It Works
- **PopUp Script**: Injected into Amazon, Flipkart, and eBay pages to fetch HTML data.
- **Background Script**: Handles message passing between content scripts and popup.
- **Popup**: Provides UI for user interaction and displays fetched product data.

## Technologies Used
- JavaScript
- Chrome Extension APIs
- DOM manipulation (DOMParser)
- HTTP requests (fetch API)

## Contributing
Contributions are welcome! Here's how you can contribute:
- Fork the repository.
- Create a new branch (`git checkout -b feature/your-feature`).
- Commit your changes (`git commit -am 'Add some feature'`).
- Push to the branch (`git push origin feature/your-feature`).
- Create a new Pull Request.

## License
This project is licensed under the [MIT License](LICENSE).


---

Feel free to customize the sections and add more details specific to your project as needed. This README file will help users understand your extension, how to install and use it, and how they can contribute to its development.
