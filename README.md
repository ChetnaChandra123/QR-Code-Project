About the Project
This is a simple QR Code Generator built using Node.js.
When you run the program in your terminal, it asks you to enter a URL.
After entering the URL, the program:

Generates a QR code image (qr_img.png)
Saves the entered URL into a text file (URL.txt)

You can then scan the QR code using your phone to instantly visit the website!


⚙️ Features

📥 Takes user input directly from the terminal

🧾 Converts the URL into a QR code image

💾 Stores the entered URL in a text file

⚡ Runs completely on Node.js (no browser needed)



🧰 Tech Stack

Runtime: Node.js

Packages Used:

inquirer
 → for taking user input

qr-image
 → for generating QR codes

fs (File System) → Node’s built-in module for saving files



📦 Installation and Usage


Clone this repository:
git clone https://github.com/yourusername/qr-code-generator-node.git


Navigate into the project folder:
cd qr-code-generator-node


Install the required dependencies:
npm install inquirer qr-image


Run the program:
node index.js


Follow the prompt:
Type your URL: https://www.google.com


You’ll see two files generated:

🖼️ qr_img.png → the generated QR code

📄 URL.txt → the URL you entered



📁 Folder Structure Diagram

Here’s a visual to help you understand what to push to GitHub 👇

<img width="519" height="137" alt="image" src="https://github.com/user-attachments/assets/2525c990-5429-437e-b928-77175756df0d" />



💡 Future Improvements

i. Option to customize QR color and size

ii. Save multiple URLs in one go

iii. Add an Express.js web interface
