# ⚖️ SOLITAIRE — Legal & Technical Evaluation Suite

<div align="center">

**A dual-report underwriting tool for Legal Scrutiny & Technical Valuation, built for DSA loan workflows.**

*Solitaire Finz Mart · Bhiwandi, Maharashtra*

[![Live Site](https://img.shields.io/badge/Live-GitHub%20Pages-C4A672?style=for-the-badge&logo=github&logoColor=white)](https://sachink24.github.io/SOLITAIRE-Legal---Technical/index.html)
![Status](https://img.shields.io/badge/Status-Active-5FA97A?style=for-the-badge)
![Backend](https://img.shields.io/badge/Backend-Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

</div>

---

## ✨ Overview

**SOLITAIRE** is a mobile-first, single-page web application used by Solitaire Finz Mart to generate **bank-ready Legal and Technical Evaluation Reports** for loan proposals — the two reports every bank/NBFC credit file needs before sanctioning a Home Loan, LAP, Business Loan, or Construction Finance case.

Instead of juggling Word templates and manual checklists, an Advocate or Technical Associate fills a structured, section-by-section form directly on their phone or laptop, sees a live completion meter, and exports a clean, print-ready PDF — all synced in real time to a shared Supabase backend so Owners and Agents can track progress without chasing WhatsApp updates.

---

## 🗂️ Pages

| Page | Purpose |
|---|---|
| `index.html` | **Legal Evaluation Report** — title investigation, litigation search, statutory compliance |
| `legal.html` | Mirror entry point for the Legal Evaluation Report (same tool, linked from nav) |
| `technical.html` | **Technical Evaluation Report** — site visit, valuation, construction compliance |
| `privacy.html` | Privacy Policy & Terms of Service |

---

## 🧭 Core Features

- **📋 Section-by-section report builder** — each report is broken into focused sections (Header, Title Investigation, Document Verification, Litigation Search, Statutory Compliance, Risk Assessment, Sign-off, and more) so nothing gets missed on a live case.
- **🎭 Role-based views** — switch between **Advocate / Technical Associate**, **DSA Admin**, and **Agent (view-only)** to control what's editable vs. read-only.
- **🔗 Cross-linked reports** — the Legal report shows a live read-only summary of Technical findings (and vice versa), so both sides of a credit file stay consistent.
- **🚦 Risk & recommendation chips** — quick visual Green / Amber / Red risk levels feed straight into the final recommendation.
- **📈 Live progress meter** — a real-time "% complete" tracker shows exactly how far a draft report is from submission-ready.
- **☁️ Supabase-backed autosave** — every field syncs to a shared cloud database, so a report started on one device is instantly visible to the rest of the team.
- **🖨️ One-click PDF export** — "Export Bank-Ready PDF" opens a print-formatted view ready to save or send to the lender.
- **🌗 Dark / light theme toggle** — a black-and-gold "Solitaire" aesthetic in dark mode, with a warm ivory-and-gold light mode.
- **📱 Mobile-first design** — built to be filled out on-site, on a phone, during a property visit.

---

## 🎨 Design Language

A consistent black-and-gold identity runs across every page:

- **Typography:** Cormorant Garamond (serif headings) + Inter (body) + IBM Plex Mono (data/codes)
- **Palette:** Deep navy-black backgrounds (`#0A0D12`) with warm gold accents (`#C4A672`) and status colors for OK / Warning / Risk states
- **Components:** Rounded panels, soft gold borders, sticky top navigation, and a signature/seal block for sign-off

---

## 🏦 Built For

Loan products underwritten through Solitaire Finz Mart's partner banks & NBFCs, including:

`Home Loan` · `LAP` · `Business Loan` · `Balance Transfer` · `Construction Loan` · `Project Finance` · `Commercial Property` · `OD / CC`

Across partners such as **ICICI, Axis, SBI, PNB, HDFC, Piramal, Godrej, Shriram, Tata Capital, IIFL**.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS (single-file pages, no build step)
- **Backend:** [Supabase](https://supabase.com) (Postgres + realtime sync)
- **Fonts:** Google Fonts (Cormorant Garamond, Inter, IBM Plex Mono)
- **Hosting:** GitHub Pages

---

## 🚀 Getting Started

This is a static, no-build site — just open a page or serve the folder:

```bash
git clone https://github.com/sachink24/SOLITAIRE-Legal---Technical.git
cd SOLITAIRE-Legal---Technical
# open index.html directly, or serve locally:
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## 🔒 Privacy & Compliance

Application data is stored on Supabase over encrypted (HTTPS/TLS) connections with role-based access control. See [`privacy.html`](./privacy.html) for the full policy — Solitaire Finz Mart acts strictly as a DSA/advisory intermediary; final loan approval and terms rest with the partner bank/NBFC.

---

<div align="center">

**© 2026 Solitaire Finz Mart** · Loan DSA & Financial Advisory · Bhiwandi, Thane District, Maharashtra

</div>
