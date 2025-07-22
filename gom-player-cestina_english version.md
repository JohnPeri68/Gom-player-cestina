# 🇬🇧 Czech Localization for GOM Player: Trick by John Peri from Knínice

## 🧰 Requirements
- GOM Player (recommended version: 2.3.103 CZ or older)
- Czech language file `cze.ini`
- Administrator privileges in Windows

---

## 📦 Step 1: Get the `cze.ini` file
Download the Czech language file from sites like:
- [Radírna.cz – GOM Player language guide](https://www.radirna.cz/software/gom-player-jak-na-download-a-cestinu.html)
- [INSTALUJ.cz – GOM Player download page](https://www.instaluj.cz/gom-player)

The file may be a standalone `.ini` or inside a `.rar`/`.zip` archive.

---

## ✏️ Step 2: Rename the file
Rename `cze.ini` to `english.ini`  
➡️ GOM Player loads its interface language from this file by default.

---

## 📁 Step 3: Place the file
Insert `english.ini` into this folder:
C:\Program Files\GRETECH\GOMPlayer\Language

If the folder doesn’t exist, create it manually. Replace the original `english.ini` with the new one containing Czech translations.

---

## 🔐 Step 4: Run as Administrator
Windows may block file replacement unless you run as admin:
- Open Windows Explorer as administrator
- Or use CMD with admin rights:
copy /Y "C:\path\to\your\english.ini" "C:\Program Files\GRETECH\GOMPlayer\Language\english.ini"


---

## ✅ Step 5: Launch GOM Player
After starting, the interface should appear in Czech 🎉

---

> ✍️ Author: **John Peri from Knínice**  
> 🧠 This guide helps bring Czech