# Color Palette Extractor

A beautiful, minimalist web application that extracts color palettes from images. Built with vanilla JavaScript and Tailwind CSS, this tool helps designers and developers quickly discover color schemes from any image.

## Features

- **Image Upload**: Drag-and-drop or click to upload any image
- **Color Extraction**: Automatically extracts dominant colors using the Color Thief algorithm
- **Multiple Formats**: View colors in HEX, RGB, or HSL formats
- **Adjustable Count**: Choose between 2-10 colors to extract
- **Copy to Clipboard**: Click any color to instantly copy its value
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Dark Theme**: Easy on the eyes with a sleek monochrome interface

## Demo

Upload an image and watch as beautiful color palettes are extracted in real-time. The interface features:

- Clean drag-and-drop zone with image preview
- Interactive color cards with smart contrast text
- Visual summary bar showing the complete palette
- Smooth animations and micro-interactions

## Technology Stack

- **HTML5**: Semantic markup and modern features
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Vanilla JavaScript**: No dependencies, pure JS functionality
- **Color Thief**: Advanced color extraction algorithm

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - runs entirely in the browser

### Usage

1. **Open the Application**: Open `index.html` in your web browser
2. **Upload an Image**: 
   - Click the upload area to select a file
   - Or drag and drop an image onto the upload zone
3. **Customize Extraction**:
   - Use the slider to adjust the number of colors (2-10)
   - Select your preferred color format (HEX, RGB, HSL)
4. **Extract Colors**: Click "Re-extract Colors" or let it auto-extract
5. **Copy Colors**: Click any color card to copy its value to clipboard

### File Upload

- **Supported Formats**: JPG, PNG, GIF, WebP, and all major image formats
- **File Size**: Works best with images under 10MB
- **Privacy**: All processing happens locally in your browser - no data is sent to servers

## Color Formats

### HEX
- Example: `#FF5733`
- Best for: Web development, CSS

### RGB
- Example: `RGB(255, 87, 51)`
- Best for: Design software, programming

### HSL
- Example: `HSL(9, 100%, 60%)`
- Best for: Color manipulation, design systems

## Features in Detail

### Smart Contrast Text
Color cards automatically adjust text color based on background brightness for optimal readability.

### Visual Summary Bar
A compact horizontal bar at the bottom shows all extracted colors proportionally.

### Responsive Grid
Color cards automatically adjust from 2-column to single-column layout on smaller screens.

### Toast Notifications
Get instant feedback when colors are copied to clipboard.

## Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## Contributing

This project is open to contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature-name`
3. **Make your changes**
4. **Test thoroughly** in multiple browsers
5. **Commit your changes**: `git commit -m 'Add feature description'`
6. **Push to branch**: `git push origin feature-name`
7. **Open a Pull Request**

### Development

To work on this project locally:

1. Clone the repository
2. Open `index.html` in your browser
3. Make changes to the files
4. Refresh the browser to see updates

No build process or development server required!

## Project Structure

```
color-palette/
├── index.html          # Main application file
├── README.md           # This documentation
└── .git/              # Git version control
```

## Performance

- **Fast Loading**: Under 50KB total size
- **Instant Processing**: Color extraction in milliseconds
- **Memory Efficient**: Optimized for smooth performance
- **No Dependencies**: Zero external dependencies beyond CDN links

## Privacy & Security

- **Local Processing**: All image processing happens in your browser
- **No Data Collection**: No analytics or tracking
- **Secure**: HTTPS ready for production deployment
- **Open Source**: Fully transparent codebase

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- **Color Thief**: For the excellent color extraction algorithm
- **Tailwind CSS**: For the utility-first CSS framework
- **Inter Font**: For the clean, modern typography

## Future Enhancements

- [ ] Export palettes as CSS variables
- [ ] Save palettes to local storage
- [ ] Import/export palette files
- [ ] Color blindness simulation
- [ ] Palette harmony suggestions
- [ ] Integration with design tools (Figma, Sketch)

---

Made with ❤️ for designers and developers who love beautiful colors.
