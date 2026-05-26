# Multiple Bootstrap Colorpicker

A simple demo project showing how to create and use multiple dynamically added Bootstrap colorpickers on a single page.

## Features

- Add multiple colorpickers dynamically
- Remove colorpickers individually
- Each colorpicker maintains its own state
- Uses Bootstrap 2.1.1 and bootstrap-colorpicker 2.5.1

## Demo

![Demo Screenshot](https://raw.githubusercontent.com/username/multiple_bootstrap_colorpicker/main/screenshot.png)

## How to Use

1. Clone this repository
2. Open `example.html` in your browser
3. Click "Add new" to add more colorpickers
4. Click "Remove" to delete a colorpicker
5. Click on the color preview to open the colorpicker

## Implementation Details

The project uses a clever CSS trick to make the colorpicker open when clicking on the color preview area. The main components are:

- `example.html`: Contains the HTML structure and JavaScript logic
- `example.css`: Provides the CSS styling for the colorpicker trick

## Dependencies

- jQuery 2.1.4
- Twitter Bootstrap 2.1.1
- bootstrap-colorpicker 2.5.1

All dependencies are loaded from CDN in the example.html file.

## License

This project is open source and available under the MIT License.