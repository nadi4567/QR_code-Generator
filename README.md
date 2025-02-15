QR Code Generator
- This is a simple Node.js project that generates a QR code from a user-provided URL using the inquirer and qr-image npm packages. It also saves the input URL to a text file using Node.js' native fs module.
- For example: if you type youtube.com, program will generate qr image in qr-img.png file. And scan that image. it will direct to specific path.

🛠 Features
- Takes user input using inquirer
- Generates a QR code image using qr-image
- Saves the entered URL in a text file

Prerequisites
- Make sure you have the following installed:
- Node.js
- npm (comes with Node.js)

.
📂 Installation

Clone the repository:
- git clone https://github.com/nadi4567/QR_code-Generator.git

Navigate to the project directory:
- cd QR_code-Generator
  
Install dependencies:
- npm install

Usage

Run the script using the following command:
- node index.js
- Follow the prompts to enter a URL. The script will generate a QR code image (qr_img.png) and save the URL to a text file (URL.txt).

Dependencies

inquirer - Used to prompt the user for input

qr-image - Used to generate the QR code image

Node.js fs module - Used to write data to a file


[Yu Nadi Soe]



