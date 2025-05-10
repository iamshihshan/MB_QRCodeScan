# 📷 QR Code Scanner for Mobile (Offline & Online)

This project is a mobile-friendly QR code scanner built with JavaScript using [`html5-qrcode`](https://github.com/mebjas/html5-qrcode). It allows scanning equipment and RFID QR codes, dynamically updates entries, and provides a JSON export that can be copied to clipboard.

✅ **Features:**
- Works on both desktop and mobile browsers.
- Camera-based QR code scanning.
- Matches scanned equipment to existing entries.
- Prompts for RFID QR code after match.
- Appends RFID to matched entry.
- One-click JSON export to clipboard.
- Fully offline-capable (when served locally).

---

## 🚀 How to Use

### 🟢 Online (via GitHub Pages)
1. Visit the live site:  
   👉 `https://<your-username>.github.io/qr-scanner/`
2. Grant camera permission when prompted.
3. Click **"Start Scanning"**.
4. Scan an Equipment QR code → then an RFID QR code.
5. Press **"Copy JSON"** to export updated data.

---

### 🔧 Offline (Run Locally)
You can use this without internet by serving it from a local server:

#### With Python:
```bash
# In the folder containing index.html and html5-qrcode.min.js
python -m http.server 8000
