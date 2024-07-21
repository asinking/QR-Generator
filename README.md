QR Code Generator
(*)Overview:-
The QR Code Generator is a simple Node.js application that allows users to create QR codes from URLs. The application prompts the user to enter a URL, generates a QR code for the given URL, and saves both the QR code image and the URL to local files. This tool leverages the inquirer library for interactive command-line prompts, qr-image for QR code generation, and fs for file system operations.

(*)Features:-
User Prompt: Asks the user to input a URL via a command-line prompt.
QR Code Generation: Creates a QR code for the provided URL using the qr-image module.
File Saving:
Saves the generated QR code as a PNG image (QR_img.png).
Saves the input URL to a text file (URL.txt).

(*)Installation:-
To get started with this project, follow these steps:

(1) Clone the Repository:-

git clone https://github.com/yourusername/qr-generator.git
cd qr-generator

(2) Install Dependencies:-

Ensure you have Node.js installed. Then, install the required npm packages:
npm install

Usage:-
Run the application with the following command:
node index.js

Follow the on-screen prompt to enter a URL. The application will generate a QR code for the URL and save it as QR_img.png in the current directory. The URL will also be saved in a text file named URL.txt.

Error Handling:-
The application includes basic error handling to manage cases where:

-The prompt cannot be rendered due to terminal issues (TTY errors).
-Other unexpected errors occur during execution.

Example:-
Type in your URL: https://example.com
This will generate a QR code for https://example.com and save it as QR_img.png, while the URL is saved in URL.txt.

Contributing:-
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

Contact:-
For any questions or issues, please contact abhishekps5171@gmail.com

