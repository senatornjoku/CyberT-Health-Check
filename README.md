# 🛡️ CyberT Health Check

**A free, anonymous, open-source cyber security self-assessment tool for individuals, small businesses, and not-for-profits.**

>  Built for everyone, everywhere.

---

## 🌐 Live Demo

Deploy `index.html` to any static host — GitHub Pages, Netlify, Vercel, or simply open it in a browser.

---

## ✨ Features

| Feature | Detail |
|---|---|
| 🔒 **Fully Anonymous** | Zero data collection. All logic runs locally in the browser. |
| ⚡ **~5 Minutes** | 15 questions across 5 key security categories |
| 👤 **3 User Profiles** | Individual · Small Business · Not-for-Profit |
| 📊 **Scored Results** | Overall percentage score + per-category breakdown |
| 📋 **Action Plan** | Prioritised, tailored recommendations with external links |
| 🖨️ **Printable Report** | Built-in print stylesheet for offline records |
| 📦 **Zero Dependencies** | Pure HTML + CSS + Vanilla JS. No frameworks, no npm. |

---

## 📂 Repository Structure

```
cybertHealthCheck/
├── index.html        # The entire application (self-contained)
├── README.md         # This file
└── LICENSE           # MIT License
```

Everything is in a single `index.html` file — no build step, no dependencies.

---

## 🚀 Getting Started

### Option 1 — Open Locally
Download `index.html` and open it in any modern web browser. That's it.

### Option 2 — GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your tool will be live at `https://<your-username>.github.io/<repo-name>/`

### Option 3 — Netlify Drop
Drag and drop `index.html` onto [app.netlify.com/drop](https://app.netlify.com/drop) for an instant public URL.

---

## 📋 Assessment Categories

The tool covers five core security domains:

1. **🔑 Passwords & Authentication** — Unique passwords, password managers, MFA
2. **🛡️ Software & Device Security** — Updates, antivirus, firewall
3. **💾 Backups & Data Recovery** — Backup frequency, offsite storage, restore testing
4. **🎣 Phishing & Scam Awareness** — Phishing recognition, link verification, training
5. **🔐 Access Control & Accounts** — Least privilege, offboarding, third-party app auditing

---

## 📊 Scoring

| Score | Maturity Level | Description |
|---|---|---|
| 85–100% | ✅ Excellent | Strong cyber hygiene across all key areas |
| 67–84% | 🔵 Good | Solid posture with a few gaps to address |
| 34–66% | 🟡 Needs Work | Some protections in place, meaningful gaps remain |
| 0–33%  | 🔴 Needs Attention | Significant exposure — start with high-priority actions |

**Answer scoring:**
- **Yes** = 2 points
- **Not Sure** = 1 point
- **No** = 0 points
- **N/A** = excluded from calculation

---

## 🛠️ Customisation

Since it's a single HTML file, customisation is straightforward:

- **Add/edit questions** → Modify the `CATEGORIES` array in the `<script>` block
- **Update recommendations** → Modify the `RECO_DB` object
- **Change colours/fonts** → Edit the CSS variables in `:root`
- **Add a new category** → Add a new object to `CATEGORIES` and corresponding entries to `RECO_DB`

---

## 📄 Disclaimer

CyberT Health Check is an open-source self-assessment tool intended for **general awareness purposes only**. Results are indicative and do not constitute a formal security audit or penetration test. For critical infrastructure, regulated industries, or formal compliance needs, consult a qualified cyber security professional.

---

## 📜 License

MIT License — free to use, modify, and distribute. See [LICENSE](LICENSE).

---

## 🙏 Acknowledgements

- Inspired by the Australian Signals Directorate
- Security guidance references [cyber.gov.au](https://www.cyber.gov.au) and [ACSC Essential Eight](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/essential-eight)

---

*CyberT Health Check — Built to make cyber security accessible for everyone.*
Engr. Titus Njoku.O Msc, CAHIMS
