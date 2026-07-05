# Job Search Agent
> Rahul Raj | Android Developer | rahulraj94391@gmail.com
> Last updated: 2026-07-05

---

## 📐 Ground Rules

- **All structured data lives in `Job_Search_Tracker.xlsx`** — companies, contacts, applications, resume versions. Never duplicate this data here.
- Keep this file minimal: instructions, templates, and protocols only.

---

## 📋 Next Steps

1. Send referral messages to the 6 accepted PhonePe contacts → update `Referral Contacts` sheet
2. Check Couchbase connections → if accepted, send referral message → apply at job URL in `Companies` sheet
3. Apply to PhonePe, Flipkart, Weekday AI, Snapmint, Innoventes → update `Applications` sheet

---

## 💬 Referral Message Template

```
Hi [Name], thanks for connecting!

I'm Rahul, an Android Developer with 3 years of experience at Zoho,
working with Kotlin, MVVM, Jetpack, and Clean Architecture.

I noticed there are Android developer openings at [Company] and I'd love
to be considered. Would you be open to referring me or sharing any
advice on the process?

Here is my resume: https://bit.ly/4viEDf9

Thanks!
```

---

## 📄 Resume Workflow

1. Edit `Rahul_Raj_Resume.tex` → recompile → save as `Rahul_Raj_Resume_vN.pdf`
2. Update `Resume Versions` sheet in `Job_Search_Tracker.xlsx` — set old `Current?` = No, add new row
