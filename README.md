# Simple-Text-Editor with Font Customization.
Punt-Partner assignment simple-text-editor.
**UI Deployed link:** https://text-editor-fe.vercel.app/

This project is a simple text editor implemented using React and JavaScript. The editor allows users to select a font family, font weight, and toggle italic styling. The font settings are applied instantly to the entire text. The editor also supports auto-saving the text and font settings locally in the browser, ensuring that the current content and settings are restored upon reloading the page. Additional functionalities include resetting the editor and saving the text as a list below the editor box.

## Features

1. **Font Family Selector**: Displays a list of all Google Fonts.
2. **Font Weight Selector**: Shows the appropriate font weights supported for the selected font family.
3. **Italic Toggle**: The italic toggle is active only if the selected font family and weight combination supports italic.
4. **Auto-Save**: Saves the text and font settings locally in the browser.
5. **Reset Button**: Resets the text area.
6. **Save Button**: Saves the current text to a list displayed below the editor.

## Folder Structure
![folder-structure-text-editor](https://github.com/Deepak-25yadav/simple-text-editor/assets/112754831/d2795d50-8970-4271-ad08-2be8d0a29bf6)


## Setup and How to Run the Application

### Prerequisites

- Node.js (v12 or later)
- npm (v6 or later) or yarn

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Deepak-25yadav/simple-text-editor.git
   cd simple-text-editor
   cd text-editor-fe
   
### Install the dependencies:
npm install

## Running the Application
### Start the development server:
npm start

Open your browser and navigate to **http://localhost:3000**

## Assumptions

1. **LocalStorage as a Proxy for Backend**: The application uses local storage to simulate a backend for saving and retrieving data. In a real-world application, this data would be managed by a backend service.
2. **Font Variants Handling**: The application assumes that all font families and their variants are correctly listed in the `fonts.json` file.
3. **Error Handling**: The application includes basic error handling for common issues, such as missing font variants.


## Improvements

1. **Enhanced Error Handling**: More comprehensive error handling to cover edge cases and provide user-friendly error messages.
2. **Responsive Design**: Ensure the editor is fully responsive and works well on all device sizes.
3. **Unit Tests**: Add unit tests for all components and utilities to ensure robustness and reliability.
4. **Code Optimization**: Refactor and optimize the code for better performance and maintainability.
5. **Backend Integration**: Replace local storage with a real backend service for persistent data storage and retrieval.

## Contributing

1. **Fork the repository**.
2. **Create a new branch**:
   ```sh
   git checkout -b feature-branch

3. **Make your changes and commit them**
git commit -m 'Add some feature'
4. **Push to the branch:**
git push origin feature-branch


