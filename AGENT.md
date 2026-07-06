# Job Search Agent
> Rahul Raj | Android Developer | rahulraj94391@gmail.com
> Last updated: 2026-07-07

---

## 📐 Ground Rules

- **All structured data lives in `Job_Search_Tracker.xlsx`** — companies, contacts, applications, resume versions. Never duplicate this data here.
- Keep this file minimal: instructions, templates, and protocols only.

---

## 📋 Next Steps

1. ~~Send referral messages to the 6 accepted PhonePe contacts~~ ✅ Done 2026-07-07 — awaiting replies
2. ~~Check Couchbase connections~~ ✅ Done 2026-07-07 — 4/7 accepted, referral messages sent to Tanvi Johari, Thejas N U, Nishant Tripathy, Subasish Mohapatra — awaiting replies
3. Apply to PhonePe, Flipkart, Weekday AI, Snapmint, Innoventes → update `Applications` sheet

---

## 🔄 Job Hunt Workflow

1. **Find company** on LinkedIn → add to `Companies` sheet in Excel
2. **Find job posting** → get Job ID / URL → add to `Companies` sheet
3. **Send connection requests** to Android devs at that company → add each to `Referral Contacts` sheet (`Status = pending`)
4. **When connection accepted** → update `Status = accepted`, fill `Accepted Date`
5. **Send referral DM** using template below (fill `[Name]`, `[Company]`, `[Job URL / Referral Link]`) → set `Referral Msg Sent = Yes`, `Reply Status = pending`
6. **When they reply** → update `Reply Status`, `Referral Agreed = Yes/No`
7. **Apply to job** (with referral link if agreed) → add row to `Applications` sheet

---

## 💬 Referral Message Template

```
Hi [Name], thanks for connecting!

I'm Rahul, an Android Developer with 3 years of experience at Zoho,
working with Kotlin, MVVM, Jetpack, and Clean Architecture.

I noticed there are Android developer openings at [Company] and I'd love
to be considered. Would you be open to referring me or sharing any
advice on the process?

Job listing: [Job URL / Referral Link]

Here is my resume: https://bit.ly/4viEDf9

Thanks!
```

---

## 📄 Resume Workflow

1. Edit `Rahul_Raj_Resume.tex` → recompile → save as `Rahul_Raj_Resume_vN.pdf`
2. Update `Resume Versions` sheet in `Job_Search_Tracker.xlsx` — set old `Current?` = No, add new row
