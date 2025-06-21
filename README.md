# 🤖 My AI Chat Bot - Powered by WebLLM

A beautiful, modern AI chat bot that runs **completely in your browser** using WebLLM! No servers, no API keys, and all your conversations stay private on your device.

## ✨ Features

- 🌐 **Runs entirely in your browser** - No server required!
- 🔒 **100% Private** - All processing happens locally
- 🚀 **Hardware Accelerated** - Uses WebGPU for fast inference
- 💬 **Real-time Streaming** - See responses as they're generated
- 📱 **Mobile Friendly** - Works on desktop and mobile devices
- 🎨 **Beautiful UI** - Modern, responsive design
- 🔄 **Multiple AI Models** - Choose from various pre-built models

## 🚀 Live Demo

Visit your GitHub Pages site at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## 🛠️ How It Works

This chat bot uses [WebLLM](https://github.com/mlc-ai/web-llm), which brings Large Language Models directly to your browser using:

- **WebGPU** for hardware acceleration
- **WebAssembly** for optimal performance  
- **IndexedDB** for model caching
- **OpenAI-compatible API** for easy integration

## 📋 Browser Requirements

- **Chrome 113+** or **Edge 113+** (WebGPU support required)
- **At least 8GB RAM** recommended for larger models
- **Good internet connection** for initial model download (2-4GB)

## 🎯 Supported Models

The app includes several pre-built AI models:
- **Llama 3.1** - General purpose chat model
- **Phi 3** - Compact but powerful model
- **Gemma** - Google's efficient model
- **Qwen** - Multilingual model
- And more!

## 💡 Usage Instructions

1. **Choose a Model**: Select an AI model from the dropdown
2. **Download & Start**: Click the button to download and initialize the model
3. **Wait for Download**: First time will take a few minutes (models are cached after)
4. **Start Chatting**: Type your message and press Enter or click Send
5. **Enjoy**: Have conversations with your personal AI assistant!

## 🔧 Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript (ES6 modules)
- **AI Engine**: WebLLM with WebGPU acceleration
- **Model Format**: MLC (Machine Learning Compilation) format
- **Caching**: Browser IndexedDB for persistent model storage
- **Streaming**: Real-time response generation
- **Mobile Support**: Responsive design for all screen sizes

## 🚀 Deployment on GitHub Pages

This project is designed to work perfectly with GitHub Pages. The single `index.html` file contains everything needed.

## 🤝 Contributing

Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Share your experience

## 📜 License

This project uses WebLLM which is licensed under Apache 2.0. See the [WebLLM repository](https://github.com/mlc-ai/web-llm) for details.

## 🙏 Acknowledgments

- Thanks to the [MLC-AI team](https://github.com/mlc-ai) for creating WebLLM
- Built with love for the open-source AI community

---

**⚡ Powered by WebLLM - Bringing AI to everyone, everywhere!**
