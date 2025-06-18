# PubNub DMN Decision Table Editor

A professional decision table editor built with DMN.js for creating and managing business rules in PubNub applications. Features a clean, PubNub-styled interface with local hosting for maximum reliability.

## ✨ Features

- **Full DMN 1.3 Compliance** - Built on the industry standard DMN.js library
- **Local Hosting** - No external CDN dependencies, works offline
- **Clean PubNub UI** - Professional interface matching PubNub design standards
- **Right-Click Editing** - Intuitive context menus for editing table values
- **Column Name Changes** - Edit column headers and see changes reflected in main table
- **Silent Save** - Clean save process without modal distractions
- **Enhanced UX** - Tooltips, animations, and improved visual feedback

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd <repo-name>
   ```

2. **Open the application:**
   - Open `pubnub-decisions-dmn-local.html` in your web browser
   - No server required - works directly from file system

3. **Start editing:**
   - Click "Edit Decision Table" to enter edit mode
   - Right-click on cells to edit values
   - Right-click on headers to change column names
   - Click "Save Changes" to apply modifications

## 📁 File Structure

```
├── pubnub-decisions-dmn-local.html     # Main application (recommended)
├── assets/
│   ├── dmn-js/                         # DMN.js library files
│   │   ├── css/                        # DMN.js stylesheets
│   │   └── js/                         # DMN.js core library
│   └── ux-tools/                       # UX enhancement libraries
│       ├── animate.min.css             # CSS animations
│       ├── sweetalert2.min.js          # Alert dialogs
│       └── tippy.min.js                # Tooltips
├── README_LOCAL_HOSTING.md             # Local hosting setup guide
└── *.html                              # Other versions and mockups
```

## 🔧 Local vs CDN Versions

- **`pubnub-decisions-dmn-local.html`** ⭐ **Recommended** - Uses local assets, works offline
- **`pubnub-decisions-dmn.html`** - Uses CDN dependencies (requires internet)

## 💡 Usage

### Editing Decision Tables
1. Click "Edit Decision Table" to enter edit mode
2. Right-click on any cell to edit its value
3. Right-click on column headers to rename columns
4. Use the DMN.js interface for advanced table operations
5. Click "Save Changes" to apply and return to view mode

### Column Management
- **Input Columns**: Define conditions (User Tier, Priority, etc.)
- **Output Columns**: Define actions (Target Channel, etc.)
- **Header Editing**: Right-click headers to change column names
- **Auto-sync**: Changes sync between DMN editor and main table display

## 🛠️ Technical Details

- **DMN.js Version**: 16.7.0 (locally hosted)
- **DMN Standard**: 1.3 compliant
- **File Size**: ~3MB total (including all assets)
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Dependencies**: Self-contained, no external requests

## 📋 Example Use Cases

- **Message Routing**: Route messages based on user tier and priority
- **Resource Allocation**: Assign resources based on capacity and demand
- **Access Control**: Grant permissions based on user roles and context
- **Business Rules**: Implement complex business logic visually

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source. Feel free to use, modify, and distribute.

## 🔗 Related Files

- `README_LOCAL_HOSTING.md` - Detailed local asset setup guide
- `setup_instructions.md` - Initial setup instructions
- `troubleshooting_steps.md` - Common issues and solutions 