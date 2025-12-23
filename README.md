# AI Voice Assistant

An AI-powered voice assistant built with **React** and **TypeScript**, integrating **Hugging Face Inference API** for real-time natural language understanding, speech recognition, and text-to-speech. Designed as a practical ML-enabled frontend application demonstrating AI integration in production-ready web apps.

## Key Features

- 🎙️ **Speech Recognition** using Web Speech API  
- 🔊 **Text-to-Speech (TTS)** for AI-generated responses  
- 🤖 **LLM Integration** via Hugging Face (LLaMA-based models)  
- ⚡ **Streaming Responses** for real-time interaction  
- 📱 **Responsive UI** with modern frontend practices  

## Tech Stack

- **React (18)**
- **TypeScript**
- **Tailwind CSS**
- **Hugging Face Inference API**
- **Web Speech API**
- **Lucide React Icons**

## Architecture Overview

- Frontend handles voice input, UI state, and streaming output
- Hugging Face API processes user prompts and generates responses
- Modular hooks manage speech recognition and synthesis
- Typed services layer for clean AI API integration

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Master-Dev201/ai-voice-assistant.git
cd ai-voice-assistant
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file:

```env
VITE_HUGGINGFACE_API_KEY=your_huggingface_api_key
```

### 4. Run the application

```bash
npm run dev
```

## Usage

* Click the **microphone** to start or stop voice input
* Speak or type a prompt
* Receive **AI-generated responses** with optional speech output

## Use Case Relevance (ML Profile)

* Demonstrates **LLM inference integration**
* Practical example of **AI-powered UX**
* Clean separation of AI, speech, and UI layers
* Suitable for portfolios in **ML Engineering**, **AI Applications**, and **Frontend + AI** roles
