# WhatsApp Quick Message

A single-page web application that converts Israeli phone numbers into WhatsApp message links, allowing you to send messages without adding contacts to your phone.

## Features

- 📱 **Auto-paste detection**: Automatically detects and processes phone numbers from clipboard on focus
- 🇮🇱 **Israeli number support**: Handles all common Israeli phone number formats:
  - `050-123-4567`
  - `+972 50 123 4567`
  - `0501234567`
  - `972501234567`
- ✨ **Real-time formatting**: Shows properly formatted international number
- 🚀 **One-click WhatsApp**: Direct link to open WhatsApp chat
- 📱 **Mobile-friendly**: Optimized for iPhone and mobile browsers
- ⚡ **No contact required**: Opens WhatsApp without adding to contacts

## How to Use

1. Open `index.html` in your web browser
2. Paste or type an Israeli phone number in any common format
3. Click "Generate WhatsApp Link" or press Enter
4. Click "Open WhatsApp Chat" to start messaging

## Supported Formats

The app automatically converts these formats to WhatsApp-compatible links:

| Input Format | Example | Output |
|-------------|---------|---------|
| Mobile with dashes | `050-123-4567` | `+972 50-123-4567` |
| International | `+972 50 123 4567` | `+972 50-123-4567` |
| Compact | `0501234567` | `+972 50-123-4567` |
| Without leading 0 | `501234567` | `+972 50-123-4567` |

## Technical Details

- Pure HTML, CSS, and JavaScript - no dependencies
- Works offline after initial load
- Clipboard API integration for auto-paste (where supported)
- Mobile-optimized UI with WhatsApp-inspired design
- Error validation for invalid numbers

## Browser Compatibility

Works on all modern browsers including:
- Safari (iOS/macOS)
- Chrome (Android/Desktop)
- Firefox
- Edge

## File Structure

```
whatsapp quick message/
├── index.html          # Main application file
└── README.md          # This documentation
```

## Running the App

Simply open `index.html` in any web browser. No server required!