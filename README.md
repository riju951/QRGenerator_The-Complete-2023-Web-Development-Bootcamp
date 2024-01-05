# QRGenerator_The-Complete-2023-Web-Development-Bootcamp

# QR Code Generator

## About
QR Code Generator is a simple yet powerful Node.js application that enables users to generate QR code images from URLs. This project leverages various Node.js modules, including the built-in `fs` package and npm packages such as `inquirer` and `qr-image`, to facilitate the QR code generation process seamlessly.

## Key Features
- **URL-to-QR Code Conversion:** Converts user-provided URLs into corresponding QR code images.
- **User Input via Inquirer:** Utilizes the `inquirer` package to obtain user input in a user-friendly and interactive manner.
- **Efficient QR Code Generation:** Uses the `qr-image` package to swiftly generate QR code images based on the entered URLs.

  ![image](https://github.com/riju951/QRGenerator_The-Complete-2023-Web-Development-Bootcamp/assets/82694741/648b7a8d-c81e-45e6-91e3-220181eb9b1b)


## Getting Started
To run the project locally, follow these steps:

1. **Download Files:** Download the project files from the repository.

2. **Initialize npm:** Open your terminal or command prompt, navigate to the project directory, and run the following command to initialize npm.
   ```bash
   npm init -y
   ```

3. **Install Dependencies:** Use npm to install the required npm packages - `inquirer` and `qr-image`.
   ```bash
   npm install inquirer qr-image
   ```

4. **Run the Project:** Execute the `index.js` file using Node.js by running the following command:
   ```bash
   node index.js
   ```

5. **User Input:** Upon running the project, you'll be prompted to enter a URL. Input the desired URL and proceed.

6. **Generate QR Code:** After entering the URL, the application will generate a QR code image for the provided URL.

7. **View QR Image:** The generated QR code image will be available in the project directory.

## Usage
Run the project with Node.js and follow the instructions prompted in the terminal to create QR code images for different URLs.

## Technologies Used
- **Node.js:** JavaScript runtime environment for executing the application.
- **`fs` Package:** Built-in Node.js module for file system operations.
- **`inquirer` Package:** NPM package used for user input handling.
- **`qr-image` Package:** NPM package enabling the creation of QR code images.

## Usage
QR Code Generator simplifies the process of generating QR code images from URLs. Users can quickly generate QR codes for various web links, facilitating easy sharing or access through QR code scanning.

## Credits
This project was developed by drawing inspiration from "The Complete 2023 Web Development Bootcamp" instructed by Angela Yu. Enhancements and modifications can be made to adapt the application according to specific needs and preferences.


