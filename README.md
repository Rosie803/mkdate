# 💄 Mary Kay Batch Code Decoder

A simple, mobile-friendly web tool for consultants to instantly check the manufacturing date and shelf life of products using the 4-character batch code.

**🔗 [CLICK HERE TO OPEN THE APP]**

---

## ✨ Features
* **Instant Decoding:** Input the 4-character batch code (e.g., `H D 2 5`) to see the date.
* **Expiration Calculator:** Automatically adds 3 years to the manufacturing date to show the "Best By" date.
* **Offline Capable:** Once loaded on your phone, it works without internet access (perfect for events with bad reception).
* **App-Like Feel:** Can be saved to the iPhone/Android home screen for quick access.
* **Privacy Focused:** No data is stored or sent to a server. All calculations happen right on your phone.

## 📅 Decoding Logic
 This tool uses the standard Mary Kay batch code system:

**1. First Character (Year of Manufacture)**
* **K** = 2026
* **H** = 2025
* **F** = 2024
* **D** = 2023
* **C** = 2022
* **B** = 2021
* **A** = 2020
* **Y** = 2019
* **R** = 2018

**2. Second Character (Month)**
* **A** through **X** corresponds to Jan–Dec (skipping some letters).

**3. Last Two Digits (Day)**
* Represents the specific day of the month.

## 📱 How to Install (Add to Home Screen)
You do not need an App Store to use this!

**iPhone (iOS):**
1.  Open the link in **Safari**.
2.  Tap the **Share** button (square with arrow).
3.  Select **"Add to Home Screen"**.

**Android:**
1.  Open the link in **Chrome**.
2.  Tap the **three dots** (menu).
3.  Select **"Add to Home screen"**.

## 🛠 Technical Details
* **Tech Stack:** HTML5, CSS3, Vanilla JavaScript.
* **Hosting:** GitHub Pages (Free, Static hosting).
* **Files:** Single-file architecture (`index.html`) for easy maintenance.

---

### ⚠️ Disclaimer
*This tool is a helpful utility created for independent consultants. It is **not** an official application of Mary Kay Inc. All product names, logos, and brands are property of their respective owners.*
