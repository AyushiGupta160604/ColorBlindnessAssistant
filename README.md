# Color Blindness Assistant

## Overview
#### Color Blindness Assistant is a Chrome extension designed to improve accessibility for users with color vision deficiencies. By applying various color filters to web pages, it helps users with different types of color blindness view content more clearly and comfortably.

## Features
- Filter Options: Easily switch between different color blindness filters:
  - None: Normal Vision
  - Protanopia: Red Color Blindness
  - Deuteranopia: Green Color Blindness
  - Tritanopia: Blue Color Blindness
- User-Friendly Interface: A simple popup with a dropdown menu to select the desired filter and an apply button.
- Persistent Settings: Save your default filter setting for future browsing sessions.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/AyushiGupta160604/ColorBlindnessAssistant.git
   ```
2. Load the extension:
   -  Open Chrome and navigate to chrome://extensions/.
   -  Enable "Developer mode" using the toggle switch.
   -  Click "Load unpacked" and select the directory containing the extension.
  
## Usage
1. Open the Popup: Click the extension icon in the Chrome toolbar.
2. Select a Filter: Choose a color blindness filter from the dropdown menu.
3. Apply Filter: Click the "Apply" button to activate the selected filter on the current webpage.

## Development
This extension is built using:
- Frontend: HTML, CSS, and JavaScript
- Backend: No server-side code required

## Project Structer
- manifest.json: Chrome extension manifest file
- background.js: Background script for handling installation events
- popup/: Popup UI and logic
  - popup.html: HTML for the popup
  - popup.css: Styles for the popup
  - popup.js: JavaScript for the popup interactions
- content/: Content scripts applied to web pages
  - content.css: CSS for applying filters
  - content.js: JavaScript for injecting SVG filters
- options/: Options page for setting default filters
  - options.html: HTML for the options page
  - options.js: JavaScript for saving default filter settings
- filter.svg: SVG filters for color blindness simulation

## Contact
#### For any inquiries or feedback, please contact the project maintainer at:
- Email: `22cs3022@gmail.com`
- LinkedIn: `https://www.linkedin.com/in/ayushigupta1604/`
- Twitter: `https://x.com/Ayushi_G16`
- Github: `https://github.com/AyushiGupta160604`
- Topmate: `https://topmate.io/ayushi_gupta16/`
- Fiver: `https://www.fiverr.com/users/ayushigupta200/`
