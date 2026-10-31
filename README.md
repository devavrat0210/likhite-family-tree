# मुरबाडकर लिखिते वंशावळ (Murbadkar Likhite Family Tree)
**Interactive Genealogical Archive & Family Tree Visualizer (12 Generations • 175+ Members)**

An interactive, searchable, and editable digital genealogy of the **Murbadkar Likhite (मुरबाडकर लिखिते)** family, tracing 12 generations from founding ancestor **तुकाजी (Tukaji)** to the newest generation.

---

## 🌟 वैशिष्ट्ये (Key Features)

* **परस्परसंवादी वंशावळ (Interactive Canvas):** Smooth pan, zoom, click-to-expand, and generational levels (पिढी १ ते १२).
* **शोध सुविधा (Live Search):** Search any ancestor in Marathi Devanagari or English.
* **देवव्रत शाखा (Quick Locate):** 1-click button to center on Devavrat and his children Viaan & Viraj.
* **माहिती संपादन व विस्तार (Full Editor):**
  * कोणत्याही व्यक्तीची माहिती, स्पेलिंग दुरुस्त करा.
  * **जन्म तारीख (Birthdate)** जोडा.
  * नवीन मुले (Add Child) किंवा भावंडे (Add Sibling) जोडून वंशावळ वाढवा.
  * स्वयंचलित **Local Storage** मध्ये बदल सेव्ह होतात.
  * **Export / Import JSON:** अद्ययावत वंशावळ फाईलमध्ये सेव्ह करून नंतर लोड करा.
* **मूळ दस्तऐवज (Original 1992 Scans):** २८ नोव्हेंबर १९९२ ची सर्व ८ मूळ हस्तलिखित पत्रके थेट ब्राऊझरमध्ये पाहण्याची सोय.
* **WhatsApp साठी चित्रे:** Ultra-HD (29,712 × 5,110 px) आणि मोबाईल-फ्रेंडली (9:16) चित्रे १-क्लिकमध्ये डाउनलोड करा.

---

## 🚀 GitHub Pages वर लाईव्ह कसे करावे (How to Host on GitHub Pages)

हे फोल्डर थेट GitHub वर अपलोड करून विनामूल्य (Free) वेबसाईट म्हणून होस्ट करण्यासाठी खालील ३ पायऱ्या करा:

### पायरी १: GitHub वर नवीन Repository तयार करा
1. [github.com](https://github.com) वर जाऊन लॉगिन करा.
2. **New Repository** तयार करा (उदा. `likhite-family-tree`).
3. Repository **Public** ठेवा.

### पायरी २: या फोल्डरमधील सर्व फाईल्स अपलोड करा
तुमच्या टर्मिनलमध्ये या फोल्डरमध्ये जाऊन खालील कमांड्स चालवा:
```bash
git init
git add .
git commit -m "Initial commit - Likhite Family Tree"
git branch -M main
git remote add origin https://github.com/<your-username>/likhite-family-tree.git
git push -u origin main
```
*(किंवा GitHub च्या वेबसाईटवरून **Upload files** पर्यायाने या फोल्डरमधील सर्व फाईल्स थेट ड्रॅग-अँड-ड्रॉप करू शकता.)*

### पायरी ३: GitHub Pages चालू करा
1. तुमच्या GitHub Repository मध्ये **Settings** वर क्लिक करा.
2. डाव्या बाजूच्या मेनूमधील **Pages** वर जा.
3. **Build and deployment** अंतर्गत:
   * **Source:** `Deploy from a branch` निवडा.
   * **Branch:** `main` आणि `/ (root)` निवडा.
   * **Save** बटणावर क्लिक करा.

🎉 अवघ्या १-२ मिनिटांत तुमची वेबसाईट लाईव्ह होईल:
```
https://<your-username>.github.io/likhite-family-tree/
```
ही लिंक तुम्ही जगातील सर्व कुटुंबीयांसोबत थेट शेअर करू शकता!

---

## 📁 फाईल रचना (Repository Structure)

* `index.html` — मुख्य परस्परसंवादी वंशावळ वेब अ‍ॅप (Interactive Web Application)
* `likhite_family_tree.json` — १७५ कुटुंबीयांचा संपूर्ण डेटाबेस (Structured Data)
* `likhite_full_family_tree_ultra_hd.jpg` — २९,७१२ × ५,११० px महाकाय पोस्टर (Full Tree Ultra HD)
* `likhite_direct_lineage_ultra_hd.jpg` — थेट १२ पिढ्यांचे मोबाईल कार्ड (9:16 Mobile HD)
* `likhite_gajanan_branch_ultra_hd.jpg` — गजानन शाखा कुटुंब चार्ट (Gajanan Branch HD)
* `Page 1.jpg` ते `Page 8.jpg` — १९९२ ची मूळ हस्तलिखित पत्रके (Original Manuscript Scans)
* `.nojekyll` — GitHub Pages static serving bypass

---

## 🏛️ कुल परिचय (Heritage Metadata)

* **कुलदैवत:** व्याघ्रांबरी, मुंजावती
* **गोत्र:** गंधमादन
* **मूळ संकलन:** श्री. भालचंद्र मोरेश्वर लिखिते व श्री. अरविंद भास्कर लिखिते (२८ नोव्हेंबर १९९२)
