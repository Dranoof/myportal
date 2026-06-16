# IGMH Drug Reference Portal

A fast, offline-capable drug reference portal for Medical Officers at Indira Gandhi Memorial Hospital (IGMH), Maldives.

Compiled by **Neal Saeed** from the IGMH Common Drug Doses handbook.

## 🌐 Live Site

> Hosted via GitHub Pages — [[your-username.github.io/your-repo-name](https://your-username.github.io/your-repo-name)](https://dranoof.github.io/myportal/)

---

## 📋 Contents

| Category | Drugs |
|---|---|
| Pain & Fever | Oral, parenteral, NSAIDs, muscle relaxants, migraine, vertigo |
| Respiratory | Antihistamines, inhalers, nebulization, smoking cessation |
| Cardiovascular | Antihypertensives, MI loading doses, GTN, lipids |
| Gastrointestinal | PPIs, antiemetics, ORS, constipation |
| Endocrine | Diabetes (oral + insulin), thyroid, bladder |
| Dermatology | Topical steroids, antifungals, oral ulcers |
| Eyes & ENT | Eye drops, ear drops, Menière's |
| Psychiatry & Neurology | SSRIs, TCAs, antipsychotics, anticonvulsants |
| Antibiotics | 13 drugs with doses, indications, and class |
| Antifungal / Antiviral | Systemic & topical antifungals, antivirals, anthelmintics |
| Vitamins & Misc | Vitamins, calcium, iron, steroids, IV fluids |
| Paediatrics OPD | Age-banded dosing for common drugs |
| Paediatrics Acute | Status epilepticus, allergic reaction, nebulization |
| Gynaecology | OCP, emergency contraception, vaginosis, candidiasis |
| Pregnancy | Safe drug list with ⚠️ warnings |
| Lactation | Safe drug list |
| G6PD Guide | Definite & possible haemolysis risk drugs |

---

## 🚀 Publishing on GitHub Pages

### Step 1 — Create a repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it anything (e.g. `igmh-drug-portal`)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the files
1. Click **uploading an existing file** on the new repo page
2. Drag and drop both files:
   - `index.html`
   - `README.md`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Select branch: `main`, folder: `/ (root)`
4. Click **Save**

### Step 4 — Visit your site
After 1–2 minutes, your site will be live at:
```
https://your-username.github.io/your-repo-name
```

---

## ✨ Features

- 🌙 / ☀️ Dark and light theme toggle
- 🔍 Live search across all drugs, doses, and classes (press `/` to focus)
- 📱 Mobile responsive with slide-out sidebar
- 🏷️ Colour-coded route badges (IV/IM, topical, combo)
- 👶 Age-banded paediatric dosing cards
- ⚠️ G6PD haemolysis risk guide
- 💊 Antibiotic table with indications and drug class
- 🤰 Pregnancy & lactation safe drug lists
- No internet required after first load (all data is embedded)

---

## 📁 File Structure

```
/
├── index.html    ← entire app (HTML + CSS + JS + data, all in one file)
└── README.md     ← this file
```

---

*For clinical use within IGMH. Always verify doses against current references before prescribing.*
