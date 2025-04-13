# OpenWebUI Starter Script

This repository contains a simple batch script to start [OpenWebUI](https://github.com/open-webui/open-webui) from a Python virtual environment and open it in your browser automatically.

## 📦 Prerequisites

- [Python](https://www.python.org/) installed
- `open-webui` installed in a Python virtual environment
- Windows OS (this script is `.bat` format)
- Default browser installed

## 📂 Folder Structure Example

C:\folderwhereopenwebui is
└── openwebui-env
├── Scripts
│ └── activate.bat └── (OpenWebUI installed here) 


## 🚀 How to Use

1. Clone this repo or copy the script file to your project folder.
2. Make sure path matches your actual virtual environment path.
3. Run `start-openwebui.bat` by double-clicking it or from a terminal.

The script will:
- Activate the Python virtual environment
- Start the `open-webui` server in the background
- Open `http://127.0.0.1:8080/` in your default browser

## ⚙️ Customization

- Change the `cd` path if your virtual environment lives elsewhere.
- Adjust the timeout (in seconds) to give the server more or less time to start.
- Want it to wait for the port to open instead of a fixed timeout? Let me know!

## 🧼 Notes

- Make sure the virtual environment has OpenWebUI installed (`pip install open-webui`)
- If you run into permissions issues, try running the script as Administrator.

---

### ✨ Example

```bash
> start-openwebui.bat
