
 Text Editor Application

This is a simple text editor application that allows users to select font families, font weights, and toggle italic styling. The application also supports saving the text and font settings locally in the browser.

## Features

- Select font family from a list of Google Fonts.
- Choose font weight for the selected font family.
- Toggle italic style based on font support.
- Auto-save text content and font settings in local storage.
- Reset and save buttons to manage text and settings.

## Prerequisites

- Web browser (Chrome, Firefox, Edge, etc.)
- Basic understanding of HTML, CSS, and JavaScript

## Setup and Installation

1. Clone the Repository

   Clone this repository to your local machine using the following command:

   bash
   git clone https://github.com/praseedakatta/Test.git
   

2. Navigate to Project Directory

   Change to the project directory:

   bash
   cd Test
   

3. File Structure

   Ensure your project directory contains the following files:

   - `index.html` - The main HTML file
   - `style.css` - The CSS file for styling
   - `script.js` - The JavaScript file containing the application logic
   - `fonts.json` - JSON file containing font data

4. Open in Browser

   Open `index.html` in your preferred web browser. You can do this by double-clicking the file or by opening it through the browser's "Open File" option.

   Alternatively, you can use a local server to serve the files. If you have Python installed, you can use:

   bash
   python -m http.server
   

   Then navigate to `http://localhost:8000` in your web browser.

## Usage

1. Font Family Selector

   - Choose a font family from the dropdown menu. The available options are populated from the 'fonts.json.json' file.

2. Font Weight Selector

   - After selecting a font family, the font weight dropdown will be updated with available weights for the selected font.

3. Italic Toggle

   - Check or uncheck the italic checkbox to apply or remove italic styling.

4. Reset Button

   - Click the "Reset" button to clear the text area and reset font settings to default.

5. Save Button

   - Click the "Save" button to save the current text content and font settings to localStorage.

## LocalStorage Handling

- The text content and font settings (font family, weight, and italic) are saved in `localStorage` and are reloaded when the page is refreshed.

## Troubleshooting

- **Font Weight Selector is Empty:** Ensure that the 'fonts.json.json' file is correctly formatted and accessible. Check the console for any errors related to loading or parsing the JSON file.
- **Font Not Applying Correctly:** Verify that the correct URL for the Google Font is being generated and applied in the `<link>` tag.

