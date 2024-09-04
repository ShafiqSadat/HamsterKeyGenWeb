:root {
    --bg-color: #f5f7fa;
    --selected-bg-color: #007bff;
    --selected-text-color: #ffffff;
    --container-bg: #ffffff;
    --text-color: #333;
    --heading-color: #007bff;
    --border-color: #ddd;
    --hover-border-color: #007bff;
    --label-color: #555;
    --slider-bg: #ddd;
    --slider-thumb: #007bff;
    --slider-thumb-hover: #0056b3;
    --button-bg: #007bff;
    --button-color: white;
    --button-hover: #0056b3;
    --progress-bg: #f5f7fa;
    --progress-fill: #007bff;
    --input-border: #ccc;
    --input-bg: #ffffff;
    --copy-button-bg: #28a745;
    --copy-button-hover: #218838;
    --footer-color: #777;
    --copy-status-color: green;
    --box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

[data-theme="dark"] {
    --bg-color: #1a1a1a;
    --selected-bg-color: #2c3e50;
    --selected-text-color: #ecf0f1;
    --container-bg: #2a2a2a;
    --text-color: #e0e0e0;
    --heading-color: #4da3ff;
    --border-color: #444;
    --hover-border-color: #4da3ff;
    --label-color: #bbb;
    --slider-bg: #444;
    --slider-thumb: #4da3ff;
    --slider-thumb-hover: #3a7abd;
    --button-bg: #4da3ff;
    --button-color: #1a1a1a;
    --button-hover: #3a7abd;
    --progress-bg: #444;
    --progress-fill: #4da3ff;
    --input-border: #444;
    --input-bg: #333;
    --copy-button-bg: #2ecc71;
    --copy-button-hover: #27ae60;
    --footer-color: #888;
    --copy-status-color: #2ecc71;
    --box-shadow: 0 4px 20px rgba(255, 255, 255, 0.1);
}

/* Ensure body scrolls */
body {
    font-family: 'Roboto', sans-serif;
    background-color: var(--bg-color);
    color: var(--text-color);
    display: flex;
    justify-content: center;
    align-items: flex-start; /* Align content to the top */
    min-height: 100vh; /* Ensure the page height is always at least 100% of the viewport */
    margin: 0;
    overflow-y: auto; /* Allow vertical scrolling */
}

.container {
    background: var(--container-bg);
    border-radius: 10px;
    box-shadow: var(--box-shadow);
    padding: 30px;
    max-width: 500px;
    width: 100%;
    text-align: center;
}

h1 {
    margin-bottom: 25px;
    font-size: 24px;
    color: var(--heading-color);
}

/* Add a max height and enable scrolling for the game options */
.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
    margin-bottom: 20px;
    max-height: 600px; /* Adjust this height based on your layout needs */
    overflow-y: auto;
    padding: 10px 10px 10px 10px
}

.game-option {
    border: 2px solid var(--border-color);
    border-radius: 10px;
    padding: 10px;
    text-align: center;
    cursor: pointer;
    transition: transform 0.3s, border-color 0.3s, background-color 0.3s, color 0.3s;
    background-color: var(--container-bg);
    color: var(--text-color);
}

.game-option:hover {
    border-color: var(--hover-border-color);
    transform: scale(1.03);
}

/* Style for selected game option */
.game-option.selected {
    transform: scale(1.05); /* Slight scale */
    border-color: var(--selected-bg-color);
    background: linear-gradient(135deg, #007bff 0%, #0056b3 100%); /* Gradient background */
    color: var(--selected-text-color) !important;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2); /* Subtle shadow */
    transition: all 0.3s ease-in-out; /* Smooth transition */
}

.game-option img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: 10px;
}

.game-option p {
    font-size: 16px; /* Increase font size */
    font-weight: 600; /* Make it bold */
}

/* Optional hover effect on game options */
.game-option:hover {
    transform: scale(1.05);
    border-color: var(--hover-border-color);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); /* Slight shadow on hover */
}

.game-option.selected p {
    color: white; /* Ensure text is visible on the new background */
}

.form-group {
    margin-bottom: 20px;
    text-align: left;
}

label {
    display: block;
    margin-bottom: 8px;
    font-weight: 500;
    color: var(--label-color);
}

.key-slider {
    display: flex;
    align-items: center;
    gap: 10px;
}

.key-slider input[type="range"] {
    -webkit-appearance: none;
    width: 100%;
    height: 8px;
    border-radius: 5px;
    background: var(--slider-bg);
    outline: none;
    transition: background 0.3s;
}

.key-slider input[type="range"]::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background: var(--slider-thumb);
    cursor: pointer;
    transition: background 0.3s;
}

.key-slider input[type="range"]:hover::-webkit-slider-thumb {
    background: var(--slider-thumb-hover);
}

#keyValue {
    font-size: 18px;
    font-weight: bold;
    color: var(--heading-color);
}

button {
    background-color: var(--button-bg);
    color: var(--button-color);
    border: none;
    padding: 12px 20px;
    font-size: 16px;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s;
    margin-top: 20px;
}

button:hover {
    background-color: var(--button-hover);
}

.hidden {
    display: none;
}

.progress-bar {
    background-color: var(--progress-bg);
    border-radius: 8px;
    overflow: hidden;
    margin-top: 25px;
    height: 35px;
    position: relative;
}

.progress-bar div {
    height: 100%;
    background-color: var(--progress-fill);
    width: 0;
    transition: width 0.5s;
}

#progressText {
    margin-top: 15px;
    font-weight: 600;
}

.key-item {
    display: flex;
    align-items: center;
    margin-top: 15px;
}

.key-item input {
    flex: 1;
    padding: 12px;
    font-size: 16px;
    border: 1px solid var(--input-border);
    border-radius: 8px;
    margin-right: 12px;
    background-color: var(--input-bg);
    color: var(--text-color);
}

.copyKeyBtn {
    background-color: var(--copy-button-bg);
    border: none;
    padding: 12px 20px;
    color: var(--button-color);
    font-size: 16px;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.copyKeyBtn:hover {
    background-color: var(--copy-button-hover);
}

.footer {
    margin-top: 25px;
    font-size: 14px;
    color: var(--footer-color);
}

#copyStatus {
    margin-top: 15px;
    color: var(--copy-status-color);
}
