# Hindsight.gui

**🔍 Hindsight: Step-by-Step Process**
🖥️ Tool: Hindsight – Chrome Forensics Tool
**✅ Step 1: Install Prerequisites**
**For Windows:**
> Install Python 3
> Optionally install Git
> OR download the prebuilt .exe from GitHub Releases

**For Linux/Kali:**
sudo apt update
sudo apt install python3 python3-pip git -y
**✅ Step 2: Download Hindsight**
Option 1: Clone GitHub Repository
git clone https://github.com/obsidianforensics/hindsight.git
cd hindsight

Option 2: Download Prebuilt .exe
Go to: https://github.com/obsidianforensics/hindsight/releases
Download hindsight_gui.exe

✅ Step 3: Install Dependencies (if using Python)
pip install -r requirements.txt

✅ Step 4: Launch Hindsight GUI
For Python version:
python3 hindsight_gui.py

For Windows prebuilt:
Double-click hindsight_gui.exe

✅ Step 5: Open in Browser
Copy the URL http://localhost:8080
Open it in Chrome or any browser
You’ll see the Hindsight GUI interface

✅ Step 6: Select Chrome Profile Path
Choose your Chrome profile location. Example for Windows:

C:\Users\<YourUsername>\AppData\Local\Google\Chrome\User Data\Default
Paste this into the Profile Path field.

✅ Step 7: Click “Run Analysis”
Click the Run button

Hindsight will parse all artifacts like history, downloads, cookies, etc.

✅ Step 8: View and Export Results
Once the analysis is complete, you can:

View results in tabs (History, Downloads, Autofill, etc.)

Click “Save XLSX” to export as an Excel file

✅ Step 9: Open the Excel File
Open the .xlsx file

Review Chrome activity like visited sites, timestamps, search terms, downloads, etc.

📌 Summary:
Hindsight makes it easy to extract and analyze Chrome browser history for digital forensics and investigations. It's free, open-source, and widely used in DFIR cases.
