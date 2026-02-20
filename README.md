📦 Lake Victoria Basin Water Board

A simple HTML project that demonstrates layered content and interactive features.
⚠️ Opening the file directly (file://) will not load all layers correctly.
You must run it on a local server for full functionality.

🚨 Why a Local Server is Required

This project uses features that browsers restrict when opening files directly, such as:

Loading layered content

Fetching local resources

JavaScript modules

Relative paths

Running a local server resolves these issues.

▶️ Getting Started
1️⃣ Clone the Repository
git clone https://github.com/elninja336/lvbwb.git
cd lvbwb
🚀 Run the Project Locally

Choose one of the methods below.

✅ Option 1: Python (Recommended – No extra setup)

Most systems already have Python installed.

python -m http.server 8000

Then open your browser and go to:

http://localhost:8000
✅ Option 2: Node.js Live Server (Auto Reload)

If you have Node.js installed:

npm install -g live-server
live-server

This will automatically open the project in your browser and reload when files change.


🛠 ⚙️ 🧰 Troubleshooting: Local Server & Layer Loading Issues (Lake Victoria Basin Water Board)

If the project isn’t loading all layers correctly, the most common cause is opening the site directly using file://. This project must be served over http:// using a local server.

✅ Quick Checklist

Do not open index.html by double-clicking it.

Start a local server (Python or live-server).

Open in your browser using:

http://localhost:8000 (Python)

or the URL live-server prints (usually http://127.0.0.1:8080)