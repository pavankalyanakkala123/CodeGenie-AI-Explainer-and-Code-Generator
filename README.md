# 🤖 CodeGenie AI: Ollama Chatbot with PaddleOCR Integration




---


## 🌟 Overview

This is a **complete, ready-to-use web application** that combines three powerful capabilities:

- 🤖 **AI Chat** – Local AI model (`phi3:mini`) for intelligent, context‑aware conversations.
- 📸 **OCR** – Advanced text extraction from images in **109+ languages** using PaddleOCR.
- 💬 **Web UI** – Modern, user‑friendly interface powered by **Streamlit**.
- 💾 **History** – Automatic chat persistence and recovery.

The application runs entirely on your computer with **NO external cloud dependencies**, ensuring complete privacy and offline functionality.

---

## ❗ Problem Statement

In today’s digital world, users need quick access to AI‑powered assistance and the ability to extract text from images. However:

- **Cloud‑based AI tools** raise privacy concerns and require constant internet connectivity.
- **Separate tools** for chat and OCR lead to workflow fragmentation.
- **Complex setup** often deters non‑technical users from leveraging local AI models.
- **No built‑in chat history** forces users to manually save conversations.

**CodeGenie AI** solves these issues by delivering a **single, offline‑first, privacy‑focused** application that integrates AI chat and OCR in a user‑friendly interface.

---

## 💡 Solution

Our application provides a **unified platform** where users can:

- **Chat with a local AI model** (`phi3:mini`) in real‑time, with streaming responses and context memory.
- **Upload images** (JPG, PNG, BMP, TIFF) and extract text with high accuracy using PaddleOCR.
- **Ask AI questions** about the extracted text, combining OCR and chat capabilities.
- **Automatically save and manage** conversation history for later reference.
- **Customize settings** (streaming toggle, OCR language) to suit individual preferences.

All processing happens **locally** – no data leaves your machine.

---

## 📊 Quick Facts

| Fact | Detail |
|------|--------|
| **Python Version** | 3.9 – 3.13 (3.13.2 tested) |
| **RAM** | 8 GB minimum, 16 GB recommended |
| **Storage** | ~10 GB free space |
| **OS Support** | Windows 10/11, Ubuntu 20.04+, macOS 10.14+ |
| **AI Model** | Ollama `phi3:mini` (2.2 GB) |
| **OCR Engine** | PaddleOCR (109+ languages) |
| **Web Framework** | Streamlit |
| **Setup Time** | 15–30 minutes |
| **Privacy** | 100% local – no cloud dependencies |
| **License** | MIT |

---

## 💻 System Requirements

### Operating System
- Windows 10/11 (Primary – Tested)
- Ubuntu 20.04+ Linux
- macOS 10.14+

### Hardware
- **Processor:** Multi‑core (4+ cores recommended)
- **RAM:** 8 GB minimum, 16 GB recommended for smooth performance
- **Storage:** 10 GB free space (for models and data)
- **Network:** Internet access **only** for initial downloads (models & packages)

