<div align="center">

<img src="https://i.postimg.cc/50sjfv65/topicon.png" alt="ChatBridge Logo" width="200">

# ChatBridge

**Seamlessly transfer your AI conversations between platforms**

Extract your current AI chat and instantly transfer it to another AI or save it locally. Zero network calls. Complete privacy.

[![Chrome Web Store](https://img.shields.io/badge/Chrome-Extension-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chrome.google.com/webstore)
[![Version](https://img.shields.io/badge/Version-1.5.0-green?style=for-the-badge)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)
[![Manifest V3](https://img.shields.io/badge/Manifest-V3-orange?style=for-the-badge)](https://developer.chrome.com/docs/extensions/mv3)

**⭐ If you find this useful, please star the repo — it helps others discover it!**

</div>

---

## 🚀 Install in 60 Seconds (No coding required)

ChatBridge isn't on the Chrome Web Store *yet*, but installing it manually only takes a minute:

1. **Download the extension**
   - Click the green **`< > Code`** button at the top of this repo → **Download ZIP**
   - Or grab [`chatbridge chrome.zip`](https://github.com/vaibhavchawla2970/ChatBridge/blob/main/chatbridge%20chrome.zip) directly
2. **Unzip the file** anywhere on your computer (e.g. Desktop)
3. Open Chrome and go to `chrome://extensions`
4. Turn on **Developer mode** using the toggle in the top-right corner
5. Click **Load unpacked** (top-left) and select the unzipped ChatBridge folder
6. Pin ChatBridge to your toolbar (click the puzzle-piece icon → pin ChatBridge) so it's always one click away

That's it — you're ready to transfer chats. ✅

> 💡 **Note:** Chrome may show a "Developer mode extensions" warning bar. This is normal for any extension installed outside the Web Store and doesn't affect functionality.

### From Chrome Web Store
*Coming soon — star/watch the repo to get notified when it's live.*

---

## Features

- **Instant Transfer** — Move conversations from one AI to another in one click
- **Save Locally** — Export chats as beautifully formatted HTML files
- **100% Private** — All processing happens locally. Zero network calls. Your data never leaves your browser
- **Smart Detection** — Automatically detects which AI platform you're using
- **Custom AI Support** — Add any AI chat platform, even if it's not built-in
- **Dark Mode** — Full support for light and dark themes
- **Lightweight** — Minimal footprint, maximum performance

---

## Supported Platforms

| Platform | Transfer To | Save as HTML |
|----------|:-----------:|:------------:|
| ChatGPT | ✅ | ✅ |
| Claude | ✅ | ✅ |
| Gemini | ✅ | ✅ |
| Grok | ✅ | ✅ |
| Z.ai | ✅ | ✅ |
| DeepSeek | ✅ | ✅ |
| Copilot | ✅ | ✅ |
| Perplexity | ✅ | ✅ |
| Mistral | ✅ | ✅ |
| Custom URLs | ✅ | ✅ |

---

## Screenshots

<div align="center">

### Extension Popup
<img src="https://i.postimg.cc/76x2NwF1/extenion.png" alt="Extension Popup" width="400">

### Chat Export Feature
<img src="https://i.postimg.cc/tTXxzpKP/chat-export.png" alt="Chat Export" width="400">

### Exported Chat in ChatGPT
<img src="https://i.postimg.cc/Y9pWxM53/showing-chat-export-in-chatgpt.png" alt="Chat Export in ChatGPT" width="400">

### Full Page View
<img src="https://i.postimg.cc/LXH1V2cV/whole-page.png" alt="Full Page View" width="400">

</div>

---

## How It Works

1. Open any supported AI chat platform
2. Click the ChatBridge icon in your browser toolbar
3. Choose your action:
   - **Save as HTML** — Downloads a beautifully formatted HTML file
   - **Transfer to another AI** — Opens the target AI and pastes your conversation
4. Continue your conversation where you left off

---

## Installing From Source (for developers)

```bash
git clone https://github.com/vaibhavchawla2970/ChatBridge.git
```

1. Go to `chrome://extensions/`
2. Enable **Developer mode**
3. Click **Load unpacked**
4. Select the cloned `ChatBridge` folder

---

## Adding Custom AI Platforms

ChatBridge lets you add any AI chat platform:

1. Click the **+** button in the extension popup
2. Enter the **AI Name** (e.g., "Pi", "Character.ai")
3. Enter the **Chat URL** (e.g., "https://character.ai")
4. Click **Save AI**

Your custom platform will now appear in the transfer options.

---

## Privacy and Security

ChatBridge is built with privacy as a core principle:

- **Zero network calls** — Everything happens locally in your browser
- **No data collection** — We don't collect, store, or transmit any user data
- **No analytics** — No tracking, no telemetry, no cookies
- **Open source** — Full transparency, inspect the code yourself

---

## Technical Details

- **Manifest Version:** 3
- **Permissions:** Minimal (`activeTab`, `scripting`, `storage`, `tabs`, `downloads`)
- **Architecture:** Modular extractors and injectors for each platform
- **Storage:** Chrome local storage for custom configurations only

---

## Contributing

Contributions are welcome. Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Setup

```bash
npm install
```

1. Go to `chrome://extensions/`
2. Enable Developer mode
3. Click "Load unpacked"
4. Select the project folder

---

## FAQ

**Is this safe to install without the Chrome Web Store?**
Yes — ChatBridge is fully open source, so you (or anyone) can inspect every line of code before installing. It requests only the minimal permissions needed to function, and makes zero network calls.

**Will Chrome disable the extension after I close my browser?**
No, once loaded it stays installed. You may occasionally see a "Disable developer mode extensions" reminder — just ignore/dismiss it.

**Does my data ever leave my browser?**
No. All extraction and formatting happens locally on your device.

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made by Vaibhav Chawla Using AI

</div>
