# 📧 Sendusly — Bulk Email Sender (Gmail + CSV)
Sendusly is a simple Python tool that sends bulk cold emails using Gmail SMTP and a CSV file — with smart delays, progress tracking, and automatic resume support.
</br>

## 🧩 Installation
### Window
1. Go to [Microsoft Store](https://apps.microsoft.com/detail/9NQ7512CXL7T?hl=en-us&gl=US&ocid=pdpshare)
2. Download & Install Python Install Manager
3. Run Python Install Manager (open CMD)
4. Just press **Y** and hit **Enter**
5. Now Run This Command in CMD:
   - `python -m venv %USERPROFILE%\myenv`
   - `%USERPROFILE%\myenv\Scripts\activate`
   - `python -m pip install requests python-dotenv`

### Linux
```
python3 -m venv $HOME/myenv
source $HOME/myenv/bin/activate
python3 -m pip install pyarmor.cli.core.linux pyarmor python-dotenv
git clone https://github.com/sharif1337/sendusly.git
cd sendusly
```
</br>

## 📄 Usage
```
python3 sendusly.py -f contacts.csv  
```
### CSV File Format
Your CSV file must contain:  
```
Email,Website  
test@mail.com,https://test.com
```
</br>

## 🔑 Gmail App Password Setup
1. Go to [Google Account Security](https://myaccount.google.com/security)
2. Enable **2-Step Verification** in your Google Account.  
3. Go to **Google Account → Security → App Passwords**.  
4. Create a new App
5. Copy the 16-character app password (with spaces).
> ⚠️ Important: Use your Gmail App Password, not your regular Gmail password.
</br>

## 🔁 Entered wrong name, email, or app password?
Just open the `.env` file and update your correct credentials.
```
EMAIL=yourgmail@gmail.com
APP_PASSWORD=ABCD EFGH 1234 5678
SENDER_NAME=Your Account Name
```
</br>

## 🧠 Features
- ✅ Bulk cold emailing via Gmail SMTP
- ✅ Smart delay system (avoids Gmail spam flags)
- ✅ Resume support — continues from where it stopped
- ✅ Simple CSV-based contact management
- ✅ Easy setup — no coding knowledge required
</br>

> [!NOTE]
> This tool is intended only for legitimate outreach and business communication.</br>
> The author is not responsible for misuse, spam activity, or any Gmail account restrictions.
</br>

👨‍💻 Author: Sharif Ansari  
⭐ Star this repo if you find it useful!
