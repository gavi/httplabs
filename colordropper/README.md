# Color Dropper Tool

## Overview

The Color Dropper Tool is a web-based application that allows users to pick colors from uploaded images. It's designed to be lightweight, fast, and easy to use, leveraging modern web technologies and CDNs for optimal performance.

## Features

- Image upload via drag-and-drop or file selection
- Real-time color picking with zoom functionality
- Display of selected colors in RGB and HEX formats
- One-click copy of HEX color codes
- Responsive design for desktop and mobile devices

## Technical Stack

- **HTML5**: Structure of the web application
- **CSS**: Styling using Tailwind CSS framework
- **JavaScript**: Vanilla JS for all functionality
- **Canvas API**: Used for image processing and color extraction

## CDNs and External Resources

1. **Tailwind CSS**: 
   - URL: `https://cdn.tailwindcss.com`
   - Version: Latest (automatically served by CDN)
   - Purpose: Provides utility-first CSS classes for rapid UI development

2. **Lucide Icons**:
   - URL: `https://unpkg.com/lucide@latest/dist/umd/lucide.js`
   - Version: Latest (specified in URL)
   - Purpose: Supplies SVG icons for the user interface

## Key Components

1. **Image Upload**:
   - Utilizes HTML5 File API for handling file inputs
   - Supports both drag-and-drop and traditional file selection

2. **Color Picking**:
   - Uses HTML5 Canvas API to read pixel data from uploaded images
   - Implements custom zoom functionality for precise color selection

3. **Zoom View**:
   - Custom-built zoom view using Canvas API
   - Displays a 21x21 pixel grid centered on the current cursor position

4. **Color Display**:
   - Shows selected color as a filled rectangle
   - Provides both RGB and HEX color codes
   - Offers one-click copy functionality for HEX codes

5. **Responsive Design**:
   - Utilizes Tailwind CSS for a mobile-first, responsive layout
   - Adapts to various screen sizes while maintaining functionality

## Installation and Running

1. Clone the repository:
   ```
   git clone https://github.com/objectgraph/httplabs.git
   ```

2. Navigate to the project directory:
   ```
   cd httplabs/colordropper
   ```

# Color Dropper Tool

[Previous sections remain unchanged]

## Installation and Running

1. Clone the repository:
   ```
   git clone https://github.com/gavi/httplabs.git
   ```

2. Navigate to the project directory:
   ```
   cd httplabs/colordropper
   ```

3. Start a local HTTP server:

   For Python 3.x:
   ```
   python -m http.server 8000
   ```
   
   For Python 2.x:
   ```
   python -m SimpleHTTPServer 8000
   ```

   If you don't have Python installed, you can use any other local HTTP server of your choice.

4. Open your web browser and visit:
   ```
   http://localhost:8000
   ```

## Browser Compatibility

The Color Dropper Tool is compatible with modern web browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Considerations

- The tool processes images client-side, so performance may vary based on the user's device capabilities and the size of the uploaded image.
- Large images may require more processing time and memory.

## Contributing

We welcome contributions to improve the Color Dropper Tool. Please submit issues or pull requests to the [project repository](https://github.com/gavi/httplabs).

## License

This project is licensed under the MIT License:

```
MIT License

Copyright (c) 2023 HTTPLabs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Acknowledgements

- Tailwind CSS team for their excellent CSS framework
- Lucide for providing high-quality open-source icons