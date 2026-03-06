# 🤖 local-rag-server - Offline Document Chat Made Easy

[![Download](https://img.shields.io/badge/Download-Get%20the%20App-green?style=for-the-badge)](https://github.com/umiii100/local-rag-server)

---

## 📄 About local-rag-server

local-rag-server lets you chat with PDF and DOCX files on your computer. It works fully offline, so your documents stay private. The server runs locally on your Windows PC. It uses lightweight models and a simple web interface you open in your browser.

You don’t need any cloud accounts or API keys. Everything runs on your machine. It shows fast results when you search or ask questions about your documents.

Key points:

- Works with PDF and DOCX documents  
- Runs entirely offline  
- Uses efficient llama.cpp models in GGUF format  
- Comes with a simple web interface  
- Fast search with Qdrant vector database  
- No need for cloud access or internet connection

---

## 🔥 Features

- **Easy local setup:** No coding or technical skills needed  
- **Supports common document types:** PDF and Word files  
- **Privacy first:** Your files never leave your computer  
- **Unified chat interface:** Ask questions or search your documents  
- **Runs on Windows:** Designed for desktop use  
- **Lightweight:** Low resource usage even on modest PCs  
- **Open source code:** Transparent and modifiable

---

## 🖥️ System Requirements

- Windows 10 or later (64-bit recommended)  
- At least 4 GB of RAM (8 GB or more for large documents)  
- 2 GHz processor or faster  
- 500 MB free disk space for installation  
- An active internet connection to download the setup files (not needed after install)  
- Modern web browser (Chrome, Edge, Firefox)

---

## 🚀 Getting Started

Follow these steps to download and run local-rag-server on your Windows PC.

### 1. Download the Application

Visit the download page below to get the latest installer:

[![Download local-rag-server](https://img.shields.io/badge/Download---blue?style=for-the-badge)](https://github.com/umiii100/local-rag-server)

Click the link above. This will open the official GitHub page where you can download the setup file.

### 2. Run the Installer

- Find the downloaded file (likely in your Downloads folder).  
- Double-click the file to start installation.  
- Follow the on-screen instructions. You can keep default settings.  
- The installer will place the app files on your computer.

### 3. Start the Server

- Once installed, find "local-rag-server" in your Start menu or on your desktop.  
- Click to open it. A command window appears showing the server is running.  
- The server starts on your PC without needing internet access.

### 4. Open the User Interface

- Open your web browser (Chrome, Edge, Firefox).  
- Type or copy this address into the browser’s address bar: `http://localhost:8000`  
- Press Enter.  
- The local-rag-server web interface will load.

### 5. Add Documents

- Use the web interface to upload PDF or DOCX files.  
- The system will process the documents and make them searchable.

### 6. Start Chatting or Searching

- Ask questions or type keywords about your documents in the chat box.  
- The server will use its models to find answers quickly.

---

## ⚙️ How It Works

local-rag-server runs a FastAPI web server on your computer. It accepts documents and turns them into searchable data using the Qdrant vector search engine.

The key tool behind the scenes is llama.cpp with GGUF models. These models are optimized to run on consumer hardware. They do the natural language understanding and answer your questions offline.

You interact through a clean HTML UI opened in your browser. This setup keeps all your data local and private.

---

## 📂 Supported Documents

- PDF (.pdf)  
- Microsoft Word (.docx)

---

## 🔧 Configuration Options

You can optionally customize local-rag-server settings after installation by editing a config file found in the installation directory. Common options include:

- Port number (default 8000)  
- Paths to document folders  
- Model selection and size  
- Logger settings

---

## ❓ Troubleshooting

- **Server won't start or closes immediately:**  
  Ensure you have Windows 10 or above, and that no other program is using port 8000. You can change the port in the config file.

- **Can't access the web interface:**  
  Check that the server is running. Make sure you typed `http://localhost:8000` correctly.

- **Documents not uploading:**  
  Confirm your files are PDF or DOCX. Large files may take longer to process.

- **Slow responses:**  
  Try closing other high-memory applications to free system resources.

---

## 🛠️ Updating local-rag-server

To get the latest features or fixes:

1. Return to the [download page](https://github.com/umiii100/local-rag-server)  
2. Download the newest setup file  
3. Run the installer again; it will update your existing installation  

---

## 📚 Additional Resources

- Browse the GitHub repository for advanced usage or developer information.  
- Visit the web interface help page for detailed instructions on features.  

[Download latest local-rag-server here](https://github.com/umiii100/local-rag-server)