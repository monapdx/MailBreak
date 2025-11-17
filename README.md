<img src="https://raw.githubusercontent.com/monapdx/MailBreak/refs/heads/main/MailBreak.png" width="680">

# MailBreak  
### *An Offline Streamlit App for Browsing Your Gmail Messages*

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)](https://streamlit.io/)
[![Platform](https://img.shields.io/badge/Platform-Offline-green)](#)
[![Google Takeout](https://img.shields.io/badge/Works%20With-Google%20Takeout-yellow?logo=google)](https://takeout.google.com/)
[![License](https://img.shields.io/badge/License-MIT-purple)](LICENSE)

**Author:** [Ashly Lorenzana](mailto:ashlylorenzana@gmail.com)  
**GitHub:** https://github.com/monapdx/MailBreak

MailBreak is a lightweight, offline Streamlit application that lets you browse your Gmail messages using data you export from **Google Takeout**. It’s perfect for people who want fast, local access to their archived inbox—no API, no server, no cloud dependencies.

---

## ✨ Overview

MailBreak was designed to help you:

- Explore your Gmail inbox *offline*
- Use custom Gmail labels to create highly specific “data slices”
- Download only the emails you actually care about from Google Takeout
- Navigate your `.mbox` file through a simple Streamlit interface
- Optionally use an included **.mbox viewer** if you prefer a classic browser-style interface

---

## 📌 Create & Use Gmail Labels

Organizing your inbox *before* exporting from Google Takeout is key.

Use Gmail labels to segment your inbox into meaningful categories—especially if you plan to export only certain labels at a time. These labels make your life MUCH easier when slicing your inbox into useful datasets.

---

## 📂 Nest Your Labels for Super-Specific Slices

You can create parent labels and nest sub-labels under them to build powerful structures.

Think of nested labels as **filters** for your Takeout export:


When you export only the sub-labels you want, your `.mbox` file becomes cleaner, smaller, and far more relevant.

---

## ⚙️ Create Filters (Automation Rules)

You can apply your labels manually, but letting Gmail automate this for you is much faster.

Create filters:

- Directly from inside any email  
- Using Gmail's powerful search operators  
- For senders, subjects, domains, or keywords  

This ensures your inbox organizes itself automatically over time.

---

## ⬇️ Download Email Data via Google Takeout

Once your labels and filters are set up, go to:

👉 **https://takeout.google.com**

Then:

1. Select **only Gmail**  
2. Expand Gmail’s options  
3. Select the **specific labels** or **sub-labels** you want  

This prevents giant, bloated data archives and lets you export only what matters.

---

## 🎯 Why Selective Label Export Matters

Downloading everything under a large parent label like `Accounts` can:

- Produce enormous `.mbox` files  
- Include tons of irrelevant email  
- Slow down parsing or viewing  

By exporting only the precise slices you want, your email data becomes targeted and clean—for example:

> *Only emails labeled as affiliate payouts across multiple platforms.*

---

## 🛠️ Install MailBreak & Run Locally

Clone the repo:

```bash
git clone https://github.com/monapdx/MailBreak
cd MailBreak

pip install -r requirements.txt

pip install streamlit

streamlit run app.py
```

### 📁 Optional: Use the Included .mbox Viewer

If you prefer a traditional message list, or if typing message IDs isn't your style, use the included MailBreak MBOX Viewer.

It allows you to:

- Scroll through messages

- View metadata

- Read HTML or plaintext content

- Navigate like a simple offline email client

Great for people who want a more classic mailbox browsing experience.

## 🤝 Contribute

Contributions are welcome!
Feel free to open issues, submit pull requests, or suggest improvements.

### 💌 Contact

**Email**: ashlylorenzana@gmail.com

**GitHub**: https://github.com/monapdx/MailBreak

## 📄 License


This project is released under the MIT License.
