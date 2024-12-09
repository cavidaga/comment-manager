# Comment Manager Pro

A browser extension for bulk comment management on social media platforms. Compatible with both Chrome and Firefox, this extension allows users to efficiently manage multiple comments simultaneously through an intuitive interface with delete, hide, and block functionality.

## 🌟 Features

- **Cross-Browser Support**: Works on both Chrome and Firefox
- **Bulk Selection**: Automatically adds checkboxes to all comments for easy selection
- **Multiple Actions**: Three main functions available:
  - Delete multiple comments
  - Hide multiple comments
  - Block multiple users
- **Dynamic Updates**: Automatically detects and adds checkboxes to new comments as they load
- **Visual Interface**: Floating action buttons with clear icons for each operation
- **Smart Processing**: Sequential processing with built-in delays to ensure reliable operation

## 🛠️ Installation

### Chrome Development Installation

1. Clone this repository:
```bash
git clone https://github.com/cavidaga/comment-manager.git
```

2. Open Chrome and navigate to `chrome://extensions/`

3. Enable "Developer mode" in the top right corner

4. Click "Load unpacked" and select the extension directory

### Firefox Development Installation

1. Clone this repository (if you haven't already):
```bash
git clone https://github.com/cavidaga/comment-manager.git
```

2. Open Firefox and navigate to `about:debugging`

3. Click "This Firefox" in the left sidebar

4. Click "Load Temporary Add-on"

5. Navigate to the extension directory and select the manifest file

## ⚙️ Configuration

The extension uses the following default configurations:
- Processing delay: 2000ms between actions
- Button positions: Fixed at bottom-left of the screen
- Icon sizes: 30x30 pixels

## 🌐 Browser Compatibility

### Chrome
- Works on Chrome version 88 and above
- Uses Chrome extension manifest V3

### Firefox
- Works on Firefox version 109 and above
- Uses Firefox add-ons standards

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## ⚠️ Disclaimer

This extension is intended for legitimate comment management purposes. Please use responsibly and in accordance with platform terms of service.

## 📧 Support

For support, please open an issue in the GitHub repository or contact cavid [at] cavid [dot] info