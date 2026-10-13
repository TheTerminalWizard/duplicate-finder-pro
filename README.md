[🇮🇷 فارسی](https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.fa.md) | [🇬🇧 English](https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.md)

🔎 **Duplicate Finder Pro**

A Python-based application for finding and managing duplicate files on Android, using Termux, Termux:GUI, and a graphical interface.

### 🎯 Project Goal

The goal of **Duplicate Finder Pro** is to make finding and managing duplicate files easier in the Android environment. This project uses Python and Termux tools and features a graphical user interface.

### ✨ Features

- 🖥️ **Graphical Interface**: Interact with the application through a GUI.
- 🔎 **Find Duplicate Files**: Scan files to identify duplicate copies.
- 📂 **File Management**: Review scan results and select files.
- ⚙️ **Settings**: Access the available settings in the application.
- 🗑️ **File Deletion Management**: Tools for deleting selected files.
- ♻️ **File Recovery**: Support for trash and recovery features available in the app.
- 📋 **Reports**: Access application reports to review operations.

> Available features may depend on the application version, Android permissions, and access to file paths.

### 📥 Installing Prerequisites for Duplicate Finder Pro

#### Step 1 — Install the Applications

1. **Install Termux**

   - Download from F-Droid:  
     [Termux from F-Droid](https://f-droid.org/packages/com.termux/)

   - Download from GitHub:  
     [Termux from GitHub](https://github.com/termux/termux-app)

2. **Install Termux:GUI**

   - Download from F-Droid:  
     [Termux:GUI from F-Droid](https://f-droid.org/packages/com.termux.gui/)

   - Download from GitHub:  
     [Termux:GUI from GitHub](https://github.com/termux/termux-gui)

✅ Both applications must be installed on your Android device.

---

#### Step 2 — Install Required Packages in Termux

Open Termux and run the following commands in order:

1. **Grant storage access**

```bash
termux-setup-storage
```

After running the command, if Android requests file access permission, approve it.

2. **Update repositories and packages**

```bash
pkg update && pkg upgrade -y
```

3. **Install Python**

```bash
pkg install python -y
```

4. **Check if pip is installed**

```bash
pip --version
```

If the `pip` command is not found, install the related package:

```bash
pkg install python-pip -y
```

Then check again:

```bash
pip --version
```

5. **Install the required library**

```bash
pip install termuxgui
```

This library is required for the Python application to communicate with Termux:GUI.

---

#### Step 3 — Run the Application

After installing the prerequisites, navigate to the folder containing the `dup_gui.py` file and run:

```bash
python dup_gui.py
```

Running this command starts **Duplicate Finder Pro**.

---

### 🔐 Access Permissions

To scan and manage files, you may need to configure file access permissions in Android or Termux. The actual access the application has to files depends on the Android version and the granted permissions.

### 🛠️ Technologies Used

- **Python** — Programming language  
- **Termux** — Environment for running command-line tools and applications on Android  
- **Termux:GUI** — Provides graphical interface capabilities for the application  

### 📄 Project License

To learn about the terms of use, modification, and redistribution of the project, check the `LICENSE` file in the repository.

### 🔗 Project Links

- [Duplicate Finder Pro Repository on GitHub](https://github.com/TheTerminalWizard/duplicate-finder-pro)
- [Persian README](https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.fa.md)
- [English README](https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.md)
