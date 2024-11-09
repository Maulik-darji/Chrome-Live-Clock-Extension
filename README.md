# Live Clock Extension

This Chrome extension adds a live clock widget to your new tab page. The clock dynamically adjusts its size based on your screen resolution, providing a responsive and visually appealing clock experience.

## Features
- Displays the current time in hours, minutes and seconds.
- Adjustable size for all screen resolutions.
- Customizable clock appearance with gradients and rounded borders.
- Option to Enable and Disable the clock widget via a Chrome extension setting.

## Installation

### 1. Download the Extension Files
- Clone or download the repository to your computer.

### 2. Load the Extension in Chrome

To install the extension locally for development:
1. Open Chrome and navigate to `chrome://extensions/`.
2. Enable **Developer mode** in the top right corner.
3. Click **Load unpacked**.
4. Select the folder containing the extension files (the folder where `manifest.json` and all related files are located).

### 3. Add the Extension to Chrome
Once the extension is loaded, the live clock will appear on your new tab page, adjusting its size based on your screen resolution.

## How It Works
- The extension uses JavaScript to get the current time and update it every minute.
- The clock container's size and font adjust dynamically based on the size of the viewport.
- The clock is styled with a beautiful gradient background and a smooth rounded border for a modern look.
- You can also toggle the clock's visibility via Chrome's storage API, which can be configured through your extension settings.


### To Configure Clock Visibility:
- The clock is initially shown. You can hide it using the setting stored in **chrome.storage.sync**.
  
## Customizing
- If you'd like to change the appearance of the clock, modify the styles in the `style.css` file.
- You can also change the gradient colors, font sizes, and border radius to fit your design preferences.

## License
This extension is open-source and free to use. Feel free to modify or contribute to this project.

## Contributing
If you want to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. We welcome contributions!

## Contact
If you have any issues or questions, please contact maulik.darji2004@gmail.com


---

