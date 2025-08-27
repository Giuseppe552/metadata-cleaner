
# 🕵️‍♂️ Metadata Cleaner


╔════════════════════════════════════════════╗  
   ⚡ Privacy Tool for Removing Hidden Metadata ⚡  
╚════════════════════════════════════════════╝  


---

A lightweight **privacy-first tool** that strips hidden metadata from common file types (PDF, DOCX, Images).  
Think of it as a **digital bleach** for your sensitive files — before sharing them online or sending to clients.  

---

## 📛 Badges
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen)
![License](https://img.shields.io/badge/License-MIT-red)

---

## 🚀 Features
- 🖼️ **Image Cleaner** – removes EXIF data (location, device info, etc.)
- 📑 **PDF Cleaner** – strips embedded metadata (author, creation, software)
- 📝 **DOCX Cleaner** – clears author, title, subject, and comments
- ⚡ **Cross-format support** – works on JPG, PNG, PDF, DOCX
- 🔒 **Privacy-first** – no external API calls, runs 100% locally

---

## ❓ Why Metadata Matters
Metadata is often invisible to the user but can reveal **sensitive information** that compromises privacy and security.  

Here are real-world risks:  
- 📍 **Location Data**: Photos often store GPS coordinates, exposing your home, office, or routes.  
- 🧑 **Identity Leaks**: Author names, company accounts, or usernames hidden in PDF/DOCX properties.  
- 🕵️ **Tracking & Profiling**: Adversaries or attackers can use metadata to link files back to you.  
- ⚖️ **Legal & Compliance**: Sensitive metadata accidentally shared could violate GDPR or client confidentiality.  

💡 By cleaning metadata before sharing, you **minimize attack surfaces**, protect personal data, and maintain professional privacy hygiene.

---

## ⚙️ Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/Giuseppe552/metadata-cleaner.git
cd metadata-cleaner
python -m pip install -r requirements.txt
````

---

## 🧪 Usage Examples

```bash
# Clean a PDF
python cleanmeta.py samples\demo.pdf -o cleaned_demo.pdf

# Clean a DOCX
python cleanmeta.py samples\demo.docx -o cleaned_demo.docx

# Clean an Image (JPG/PNG)
python cleanmeta.py samples\demo.jpg -o cleaned_demo.jpg
```

✅ Cleaned outputs:

* `cleaned_demo.pdf`
* `cleaned_demo.docx`
* `cleaned_demo.jpg`

---

## 📂 Project Structure

```
metadata-cleaner/
│── cleanmeta.py        # main script
│── requirements.txt    # dependencies
│── README.md           # documentation
│── samples/            # test files (PDF, DOCX, JPG)
│── cleaned_demo.*      # cleaned output files
```

---

## 🛰️ Roadmap

* [ ] Add support for `.pptx` (PowerPoint)
* [ ] Bulk-cleaner mode (entire folders at once)
* [ ] Export logs as JSON
* [ ] GUI version (drag & drop interface)

---

## 🔐 Security & Disclaimer

⚠️ This project is provided for educational and ethical purposes only.

It is designed to help individuals and businesses protect their privacy by removing metadata before sharing files.

The author is not responsible for misuse of this tool.

Always respect privacy laws and compliance requirements when handling sensitive data.

---

## 🕶️ Author

**Giuseppe** – Mathematics Graduate & Aspiring Security Engineer
🔗 GitHub: [@Giuseppe552](https://github.com/Giuseppe552)

💡 *"In a world of surveillance, privacy is power."*

---

## 📜 License

MIT License – Free to use, modify, and distribute.

```








