💡 [STATUS] planning


# Jira Content Converter Tampermonkey Script 🚀

Transform web content into Jira-ready text with AI-powered formatting! This script lets you seamlessly convert HTML elements (tables, images, text) into Jira-compatible markup while automating image hosting and content optimization.

---

## ✨ **Key Features**
- **Right-Click to Jira Magic**  
  Simply right-click any webpage element → select "Convert to Jira Text" → get instant formatted content.
- **Durable Image Links**  
  Auto-uploads images from Confluence/other sources to **your WebDAV server** to prevent broken links.
- **AI-Powered Cleanup**  
  Uses OpenAI to refine content structure for clarity in Jira descriptions.
- **One-Click Modal Preview**  
  Preview, copy, and paste results directly into Jira issues.

---

## 🛠️ **Quick Start**

### **Installation**
1. Install [Tampermonkey](https://www.tampermonkey.net/) (Browser extension).
2. [Click here to install the script](#) *(add your script URL here)*.

### **First-Time Setup**
1. **Configure Settings** (*Tampermonkey → Dashboard → Script Settings*):
   - OpenAI API Key + Base URL
   - WebDAV Credentials (URL, username, password)
2. **Right-click any content** → Try "Convert to Jira Text"!

---

## 🖱️ **How to Use**
1. **Right-click** a webpage element (e.g., a table, div, or image container).
2. Select **"Convert to Jira Text"** from the context menu.
3. **Preview & Copy** the formatted output from the modal window.
4. **Paste directly into Jira** 🎉

![Demo GIF](#) *(add a short demo GIF/video link here if available)*

---

## 🔧 **Customization**
Tweak the script via Tampermonkey settings:
```javascript
// Example settings (edit in Tampermonkey dashboard)
const USER_CONFIG = {
  OPENAI: {
    API_KEY: "your-api-key",
    BASE_URL: "https://api.openai.com/v1",
    MODEL: "gpt-4-turbo"
  },
  WEBDAV: {
    URL: "https://your-webdav-server.com",
    USERNAME: "user123",
    PASSWORD: "securePassword!"
  }
};
```

⚙️ Dependencies
WebDAV Server: Host images permanently (e.g., Nextcloud, OwnCloud).

OpenAI API Account (any compatible): For content structuring (billed per usage).

❓ Support
Issues? Check the browser console (F12) for errors.

Feature Requests? Open an issue here.

Happy Jira-ing! ✍️
Convert fearlessly, with fewer broken links and more coffee breaks. ☕
