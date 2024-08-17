# Hamster Promo Code Generator
![image](https://github.com/user-attachments/assets/3488f975-7188-4651-903b-7cccf1200056)


This project is a web-based application for generating promo codes for various games. The application allows users to select a game, choose the number of promo codes they want to generate, and then generates the codes while showing the progress. The application also includes options to copy the generated codes to the clipboard.

## ⭐ 💹 Need bulk keys? 
- Contact me: [Telegram](https://t.me/Shafiq)
  
## Features

- **Game Selection**: Users can select from a list of available games.
- **Key Count Selection**: Users can choose the number of keys to generate (1 to 10).
- **Progress Indication**: The application shows a progress bar and updates the user on the current status of key generation.
- **Generated Keys Display**: Once the keys are generated, they are displayed in a list with options to copy each key individually or all keys at once.
- **Copy to Clipboard**: Users can copy individual keys or all generated keys to the clipboard with a single click.
- **Responsive Design**: The application is designed to work well on various screen sizes.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/ShafiqSadat/HamsterKeyGenWeb.git
    ```

2. **Open the Project**:
    Navigate to the project directory and open the `index.html` file in your web browser.

## Usage

1. **Select a Game**:
    - Choose a game from the dropdown menu.

2. **Select Number of Keys**:
    - Choose the number of keys you want to generate from the dropdown menu.

3. **Generate Keys**:
    - Click the "Generate Keys" button to start the key generation process.
    - The form sections will be hidden, and a progress bar will indicate the progress of key generation.

4. **View and Copy Keys**:
    - Once the keys are generated, they will be displayed in a list.
    - Click the "Copy Key" button next to each key to copy it to the clipboard.
    - Click the "Copy All Keys" button to copy all generated keys to the clipboard.

5. **Generate More Keys**:
    - Click the "Generate More Keys" button to reset the form and generate more keys.

## Script Details

### JavaScript (`script.js`)

- **Event Listeners**:
    - Listens for the "DOMContentLoaded" event to initialize the application.
    - Handles the "click" event on the "Generate Keys" button to start the key generation process.
    - Handles the "click" event on the "Copy Key" buttons to copy individual keys.
    - Handles the "click" event on the "Copy All Keys" button to copy all keys.
    - Handles the "click" event on the "Generate More Keys" button to reset the form and allow generating more keys.
    - Handles the "click" event on the "Source Code" button to open the GitHub repository.

- **Functions**:
    - `generateClientId()`: Generates a unique client ID.
    - `login(clientId, appToken)`: Logs in to the API with the provided client ID and app token.
    - `emulateProgress(clientToken, promoId)`: Emulates progress events required by the API.
    - `generateKey(clientToken, promoId)`: Generates a promo key using the API.
    - `generateUUID()`: Generates a unique UUID.
    - `sleep(ms)`: Pauses execution for the specified amount of time.
    - `delayRandom()`: Generates a random delay value.

### CSS (`styles.css`)

- **Styling**:
    - Modern font and color scheme.
    - Flexbox layout for centering content.
    - Rounded corners and shadows for a modern card-like appearance.
    - Transitions for interactive elements like buttons.
    - Hidden classes to show/hide elements as needed.

### HTML (`index.html`)

- **Structure**:
    - A container with form sections for game selection and key count selection.
    - Buttons for generating keys, copying keys, and generating more keys.
    - Progress bar and status updates during key generation.
    - List of generated keys with copy buttons.
    - Footer with a disclaimer and source code link.

## Disclaimer

This tool is for educational purposes only. Use responsibly.

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.

