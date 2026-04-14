# 📋 Sales Team Incentive Programme · Italy 2026

A single-page internal web application for Lycamobile Italy's Sales Team Incentive Programme. It explains the incentive structure, payout slabs, and includes a live calculator — all in **5 languages**.

---

## 🌐 Multilingual Support

| Flag | Language | Script | Direction |
|------|----------|--------|-----------|
| 🇬🇧 | English | Latin | LTR |
| 🇮🇹 | Italiano (Italian) | Latin | LTR |
| 🇮🇳 | தமிழ் (Tamil) | Tamil | LTR |
| 🇧🇩 | বাংলা (Bangla) | Bengali | LTR |
| 🇵🇰 | اردو (Urdu) | Nastaliq | RTL |

Language switching is instant, with full RTL layout support for Urdu.

---

## ✨ Features

- **Role Overview** — Incentive slabs for Regional Manager, Office Manager, and Zone Manager
- **Performance Weightage** — Visual breakdown of GA (75%), UAO (20%), and New Shops (5%)
- **Payout Table** — Role-switchable table showing incentive earned per achievement band
- **Live Calculator** — Enter targets and MTD actuals to estimate your incentive in real time
- **Terms & Conditions** — All 12 programme rules clearly listed
- **Fully Responsive** — Works on desktop, tablet, and mobile
- **RTL Layout** — Complete right-to-left support for Urdu
- **No build tools** — Pure HTML, CSS, and JavaScript in a single file

---

## 📁 Project Structure

```
.
├── index.html      # Complete single-page application
├── README.md       # This file
├── LICENSE         # MIT License
└── .gitignore      # Git ignore rules
```

---

## 🏗️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure |
| CSS3 (custom properties, grid, flexbox) | Styling & layout |
| Vanilla JavaScript (ES6+) | Calculator, language switching, payout table |
| Google Fonts | Syne, DM Sans, Noto Sans Tamil, Noto Sans Bengali, Noto Nastaliq Urdu |

> No frameworks, no dependencies, no build step.

---

## 💰 Incentive Structure Summary

### Roles & Base Slabs

| Role | Monthly Slab | Max (120%) |
|------|-------------|------------|
| Regional Manager | €1,500 | €1,800 |
| Office Manager | €1,000 | €1,200 |
| Zone Manager | €700 | €840 |

### Payout Bands

| Overall Weightage | % of Slab Paid |
|-------------------|----------------|
| Below 90% | €0 (no payout) |
| 90% – 94% | 50% |
| 95% – 99% | 80% |
| 100% – 105% | 100% ⭐ |
| 106% – 119% | 110% |
| 120% and above | 120% 🏆 |

### KPI Weightage

| Metric | Weight | Description |
|--------|--------|-------------|
| GA (Gross Additions) | 75% | New active SIM sales |
| UAO (Unique Active Outlets) | 20% | Outlets with ≥1 GA sale |
| NA (New Shops) | 5% | Newly onboarded shops |

---

## 🌍 Adding a New Language

All translations live in the `translations` object inside the `<script>` tag in `index.html`.

1. Open `index.html` and locate the `const translations = { ... }` block.
2. Add a new language key (e.g., `"fr"` for French).
3. Copy the `"en"` block as a template and translate all string values.
4. Add a button for the new language in the `#lang-dropdown` `<div>` inside the language switcher HTML block.
5. If the language is RTL, add its key to the `rtlLangs` array in the `setLanguage()` function.

---

## ⚠️ Important Notes

- This page is **for internal staff use only**.
- All incentive calculations shown are **estimates**. Final payouts are subject to management approval and all published T&C.
- The company reserves the right to change the incentive scheme at any time.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

This is an internal tool. For change requests, please raise them through your line manager or the Sales Operations team.

---

*HS Italy · Sales Team Incentive Programme · 2026*
