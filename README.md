# 🚀 AADAT - AI Habit Tracker

AADAT is a modern **AI-powered desktop application** that helps users track habits, analyze behavior, and improve productivity using intelligent insights.

---

## ✨ Features

* 📊 Daily habit tracking
* 🤖 AI-based insights & analysis
* 📈 Progress visualization
* 🎯 Goal setting system
* 💻 Clean and modern UI
* ⚡ Fast and lightweight

---

## 🖥️ Supported Platforms

* 🍎 macOS (DMG Installer)
* 🪟 Windows (EXE Installer)

---

## 📦 Installation

### 🍎 macOS Installation

1. Download `AADAT.dmg`
2. Open the DMG file
3. Drag **AADAT.app → Applications**
4. Launch from Applications

⚠️ First time:

* Right click → Open → Allow

---

### 🪟 Windows Installation

1. Download `AADAT_setup.exe`
2. Double click the installer
3. Follow on-screen instructions
4. Launch AADAT from desktop or start menu

---

## 📂 Project Structure

```id="proj2"
AADAT/
│
├── dist/                  # Built app (macOS)
├── build/                 # Build files
├── assets/                # Icons & UI assets
├── data/                  # App data
├── main.py                # Main application
├── requirements.txt       # Dependencies
├── AADAT.spec             # PyInstaller config
├── AADAT_setup.exe        # Windows installer
├── AADAT.dmg              # macOS installer
├── icon.icns              # macOS icon
├── background.png         # DMG background
└── README.md
```

---

## ⚙️ Run from Source

```bash id="run2"
git clone https://github.com/your-username/AADAT.git
cd AADAT
pip install -r requirements.txt
python main.py
```

---

## 🏗️ Build Application

### macOS (DMG)

```bash id="mac2"
pyinstaller AADAT.spec
```

---

### Windows (EXE)

```bash id="win2"
pyinstaller main.py --onefile --windowed
```

Or using installer:

```text id="inno"
AADAT_installer.iss (Inno Setup)
```

---

## 📸 Screenshots

*Add your app screenshots here*
## 📸 App Preview
<img width="1536" height="960" alt="Screenshot 2026-04-17 at 9 25 11 PM" src="https://github.com/user-attachments/assets/ad86d6de-1c0e-4ae8-95c7-c09ce9e5cec7" />


## 📸 App Settings 
<img width="1536" height="960" alt="Screenshot 2026-04-17 at 9 26 03 PM" src="https://github.com/user-attachments/assets/7cf594f8-cd41-48eb-933a-2d175790deaa" />
## 📸 App Analysis 
<img width="1536" height="960" alt="Screenshot 2026-04-17 at 9 25 43 PM" src="https://github.com/user-attachments/assets/ff568836-55ff-472f-aad0-25559031cac5" />
## 📸 App habit  Tracker 
<img width="1536" height="960" alt="Screenshot 2026-04-17 at 9 20 38 PM" src="https://github.com/user-attachments/assets/a35efa32-8e23-43e5-83dd-516dd13d48ca" />

```

---

## 🎯 Future Improvements

* ☁️ Cloud sync
* 📱 Mobile version
* 🤖 Advanced AI features
* 🌐 Web dashboard

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork and submit pull requests.

---

## 📄 License

MIT License

---

## 👩‍💻 Author

**Madhu Sarkar**
MSc Computer Science (Honey)
AI • Cloud • App Development

---

⭐ Star this repo if you like the project!

