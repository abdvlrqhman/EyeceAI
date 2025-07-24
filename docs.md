# Eyeceai Documentation

---

## Introduction
Eyeceai is a modern, secure, and user-friendly AI chat platform supporting OpenRouter and custom models. It features a sleek UI, RTL (right-to-left) and LTR (left-to-right) language support, persistent conversations, user memory, and customizable settings. Eyeceai is designed for both everyday users and power users who want a flexible, privacy-focused AI assistant.

---

## Getting Started

### Accessing Eyeceai
Eyeceai is available as a live demo at [abdvlrqhman.com/eyeceai](https://abdvlrqhman.com/eyeceai). No installation or download is required.

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- An OpenRouter API key or a compatible custom model API key

### First Run
1. **Visit** [abdvlrqhman.com/eyeceai](https://abdvlrqhman.com/eyeceai).
2. **Sign in** with your username and API key (OpenRouter or custom model).
3. **Start chatting** with the AI!

---

## Features
- **AI Chat**: Communicate with AI models via OpenRouter or custom endpoints.
- **Multi-Conversation**: Manage multiple chat sessions with persistent history.
- **User Memory**: Store and manage user preferences and memory for context-aware responses.
- **Custom Models**: Add and use custom AI models.
- **Theme Support**: Switch between dark and light themes.
- **RTL/LTR Support**: Automatic direction detection for Arabic and English.
- **File Uploads**: Attach and preview files in chat.
- **Export/Import**: Backup and restore conversations and settings.
- **Responsive Design**: Works on desktop and mobile devices.

---

## Usage Guide

### Basic Workflow
1. **Sign In**: Enter your username and API key to access the app.
2. **Start a Conversation**: Click "New Chat" to begin a new session.
3. **Send Messages**: Type your message and press Enter or click the send button.
4. **Switch Models**: Use the model selector to change between available AI models or add your own.
5. **Upload Files**: Attach files to your messages for richer interactions.
6. **Export/Import Data**: Use the settings panel to backup or restore your data.

### Settings & Customization
- **Theme**: Toggle between dark and light mode.
- **Language Direction**: The app auto-detects Arabic and switches to RTL layout.
- **User Memory**: Add preferences and instructions to personalize AI responses.
- **Auto-Save**: Enable or disable automatic saving of your data.
- **Compact Mode**: Toggle a more condensed UI layout.

### Troubleshooting
- **Login Issues**: Ensure your API key and username are correct. The API key must be valid for OpenRouter or your custom model.
- **No Response from AI**: Check your internet connection and API key validity. If the problem persists, try switching models.
- **Data Loss**: Eyeceai auto-saves your data in the browser's local storage. If data is lost, try importing a backup if available.
- **Corrupted Data**: The app attempts to recover from backups if data corruption is detected. If all else fails, clear all data from settings and start fresh.
- **UI Problems**: Refresh the page or try a different browser.

---

## Customization
- **Themes**: Switch between dark and light modes in settings.
- **Language Direction**: The app auto-detects Arabic and switches to RTL layout.
- **User Memory**: Add preferences and instructions to personalize AI responses.
- **File Uploads**: Attach files to your chat for richer interactions.
- **Custom Models**: Add your own AI models via the settings panel.

---

## File Structure

*Note: The file structure below is for reference only. The demo is available online and not distributed as downloadable files.*
```
/Docs/
  docs.md         # This documentation file
/Seperated/eyecestatics/
  styles.css      # Main CSS for the app UI and themes
  sys.js          # Main JavaScript logic for app state, chat, models, memory, and UI
index.html        # Main HTML entry point for the Eyeceai app
```

---

## Development Guide

### Code Overview
- **`index.html`**: Main entry point. Contains the app structure, embedded styles, and script includes.
- **`sys.js`**: Handles all main logic for app state, chat, models, memory, and UI interactions. Key classes include `AppState`, `DataManager`, and `MemorySystem`.
- **`styles.css`**: Defines the visual style, themes, and responsive layout.

### Best Practices
- Keep your API keys secure. They are stored in local storage for convenience but can be cleared at any time.
- Use the export feature regularly to backup your data.
- When developing new features, follow the modular structure in `sys.js` for maintainability.
- Test changes in multiple browsers for compatibility.

### Contributing
Currently, Eyeceai is a proprietary project. For contributions, bug reports, or feature requests, please contact the author directly.

---

## FAQ

**Q: What is Eyeceai?**
A: Eyeceai is a web-based AI chat platform supporting OpenRouter and custom models, with multi-conversation, memory, and customization features.

**Q: How do I get an API key?**
A: Register at [OpenRouter](https://openrouter.ai/) or use your own compatible model's API key.

**Q: Where is my data stored?**
A: All data is stored locally in your browser's local storage. You can export/import data for backup or migration.

**Q: Can I use Eyeceai offline?**
A: The app UI works offline, but AI chat requires an internet connection and a valid API key.

**Q: How do I reset or clear my data?**
A: Go to Settings > Data & Models > Clear All Data. This will remove all conversations, memory, and settings.

**Q: How do I add a custom model?**
A: In Settings, use the "Add Model" button and provide the required details.

**Q: I see an error or the app is not working. What should I do?**
A: Try refreshing the page, checking your API key, or clearing your data. If the issue persists, contact the author.

---

## Advanced Usage

### Keyboard Shortcuts
- **Ctrl/Cmd + K**: Start a new conversation quickly.
- **Enter**: Send message (Shift+Enter for new line).
- **Escape**: Close modals or settings panel.

### Power User Tips
- **Personalize AI**: Use the memory and instructions fields in settings to guide the AI’s responses to your style and preferences.
- **Export Regularly**: Use the export feature to back up your data, especially before clearing your browser storage or switching devices.
- **Custom Models**: Add multiple custom models for different tasks and switch between them as needed.
- **File Previews**: Attach code snippets, text, or images to your messages for richer context.

---

## Privacy & Security
- **Local Storage**: All your data (conversations, memory, settings, API keys) is stored locally in your browser. No data is sent to any server except for AI requests to the selected model endpoint.
- **API Keys**: Your API key is only used to authenticate requests to the AI provider (e.g., OpenRouter). It is never sent anywhere else.
- **Clearing Data**: Use the "Clear All Data" option in settings to remove all personal data from your browser.
- **Backups**: Export your data regularly to avoid accidental loss.
- **Open Source**: Review the code to verify privacy claims (if source is available to you).

---

## Changelog

**v4.0**
- Major UI/UX redesign
- RTL (Arabic) and LTR (English) support
- Multi-conversation management
- User memory and instructions
- Custom model support
- File upload and preview
- Export/import and backup system
- Responsive design for mobile/desktop

**v3.x and earlier**
- Initial releases with basic chat and OpenRouter support

---

## License
This project is proprietary. Contact the author for licensing information. 
