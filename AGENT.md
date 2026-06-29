# Job Search Agent — Task Tracker
> Rahul Raj | Android Developer | rahulraj94391@gmail.com
> Last updated: 2026-06-09 (keep this file updated after every session)

---

## ✅ Done

- [x] Built resume — `Rahul_Raj_Resume.tex` + compiled `Rahul_Raj_Resume_v1.pdf`
- [x] Applied to **Razorpay** (Senior SDE) via LinkedIn Easy Apply — submitted 2026-06-08
- [x] Sent connection requests to **10 PhonePe Android developers** for referral (2026-06-08) — batch 1, no note
- [x] Sent **10 more PhonePe connection requests** with note (2026-06-08) — batch 2 (3 with note, 7 without — LinkedIn note quota: 3/month)
- [x] Tracked all data in **`Job_Search_Tracker.xlsx`** (4 sheets: Companies, Referral Contacts, Resume Versions, Applications)
- [x] WhatsApp notification channel set up — agent messages "Rahul Raj" on WhatsApp Web when human assistance needed

---

## 🔄 In Progress

- [ ] **PhonePe connections** — 6/20 accepted so far (batch 1: 10 sent 2026-06-08, batch 2: 10 sent 2026-06-08)
  - ✅ Accepted: Somenath Sarkar (2026-06-08), Vijay Sharma (2026-06-08), Sahil Thakar (2026-06-08), Jay Chittewan (2026-06-09), Manan Virmani (2026-06-09), Gaurav M. (2026-06-09)
  - Batch 2 with note: Shuja Reshi, Rohit Choudhary, Gaurav M. (3 notes used — LinkedIn free quota exhausted for month)
  - Batch 2 without note: Meet K Parmar, Vaibhav Birla, Shubhangi Mehrotra, Parth Chandna, Pratik Anurag, Jotish Suthar, Nimisha Sharma
  - Once accepted → send referral message → update `Job_Search_Tracker.xlsx` (Referral Contacts sheet)
- [ ] **Resume metrics** — Zoho experience bullets still have `[X]` placeholders; fill in real numbers

---

## 📋 Pending / Next Steps

### Referral Flow (PhonePe)
- [ ] Check connections daily — update `Job_Search_Tracker.xlsx` when accepted
- [ ] Send referral message to accepted contacts (draft message below)
- [ ] Track replies in xlsx (Reply Status: pending → replied / no_response)
- [ ] If referral agreed → apply to PhonePe job with referral link

### Couchbase
- [ ] **Couchbase SWE II** — job URL: https://job-boards.greenhouse.io/couchbaseinc/jobs/4666945006
  - 3+ yrs Java/Android/Kotlin, Couchbase Lite (embedded mobile DB), Bangalore on-site
  - Good fit: matches Rahul's Kotlin/MVVM/Android background
  - 7 connections sent 2026-06-09 (Ayush N., Tanvi Johari, Subasish Mohapatra, Vipul Bhardwaj, Nishant Tripathy, Vibhav Shiras, Thejas N U)
  - Wait for acceptances → send referral message → apply with referral
- [ ] **Couchbase Senior Mobile Developer** — 6-9 yrs Swift+Kotlin required — **too senior, skip**

### More Job Applications
- [ ] **PhonePe** — find Android job posting URL, apply (with referral if possible)
- [ ] **Flipkart** — search for Android SDE roles, apply
- [ ] **Weekday AI** — apply to Android roles found earlier
- [ ] **Snapmint** — apply to Android roles
- [ ] **Innoventes Technologies** — apply to Android roles

### Referral Outreach (Other Companies)
- [ ] Search for Android developers at Flipkart on LinkedIn → send connection requests
- [ ] Search for Android developers at other target companies → send connection requests
- [ ] Add new companies + contacts to `Job_Search_Tracker.xlsx`

### Resume
- [ ] Fill in `[X]` placeholders in Zoho experience section with real metrics
- [ ] Recompile PDF after edits → `Rahul_Raj_Resume_v2.pdf`
- [ ] Add v2 row to `Job_Search_Tracker.xlsx` → Resume Versions sheet

---

## 📱 WhatsApp Notification Protocol

When the agent needs human assistance for a restricted action, it will:
1. Open `https://web.whatsapp.com/`
2. Send a `[AGENT]` prefixed message to **Rahul Raj**
3. Describe exactly what needs to be done and why

**Restricted actions that trigger a WhatsApp alert:**
- Deleting files permanently
- Submitting sensitive forms
- Entering credentials or payment info
- Any irreversible action requiring your confirmation

---

## 💬 Referral Message Draft
> (Send after connection is accepted)

```
Hi [Name], thanks for connecting!

I'm Rahul, an Android Developer with 3 years of experience at Zoho,
working with Kotlin, MVVM, Jetpack, and Clean Architecture.

I noticed there are Android developer openings at PhonePe and I'd love
to be considered. Would you be open to referring me or sharing any
advice on the process?

Happy to share my resume. Thanks!
```

---

## 📄 Resume Version Workflow

**Step 1** — Edit `Rahul_Raj_Resume.tex`, make changes, recompile → new PDF (e.g. `Rahul_Raj_Resume_v2.pdf`)

**Step 2** — Open `Job_Search_Tracker.xlsx` → **Resume Versions** sheet → set previous "Current?" to No → add new row with version details.

### Version History

| Version | PDF | Changes | Reason | Date |
|---------|-----|---------|--------|------|
| v1 | Rahul_Raj_Resume_v1.pdf | Initial resume | Base / Razorpay application | 2026-06-08 |

---

## 📊 Excel Tracker — Quick Reference

**File:** `Job_Search_Tracker.xlsx` (4 sheets)

| Sheet | Purpose |
|-------|---------|
| Companies | Target companies + applied status |
| Referral Contacts | All LinkedIn connections + referral progress |
| Resume Versions | Version history of resume |
| Applications | Job applications submitted |

**Workflow for updates:**
- New connection accepted → Referral Contacts → set Status = `accepted`, fill Accepted Date
- Referral message sent → set Referral Msg Sent = `Yes`, fill Msg Date, Reply Status = `pending`
- Reply received → set Reply Status = `replied`, fill Reply Date, Referral Agreed = `Yes/No`
- New resume version → Resume Versions → set old Current? = `No`, add new row with `Yes`
- New application → Applications sheet → add row

---

## 📁 Files

| File | Description |
|------|-------------|
| `Rahul_Raj_Resume.tex` | LaTeX source for resume |
| `Rahul_Raj_Resume_v1.pdf` | Resume v1 — used for Razorpay (current active) |
| `Job_Search_Tracker.xlsx` | Excel tracker — companies, contacts, applications, resume versions |
| `AGENT.md` | This file |

---

## 🏢 Companies Tracker

| Company | Role | Applied | Referral Contacts | Status |
|---------|------|---------|-------------------|--------|
| Razorpay | Senior SDE (Android) | ✅ 2026-06-08 | — | Applied |
| PhonePe | Android Developer | ⏳ Pending | 20 sent (2026-06-08); 6 accepted | 6/20 accepted — send referral to new contacts |
| Couchbase | SWE II (Mobile/Android) | ❌ Not yet | 7 sent (2026-06-09); 0 accepted | Pending — wait for acceptances then request referral |
| Flipkart | Android SDE | ❌ Not yet | 0 | Not started |
| Weekday AI | Android | ❌ Not yet | 0 | Not started |
| Snapmint | Android | ❌ Not yet | 0 | Not started |