### Python
- **Version:** 3.9, 3.10, 3.11, 3.12, or 3.13
- **Recommended:** 3.13.2 (tested)
- [Download Python](https://www.python.org/downloads/)

---

## 🚀 Getting Started (5–10 Minutes)

1. INSTALL PYTHON
   - Download Python from https://www.python.org/downloads/
   - Run installer, CHECK "Add Python to PATH"
   - Verify: Open terminal, type "python --version"

2. INSTALL OLLAMA
   - Download from https://ollama.ai/
   - Run installer, follow instructions
   - Open terminal and run: ollama pull phi3:mini
   - Wait 5-10 minutes for model download (2.2 GB)

3. SETUP PROJECT
   - Navigate to this project folder
   - Windows: Open PowerShell here
   - Create virtual environment:
     
     python -m venv .venv
     .venv\Scripts\Activate.ps1
   
   - Install dependencies:
     
     pip install -r requirements.txt

4. RUN THE APPLICATION
   
   Terminal 1: Start Ollama server
     ollama serve
   
   Terminal 2: Run the app
     streamlit run app6.py
   
   Browser opens automatically to:
     http://localhost:8501

5. START USING
   - Type messages to chat with AI
   - Upload images to extract text
   - Chat history saves automatically

---
## FEATURES
CHAT WITH AI:
  ✓ Real-time AI responses (streaming)
  ✓ Context-aware conversations
  ✓ Automatic chat history
  ✓ Switch between past conversations
  ✓ Delete conversations anytime

IMAGE TEXT EXTRACTION (OCR):
  ✓ Upload JPG, PNG, BMP, TIFF files
  ✓ Automatically extract text
  ✓ Confidence scores for accuracy
  ✓ Supports 109+ languages
  ✓ Ask AI about extracted text

SMART FEATURES:
  ✓ Real-time streaming responses
  ✓ Context-aware AI (remembers recent chat)
  ✓ Automatic persistence (no manual save)
  ✓ Modern, responsive UI
  ✓ Settings panel for customization
---

## INSTALLATION STEPS

Step 1: Check Python Installation
  Command: python --version
  Expected: Python 3.9.x or higher

Step 2: Download Ollama
  URL: https://ollama.ai/
  Extract and run installer
  Verify: In terminal, run "ollama --version"

Step 3: Pull AI Model
  Command: ollama pull phi3:mini
  Time: 5-10 minutes
  Size: 2.2 GB
  (Only needed once)

Step 4: Create Virtual Environment
  Windows:
    python -m venv .venv
    .venv\Scripts\Activate.ps1
  
  Linux/macOS:
    python3 -m venv .venv
    source .venv/bin/activate

Step 5: Install Python Packages
  Command: pip install -r requirements.txt
  Time: 5-10 minutes
  Installs: 20+ packages

Step 6: Verify Installation
  Command: python -c "import streamlit; print('OK')"
  Expected: Output "OK"
  DONE! Ready to run.
---

##  RUNNING THE APPLICATION
IMPORTANT: Ollama must be running before starting the app!

Terminal Window 1 - Start Ollama Server:
  Command: ollama serve
  Output: Listening on 127.0.0.1:11434
  Keep this window OPEN

Terminal Window 2 - Start Streamlit App:
  Commands:
    cd <project-folder>
    .venv\Scripts\Activate.ps1         (Windows)
    OR
    source .venv/bin/activate          (Linux/macOS)
    
    streamlit run app6.py

Browser:
  Automatically opens to http://localhost:8501
  Or manually open that URL

Stopping:
  Streamlit: Press Ctrl+C
  Ollama: Press Ctrl+C
---
##   RUNNING THE APPLICATION
IMPORTANT: Ollama must be running before starting the app!

Terminal Window 1 - Start Ollama Server:
  Command: ollama serve
  Output: Listening on 127.0.0.1:11434
  Keep this window OPEN

Terminal Window 2 - Start Streamlit App:
  Commands:
    cd <project-folder>
    .venv\Scripts\Activate.ps1         (Windows)
    OR
    source .venv/bin/activate          (Linux/macOS)
    
    streamlit run app6.py

Browser:
  Automatically opens to http://localhost:8501
  Or manually open that URL

Stopping:
  Streamlit: Press Ctrl+C
  Ollama: Press Ctrl+C
---
## USAGE GUIDE
CHAT WITH AI:
  1. Type your message in the input box at bottom
  2. Press Enter or click Send
  3. AI responds with streaming text
  4. Chat history appears in sidebar
  5. Conversation auto-saved

EXTRACT TEXT FROM IMAGE:
  1. Click "Upload Image for OCR Analysis" (expandable section)
  2. Select an image file (JPG, PNG, BMP, TIFF)
  3. Click "Extract Text with OCR" button
  4. Text extracted and displayed
  5. Results also shown as JSON file
  6. Ask AI questions about the text

MANAGE CONVERSATIONS:
  1. View previous chats in sidebar
  2. Click to switch between conversations
  3. Red trash icon to delete chat
  4. New Chat button to start fresh

SETTINGS:
  1. "Enable Streaming" - Toggle real-time response
  2. "OCR Language" - Choose language for text extraction
  3. Sidebar shows current status
---
##  ACKNOWLEDGMENTS

This application uses:
  • Streamlit - Web framework
  • PaddleOCR - Text recognition
  • Ollama - Local LLM serving
  • Microsoft phi3:mini - AI model
  • LangChain - LLM framework
  • Python ecosystem

All are open-source and freely available.
