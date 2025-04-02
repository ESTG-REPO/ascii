# 🎨 ASCII Art Generator

<div align="center">
  
  ![ASCII Art Generator Banner](https://i.ibb.co/HN4BFKJ/ascii-art-sample.png)
  
  <h3>Transform your images into beautiful ASCII art with powerful customization</h3>

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
  [![Bootstrap](https://img.shields.io/badge/Bootstrap-5.2.3-7952B3.svg)](https://getbootstrap.com/)
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg)](https://html.org/)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg)](https://www.w3.org/Style/CSS/)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  
  <a href="https://ascii.pt" target="_blank">
    <img src="https://img.shields.io/badge/Visit-ASCII.PT-4CAF50?style=for-the-badge&logo=image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48dGV4dCB5PSIuOWVtIiBmb250LXNpemU9IjkwIj7wn4e4PC90ZXh0Pjwvc3ZnPg==" alt="Visit ASCII.PT" height="36"/>
  </a>
  
</div>

## 📋 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Usage Guide](#-usage-guide)
- [Customization Options](#-customization-options)
- [Technical Details](#-technical-details)
- [Algorithm Implementation](#-algorithm-implementation)
- [Keyboard Shortcuts](#%EF%B8%8F-keyboard-shortcuts)
- [Troubleshooting](#-troubleshooting)
- [Performance Tips](#-performance-tips)
- [Browser Compatibility](#-browser-compatibility)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)
- [Contact & Support](#-contact--support)

## 🌟 Overview

The **ASCII Art Generator** is a sophisticated web application that transforms ordinary images into text-based art with extraordinary detail and customization options. Built with modern web technologies, it provides an intuitive interface for converting any image into ASCII characters with precise control over the output style, density, and visual effects.

Whether you're looking to create nostalgic text art, generate creative visuals for your projects, or simply explore the intersection of images and text, this tool offers a comprehensive suite of features to bring your creative vision to life.

### What is ASCII Art?

ASCII art is a graphic design technique that uses printable characters from the ASCII standard to create images. It's been a popular form of digital art since the early days of computing when graphical capabilities were limited. Our generator brings this classic art form into the modern age with advanced algorithms and customization options.

## 🔍 Live Demo

Experience the ASCII Art Generator in action! Visit our official website [ASCII.PT](https://ascii.pt) to try all features without installation.

<div align="center">
  <a href="https://ascii.pt" target="_blank">
    <img src="https://img.shields.io/badge/Try_it_now_on-ASCII.PT-4CAF50?style=for-the-badge&logo=image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48dGV4dCB5PSIuOWVtIiBmb250LXNpemU9IjkwIj7wn4e4PC90ZXh0Pjwvc3ZnPg==" alt="Try it on ASCII.PT" height="48"/>
  </a>
</div>

## ✨ Features

<table>
  <tr>
    <td width="50%">
      <h3>🖌️ Conversion Methods</h3>
      <ul>
        <li><strong>Standard Grayscale:</strong> Classic brightness-to-character mapping</li>
        <li><strong>Edge Detection:</strong>
          <ul>
            <li>Sobel operator for strong edges</li>
            <li>Difference of Gaussians (DoG) for detailed contours</li>
          </ul>
        </li>
        <li><strong>Dithering Algorithms:</strong>
          <ul>
            <li>Floyd-Steinberg: Error diffusion for enhanced detail</li>
            <li>Atkinson: Balanced dithering with reduced artifacts</li>
            <li>Ordered: Structured pattern dithering</li>
            <li>Noise: Random noise for artistic effect</li>
          </ul>
        </li>
      </ul>
    </td>
    <td width="50%">
      <h3>🎛️ Image Controls</h3>
      <ul>
        <li><strong>Resolution Control:</strong> Adjust character width for detail level</li>
        <li><strong>Image Adjustments:</strong>
          <ul>
            <li>Brightness: -100 to +100</li>
            <li>Contrast: -100 to +100</li>
            <li>Blur: 0 to 10px Gaussian blur</li>
          </ul>
        </li>
        <li><strong>Special Options:</strong>
          <ul>
            <li>Invert: Reverse brightness values</li>
            <li>Ignore White: Transparent background option</li>
          </ul>
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔠 Character Options</h3>
      <ul>
        <li><strong>Built-in Character Sets:</strong>
          <ul>
            <li>Detailed: Full range of density characters</li>
            <li>Standard: Common ASCII art characters</li>
            <li>Blocks: Unicode block characters</li>
            <li>Binary: Simple 0 and 1 patterns</li>
            <li>Hex: Hexadecimal digits (0-F)</li>
          </ul>
        </li>
        <li><strong>Custom Characters:</strong> Define your own character set</li>
        <li><strong>Manual Character:</strong> Single character mode with spaces</li>
        <li><strong>Colorized Output:</strong> Preserve original image colors</li>
      </ul>
    </td>
    <td width="50%">
      <h3>📱 User Experience</h3>
      <ul>
        <li><strong>Responsive Design:</strong> Works on all devices</li>
        <li><strong>Theme Options:</strong> Light and dark mode with auto-detection</li>
        <li><strong>File Handling:</strong>
          <ul>
            <li>Drag & drop upload</li>
            <li>File dialog</li>
            <li>Sample image gallery</li>
          </ul>
        </li>
        <li><strong>Multi-view Options:</strong>
          <ul>
            <li>ASCII art view</li>
            <li>Original image view</li>
            <li>Side-by-side comparison</li>
            <li>History panel</li>
          </ul>
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>💾 Export & Share</h3>
      <ul>
        <li><strong>Copy to Clipboard:</strong> With formatting preserved</li>
        <li><strong>Download Options:</strong>
          <ul>
            <li>PNG: High-quality image with configurable resolution</li>
            <li>SVG: Scalable vector format</li>
            <li>TXT: Plain text format</li>
            <li>HTML: Styled web page with custom CSS</li>
          </ul>
        </li>
        <li><strong>Sharing:</strong> Generate URLs with embedded settings</li>
      </ul>
    </td>
    <td width="50%">
      <h3>⚙️ Advanced Features</h3>
      <ul>
        <li><strong>History System:</strong> Browse and restore previous generations</li>
        <li><strong>Presets:</strong>
          <ul>
            <li>Built-in presets (Default, Sketch, Minimalist, etc.)</li>
            <li>Save custom presets</li>
            <li>Load saved presets</li>
          </ul>
        </li>
        <li><strong>Performance Optimization:</strong> Efficient algorithms for large images</li>
        <li><strong>Keyboard Controls:</strong> Shortcuts for common actions</li>
        <li><strong>Font & Zoom Control:</strong> Customize display appearance</li>
      </ul>
    </td>
  </tr>
</table>

## 📸 Screenshots

<div align="center">
  <table>
    <tr>
      <td><img src="https://i.ibb.co/4PXYmtW/ascii-screenshot-1.jpg" alt="Main Interface" width="400"/></td>
      <td><img src="https://i.ibb.co/p0MHCnC/ascii-screenshot-2.jpg" alt="Side-by-Side View" width="400"/></td>
    </tr>
    <tr>
      <td align="center"><em>Main Interface - Dark Mode</em></td>
      <td align="center"><em>Side-by-Side Comparison View</em></td>
    </tr>
    <tr>
      <td><img src="https://i.ibb.co/6P3qQSW/ascii-screenshot-3.jpg" alt="Color ASCII Mode" width="400"/></td>
      <td><img src="https://i.ibb.co/mJjMgwY/ascii-screenshot-4.jpg" alt="Edge Detection" width="400"/></td>
    </tr>
    <tr>
      <td align="center"><em>Colorized ASCII Output</em></td>
      <td align="center"><em>Edge Detection Mode</em></td>
    </tr>
  </table>
</div>

## 🚀 Installation

The ASCII Art Generator is available online at [ASCII.PT](https://ascii.pt), but you can also run it locally as it's built with standard web technologies. Follow these simple steps to get it running on your machine.

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of running a local server (optional)

### Method 1: Direct Download

1. **Download the code** from the GitHub repository:
   ```bash
   git clone https://github.com/your-username/ascii-art-generator.git
   cd ascii-art-generator
   ```

2. **Start a local server** using one of these methods:

   <details>
   <summary>Using Python (recommended)</summary>
   
   ```bash
   # Python 3
   python -m http.server 8080
   
   # Python 2
   python -m SimpleHTTPServer 8080
   ```
   </details>

   <details>
   <summary>Using Node.js</summary>
   
   ```bash
   # Install serve globally (one-time setup)
   npm install -g serve
   
   # Start the server
   serve -p 8080
   ```
   </details>

   <details>
   <summary>Using PHP</summary>
   
   ```bash
   php -S localhost:8080
   ```
   </details>

3. **Access the application** by navigating to:
   ```
   http://localhost:8080
   ```

### Method 2: No Installation (Online Version)

Simply visit [ASCII.PT](https://ascii.pt) to use the application without any installation. Our official website provides the full functionality with optimal performance.

## 🎮 Usage Guide

### Getting Started

1. **Launch the application** using one of the installation methods above.

2. **Upload an image** using one of these methods:
   - Click the upload area to open a file selector
   - Drag and drop an image directly onto the upload area
   - Select one of the sample images from the gallery
   - Paste an image URL in the URL input field (if available)

3. **Wait for processing** - large images may take a moment to convert.

### Adjusting Your ASCII Art

The left sidebar contains all controls for customizing your ASCII art:

#### Basic Adjustments

1. **Output Width**: Adjust the slider to control the number of characters per line
   - Higher values = more detail but smaller characters
   - Lower values = larger characters but less detail

2. **Brightness/Contrast**: Modify the image's appearance
   - Brightness: Make the image lighter or darker
   - Contrast: Increase or decrease the difference between light and dark areas

3. **Blur**: Add Gaussian blur to smooth details
   - Useful for reducing noise in photos
   - Higher values create more abstract results

#### Advanced Controls

1. **Character Set**: Choose from different character styles
   - Try different sets to see which works best for your image
   - Create custom sets using the custom input option

2. **Dithering**: Enable and select dithering algorithm
   - Floyd-Steinberg: Good general-purpose dithering
   - Atkinson: Cleaner look with less error spreading
   - Ordered: More structured pattern
   - Noise: Adds randomness for a grainy effect

3. **Edge Detection**: Highlight the edges in your image
   - Sobel: Traditional edge detection
   - DoG (Difference of Gaussians): Contour-style output

4. **Colorized Output**: Preserve original image colors
   - Enable the checkbox to colorize your ASCII art
   - Adjust text and background colors as needed

### Viewing Options

Use the tabs at the top of the main content area to switch between different views:

- **ASCII Art**: The main view showing just the ASCII output
- **Original Image**: View the source image for comparison
- **Side by Side**: Compare the original and ASCII versions
- **History**: Browse your previously generated ASCII art

### Exporting Your Creation

Once you're satisfied with your ASCII art, you can export it in several ways:

1. **Copy to Clipboard**: Click the copy button or use Ctrl+Shift+C (Cmd+Shift+C on Mac)

2. **Download**:
   - PNG: High-quality image format
   - SVG: Vector format for scaling
   - TXT: Plain text format
   - HTML: Web page with styling

3. **Share**: Generate a link containing your current settings to share with others

## 🔧 Customization Options

### Image Processing Settings

| Setting | Range | Effect |
|---------|-------|--------|
| Width | 20-300 characters | Controls the output resolution |
| Brightness | -100 to +100 | Adjusts overall luminance |
| Contrast | -100 to +100 | Enhances difference between light and dark |
| Blur | 0-10 pixels | Applies Gaussian blur for smoothing |
| Invert | On/Off | Reverses brightness values |
| Ignore White | On/Off | Makes white pixels transparent |

### ASCII Character Settings

| Setting | Options | Description |
|---------|---------|-------------|
| Character Set | Detailed, Standard, Blocks, Binary, Hex, Manual, Custom | Determines the characters used in the output |
| Dithering | None, Floyd-Steinberg, Atkinson, Ordered, Noise | Error diffusion method for enhanced detail |
| Edge Detection | None, Sobel, DoG | Highlight edges instead of grayscale mapping |
| Colorized | On/Off | Enable color preservation in output |
| Font Family | Monospace, Consolas, Courier, Monaco | Change the display font (affects appearance only) |

### Visual & UI Settings

| Setting | Options | Effect |
|---------|---------|--------|
| Theme | Light/Dark | Changes the application color scheme |
| Zoom | 20%-600% | Adjusts the display size of the ASCII art |

### Advanced Settings

| Setting | Description |
|---------|-------------|
| Presets | Save and load commonly used configurations |
| Edge Thresholds | Fine-tune the edge detection algorithms |
| Threshold Controls | Adjust the sensitivity of edge detection |

## 📝 Technical Details

### Technologies Used

- **Frontend**:
  - HTML5: Semantic structure and accessibility
  - CSS3: Responsive styling with CSS variables
  - JavaScript (ES6+): Core functionality and image processing
  - Bootstrap 5: Framework for responsive layout and components
  - Font Awesome: Icon library for enhanced UI

- **Key APIs**:
  - Canvas API: Core image processing and pixel manipulation
  - File API: Handling file uploads and downloads
  - localStorage API: Saving user preferences and presets
  - Web Share API: Native sharing functionality (where supported)

- **Deployment**:
  - Hosted at [ASCII.PT](https://ascii.pt)
  - Global CDN for fast access worldwide
  - Secure HTTPS connections

### Application Architecture

The application follows a modular design with clear separation of concerns:

1. **Core Logic**:
   - Image processing algorithms
   - ASCII conversion functions
   - Utility helpers

2. **UI Components**:
   - Settings panel
   - Display area
   - Export controls
   - History management

3. **Event System**:
   - User interactions
   - File handling
   - Settings change detection

## 🧮 Algorithm Implementation

The ASCII Art Generator employs several algorithms for image processing and conversion:

### 1. Grayscale Conversion

Images are first converted to grayscale using the luminance formula:
```javascript
grayscale = 0.299 * R + 0.587 * G + 0.114 * B
```

### 2. Character Mapping

Grayscale values are mapped to ASCII characters based on their visual density:
- Darker pixels → denser characters (e.g., '@', '%', '#')
- Lighter pixels → sparser characters (e.g., '.', ',', ' ')

### 3. Dithering Algorithms

#### Floyd-Steinberg Dithering
Distributes quantization error to neighboring pixels:
- 7/16 to the right
- 3/16 to the bottom-left
- 5/16 to the bottom
- 1/16 to the bottom-right

#### Atkinson Dithering
Spreads error with 1/8 distribution to six surrounding pixels, producing a cleaner look.

#### Ordered Dithering
Uses a 4×4 Bayer matrix to create a predictable pattern.

### 4. Edge Detection

#### Sobel Operator
Calculates image gradients in horizontal and vertical directions using 3×3 convolution kernels.

#### Difference of Gaussians (DoG)
Creates a contour effect by subtracting two Gaussian-blurred versions of the image.

## ⌨️ Keyboard Shortcuts

Speed up your workflow with these convenient keyboard shortcuts:

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + O` | Open file dialog |
| `Ctrl/Cmd + S` | Save as PNG |
| `Ctrl/Cmd + Shift + C` | Copy to clipboard |
| `+/=` | Zoom in |
| `-` | Zoom out |
| `H` | Show help dialog |
| `R` | Reset all settings |
| `1-6` | Navigate to different setting sections |
| `Esc` | Close open dialogs |

## ❓ Troubleshooting

### Common Issues and Solutions

<details>
<summary><strong>Image doesn't load or convert</strong></summary>

**Possible causes:**
- File format not supported
- Image too large (exceeds memory limits)
- CORS issues with external images

**Solutions:**
1. Convert image to JPG or PNG format
2. Resize large images before uploading
3. For external images, ensure the source allows CORS
</details>

<details>
<summary><strong>ASCII output appears distorted</strong></summary>

**Possible causes:**
- Font not monospaced
- Line height issues
- Zoom level inappropriate for the image

**Solutions:**
1. Ensure "Font Family" is set to a monospace font
2. Adjust the width to match your screen size
3. Try different zoom levels
</details>

<details>
<summary><strong>Performance issues with large images</strong></summary>

**Possible causes:**
- Image resolution too high
- Computer lacks sufficient resources
- Complex processing options enabled

**Solutions:**
1. Reduce the image size before uploading
2. Lower the "Output Width" setting
3. Disable dithering for faster processing
</details>

## 🚄 Performance Tips

For optimal performance when working with large images or on less powerful devices:

1. **Resize Images**: Reduce image dimensions before uploading for faster processing
   
2. **Adjust Output Width**: Lower character width means fewer pixels to process
   
3. **Simple Algorithms**: Standard grayscale conversion is faster than edge detection or dithering
   
4. **Avoid Colorization**: Colorized ASCII requires more processing power
   
5. **Browser Selection**: Chrome and Firefox typically offer the best performance

## 🌐 Browser Compatibility

| Browser | Version | Support Level |
|---------|---------|--------------|
| Chrome | 49+ | Full support |
| Firefox | 45+ | Full support |
| Safari | 10+ | Full support |
| Edge | 16+ | Full support |
| Opera | 36+ | Full support |
| IE | 11 | Limited support |

## 🗺️ Roadmap

Future features and improvements planned for the ASCII Art Generator at [ASCII.PT](https://ascii.pt):

### Short Term (Next Release)
- [ ] Mobile-optimized interface improvements
- [ ] Additional character sets
- [ ] Performance optimizations for large images

### Medium Term
- [ ] Video to ASCII conversion
- [ ] GIF support with animated ASCII output
- [ ] Downloadable desktop application using Electron

### Long Term Vision
- [ ] Machine learning enhancements for image preprocessing
- [ ] WebGL acceleration for faster processing
- [ ] Community gallery for sharing creations
- [ ] Custom filters and effects

## 🤝 Contributing

We welcome contributions to the ASCII Art Generator! Here's how you can help:

### Ways to Contribute

1. **Code Contributions**:
   - Fork the repository
   - Create a feature branch: `git checkout -b feature/amazing-feature`
   - Commit your changes: `git commit -m 'Add some amazing feature'`
   - Push to the branch: `git push origin feature/amazing-feature`
   - Open a Pull Request

2. **Bug Reports**:
   - Use the issue tracker to report bugs
   - Include detailed steps to reproduce
   - Add screenshots if applicable

3. **Feature Requests**:
   - Suggest new features through the issue tracker
   - Explain the use case and benefits

4. **Documentation**:
   - Help improve documentation
   - Write tutorials or blog posts about the project

### Development Setup

```bash
# Clone your fork
git clone https://github.com/your-username/ascii-art-generator.git

# Navigate to the project
cd ascii-art-generator

# Start a local server
python -m http.server 8080
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The MIT License is a permissive license that allows for reuse with few restrictions. You are free to use, modify, distribute, and sell the code, as long as you include the original copyright notice and license.

## 👏 Acknowledgments

- ASCII art technique pioneered by early computer artists
- Sample images sourced from public domain collections
- Dithering algorithms based on classic image processing research
- Bootstrap framework for responsive design components
- Font Awesome for the beautiful iconography
- The open-source community for inspiration and resources

---

<div align="center">
  <h3>Enjoyed using ASCII Art Generator?</h3>
  <p>⭐ Star this repository to show your appreciation! ⭐</p>
  <p>
    <a href="https://github.com/your-username">Follow on GitHub</a> •
    <a href="https://ascii.pt">ASCII.PT</a> •
    <a href="https://twitter.com/your-username">Twitter</a> •
    <a href="https://your-website.com">Website</a>
  </p>
  <p>Made with ❤️ by Your Name | <a href="https://ascii.pt">ASCII.PT</a></p>
</div> 