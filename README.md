# मुरबाडकर लिखिते वंशावळ (Murbadkar Likhite Family Tree)
**Interactive Genealogical Archive & Family Tree Visualizer (12 Generations • 175+ Members)**

An interactive, searchable, and editable digital genealogy of the **Murbadkar Likhite (मुरबाडकर लिखिते)** family, tracing 12 generations from founding ancestor **तुकाजी (Tukaji)** to the newest generation (**Viaan & Viraj**).

---

## 🔒 Password Protection (गोपनीयता व पासवर्ड संरक्षण)

The website is protected with a family access security gate using **SHA-256 cryptographic verification**. Only family members who enter the correct password can view the family tree.

* **Default Family Password:** `likhitefamily`
* **Session Persistence:** Once unlocked in a browser tab, family members remain logged in for that session.
* **Lock Button:** A "🔒 Lock" button is located on the top header toolbar to instantly re-lock the screen.

### How to Change the Password:
1. Choose your desired new password (e.g., `MyFamilyPass2026`).
2. Generate its SHA-256 hash using terminal or Python:
   ```bash
   python3 -c "import hashlib; print(hashlib.sha256('MyFamilyPass2026'.encode()).hexdigest())"
   ```
3. Open `index.html` in an editor, find line ~1235:
   ```javascript
   const PASSWORD_HASH = "c7d4d474041934d45ddd358d5a64d9a68866279b11db55f5b953bb20040c9cdf";
   ```
4. Replace the string with your new SHA-256 hash and save. The plain text password is never stored or visible in the code.

---

## 🌟 Features (वैशिष्ट्ये)

* **Interactive Canvas:** Smooth pan, zoom, click-to-expand, and generational levels (पिढी १ ते १२).
* **Live Search:** Fast search by ancestor name in Marathi Devanagari or English transliteration.
* **Locate Devavrat Branch:** 1-click button to center directly on Devavrat and his children **Viaan & Viraj**.
* **Edit & Extend Tree:**
  * Edit name spelling in Devanagari & English.
  * Add **Birthdate** and notes.
  * Add new children (**Add Child**) or siblings (**Add Sibling**) to extend the lineage.
  * Changes auto-save to browser **LocalStorage**.
  * **Export / Import JSON:** Download your updated family database anytime.
* **Original 1992 Manuscript Scans:** Built-in viewer for all 8 original handwritten sheets from November 28, 1992.
* **WhatsApp Exports:** 1-click access to download Ultra-HD (29,712 × 5,110 px) and mobile cards.

---

## 🚀 Step-by-Step GitHub Pages Hosting Instructions

Host this private family archive on **GitHub Pages** for free in 4 simple steps:

### Step 1: Create a GitHub Repository
1. Log in to [github.com](https://github.com) (sign up if you don't have an account).
2. Click the **+** (plus icon) in the top right corner and select **New repository**.
3. Set **Repository name**: e.g., `likhite-family-tree` or `likhitefamily`.
4. Choose **Public** (GitHub Pages requires Public on free accounts; the password gate secures the webpage).
5. Leave "Add a README file", ".gitignore", and license **UNCHECKED** (we already have them ready).
6. Click **Create repository**.

### Step 2: Push this Folder to GitHub
Open Terminal on your Mac and run:
```bash
cd /Users/devavrat0210/Desktop/Temp/likhitefamilytree/LikhiteFamilyTreeWeb
git remote add origin https://github.com/<YOUR-GITHUB-USERNAME>/<YOUR-REPO-NAME>.git
git branch -M main
git push -u origin main
```
*(Replace `<YOUR-GITHUB-USERNAME>` and `<YOUR-REPO-NAME>` with your actual GitHub username and repository name).*

### Step 3: Enable GitHub Pages
1. On your GitHub repository page, click **Settings** (tab at the top).
2. On the left sidebar menu, click **Pages**.
3. Under **Build and deployment**:
   * **Source:** Select `Deploy from a branch`.
   * **Branch:** Select `main` and folder `/ (root)`.
   * Click **Save**.

### Step 4: Share with Family
Within 1-2 minutes, GitHub will publish your live site at:
```
https://<YOUR-GITHUB-USERNAME>.github.io/<YOUR-REPO-NAME>/
```
Share this link with your family along with the password (`likhitefamily`). When they visit the link:
1. They will see the royal **मुरबाडकर लिखिते कुलवृक्ष** lock screen.
2. They enter `likhitefamily` and click **Unlock Family Tree**.
3. The full tree, search, zoom, WhatsApp images, and handwritten 1992 scans will open seamlessly on mobile phones, tablets, or computers!

---

## 📁 Repository Contents

* `index.html` — Password-protected interactive family tree web application.
* `likhite_family_tree.json` — 175+ members across 12 generations structured database.
* `likhite_full_family_tree_ultra_hd.jpg` — 29,712 × 5,110 px master poster image.
* `likhite_direct_lineage_ultra_hd.jpg` — Direct 12-generation lineage mobile card.
* `likhite_gajanan_branch_ultra_hd.jpg` — Gajanan branch family lineage card.
* `Page 1.jpg` to `Page 8.jpg` — 1992 handwritten original manuscript scans.
* `.nojekyll` — Ensures GitHub Pages serves all assets and subfolders correctly.
* `.gitignore` — Ignores unnecessary temporary operating system files.

---

## 🏛️ Heritage Metadata (कुल परिचय)

* **कुलदैवत:** व्याघ्रांबरी, मुंजावती
* **गोत्र:** गंधमादन
* **मूळ संकलन:** श्री. भालचंद्र मोरेश्वर लिखिते व श्री. अरविंद भास्कर लिखिते (२८ नोव्हेंबर १९९२)
