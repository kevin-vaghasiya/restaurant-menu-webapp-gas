# Restaurant Menu Web App using Google Sheet and Google Apps Script

Easily create a digital restaurant menu accessible via QR Code. Modify the menu using Google Sheets and have changes automatically reflected in the live web app!

## Setup and Configuration

### Step 1: Google Sheet Setup
1. Copy the template spreadsheet from [this link](https://docs.google.com/spreadsheets/d/1fFQ3Way0qLuc6Z1QsqIu8E-8URorVDQwxGII8pnGeW4/edit#gid=967431055).
2. In the **Settings** sheet, provide the restaurant name, logo URL, and currency symbol.
3. Populate the **Categories** sheet with categories like starters, main course, etc.
4. Fill in the **Menu** sheet with menu items including their name, description, image URL, price, and category.

### Step 2: Deploy the Web App
1. Open the spreadsheet.
2. Navigate to the `Extensions` menu and select `Apps Script`.
3. Click the `Deploy` button > `New deployment`.
4. Press `Deploy` and then authorize access.
5. Grant the necessary permissions. A Web App URL will be generated. Make sure to copy this URL.

### Step 3: Generate QR Code
1. Visit [QR Code Generator](https://www.the-qrcode-generator.com/).
2. Paste the copied Web App URL and generate your QR Code.
3. Download and print the QR Code for your restaurant's customers to access the menu.

🔗 Note: You can use Google Drive links for images. Ensure the file sharing settings are set to "Anyone can access".

## Features

- **Real-time Updates**: Any changes made to the Google Sheet will automatically reflect in the web app.
- **Customizable**: Easily modify menu items, add images, and adjust pricing through the Google Sheet interface.
- **Open Source**: Contributions and improvements are welcome!

## Safety and Privacy

We respect your privacy! This open-source project does not collect or share any data. Always ensure you're granting permissions to trusted scripts and applications.

## Feedback and Contributions

Your feedback is valuable! If you encounter any issues or have feature suggestions, please [open an issue](https://github.com/kevin-vaghasiya/restaurant-menu-webapp-gas/issues) on GitHub.


## License

This project is open source and available under the MIT License

