## QR-Code-Generator

**Description:**

This is a QR code generator built using Node.js. It allows you to easily create QR codes for various types of data, such as URLs, text, contact information, and more. The QR code generator leverages the `qrcode` library, which makes the process straightforward and efficient.


## Screenshots:
1. Enter the URL
![image](https://github.com/atinder11/QR-Code-Generator/assets/111070211/d856013b-1aa1-4075-a794-f254ce3289fa)
2.
![image](https://github.com/atinder11/QR-Code-Generator/assets/111070211/a3da7c58-3c23-469c-9eb6-81309f86f155)
3.Fetch the URL
![image](https://github.com/atinder11/QR-Code-Generator/assets/111070211/d8b100a9-6214-4928-886b-81f942ce5daa)

**QR Code Generator - Node.js**




**Installation:**

1. Make sure you have Node.js installed on your machine. You can download it from the official website: https://nodejs.org/

2. Clone this repository to your local machine or download the ZIP file and extract it.

3. Open a terminal or command prompt, navigate to the project's root directory, and run the following command to install the dependencies:

```bash
npm install

```

**Usage:**

1. Open the terminal or command prompt in the project's root directory.

2. Run the following command to start the QR code generator:

```bash
node index.js
```

3. The program will prompt you to enter the data you want to encode into a QR code. You can type any text, a URL, contact information, or other data formats supported by the QR code standard.

4. After entering the data, press the Enter key, and the program will generate a QR code image.

5. The generated QR code image will be saved in the same directory as `index.js` with the name `qr_img.png`.

**Example:**

Let's say you want to generate a QR code for the URL "https://www.youtube.com". Follow these steps:

1. Run the QR code generator as described in the "Usage" section.

2. Enter the URL "https://www.youtube.com" and press Enter.

3. The program will generate a QR code and save it as `qr_img.png` in the same directory.

4. You can now use the generated QR code in your projects, print it, or share it as needed.

**Note:**

The generated QR codes are in the PNG format, which is widely supported and used in various applications. If you need the QR code in a different format or with specific configurations, you can modify the code in `qr-code-generator.js` accordingly.

**License:**

This QR code generator is released under the MIT License. Feel free to use and modify it for your own purposes. However, make sure to check the `LICENSE` file for more details.

For any issues or suggestions, please create an issue on the GitHub repository: [https://github.com/atinder11/QR-Code-Generator](https://github.com/atinder11/QR-Code-Generator)

Happy QR code generating!

