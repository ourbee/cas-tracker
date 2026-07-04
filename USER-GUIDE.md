# CAS API Tracker — User Guide

A step-by-step guide to building your **CAS promotion API dossier** with the CAS API Tracker.

**App:** https://ourbee.github.io/cas-tracker/
**For:** teachers in West Bengal Government-aided colleges applying for CAS promotion under G.O. 1373-Edn(CS) / UGC Regulations 2016 (4th Amendment).

You do **not** need any technical knowledge. If you can fill in a form, you can use this app.

---

## Before you start

Keep these handy — you'll enter them as you go:

- Your **Date of Joining (DoJ)** in the present grade, and the **stage of promotion** you are seeking (e.g. Stage 1→2).
- Your **college and personal details** (name, designation, scale of pay).
- Your **teaching load** per session (papers/courses taught, hours), and **examination duties**.
- Your **co-curricular, committee and administrative work**, and **professional development** (orientation/refresher courses, FDPs, seminars).
- Your **research record** — publications (with ISSN/ISBN and, where relevant, impact factor), papers presented, lectures delivered.
- The **evidence** for each item (a certificate, memo, page reference, or date) — you'll note a reference to it, and attach the actual documents as annexures at the end.

> **One golden rule: back up often.** Your data is saved inside your browser, not on a server. If you clear your browser or switch computers without a backup, it is gone. Download a backup after every working session (see Step 7).

---

## Step 1 — Open the app

Go to **https://ourbee.github.io/cas-tracker/** in Chrome, Edge, Firefox, or Safari on a laptop or desktop (a bigger screen makes the print layout easier).

You'll land on the **Dashboard**. The first time, it will look mostly empty — that's expected. You're about to fill it.

*(Optional, for offline use: you can also save the page as `index.html` and double-click it to open without internet. Your work and backups behave exactly the same.)*

## Step 2 — Set your stage and add your academic sessions

1. Choose the **promotion stage** you're applying for (Stage 1→2, 2→3, or 3→4). The app adjusts the targets to match.
2. On the **Dashboard**, add at least one **assessment window / academic session**. Each academic session runs **1 July – 30 June**, and the app anchors them to your **Date of Joining** — so add one window per year of your assessment period.

> If you try to enter teaching or activity data before adding a session, the app will remind you: *"Add at least one assessment window on the Dashboard first."*

## Step 3 — Fill in Part A (General information)

Open **Part A** and complete your service and personal details: name, college, designation, scale of pay, date of joining, period of service, and the promotion sought. This is the cover information for your dossier.

## Step 4 — Enter Category I & II for each session (Part B)

For **each academic session**, open its **Category I & II** sheet and enter what you did that year.

**Category I (assessed yearly):**

- **I(a) Direct teaching** — the papers/courses you taught, the mode of teaching, and hours. (Divided by 7.5 in the score, capped at 70.)
- **Examination duties** — internal exams conducted, scripts examined, question papers set/moderated, university exam duties. (Divided by 10, capped at 20.)
- **I(c) Innovative / ICT-aided teaching** — classes with slides/projector, learning modules, multimedia, e-resources, interactive delivery. (Divided by 10, capped at 10.)

**Category II (cumulative):**

- **II(a)** Student-related co-curricular, extension and field activities (NSS/NCC, cultural, sports, career counselling, mentoring, excursions).
- **II(b)** Corporate life — college committees, administrative responsibility, IQAC/NAAC documentation, event participation.
- **II(c)** Professional development — orientation/refresher courses, FDPs, short-term training, seminars attended, professional memberships.

For each item, add a short description and an **evidence reference** (the file, page, or date that proves it). If a figure is an estimate, tick **Estimated** and add a note.

## Step 5 — Enter Category III (cumulative research sheet)

Open the **Category III** cumulative sheet and add your research output:

- **Publications** — journal papers (UGC-listed refereed, or other UGC-notified) and books (by publisher type), with ISSN/ISBN.
- **Impact factor** — where a journal has one, choose the **IF band**: IF 1–2 (+10), IF 2–5 (+15), IF 5–10 (+20). The app adds this augmentation before splitting points between authors.
- **Papers presented** and **academic/invited lectures** (note: invited/academic lectures are capped).

## Step 6 — Watch the score and the double-count warnings

As you enter data, two things update live:

- **Score overview** — your running API total for each category and the combined figure, with the target for your chosen stage. This tells you at a glance whether you've met the requirement.
- **Double-count watchers** — some activities can legitimately be claimed under more than one head, but the rules allow them **once only**. The app watches three pairs and lets you choose where each is counted:
  - **Remedial classes** — I(a) ↔ II(a)
  - **Mentoring** — I(c) ↔ II(b)
  - **A talk / paper** — III ↔ II(c)

  When it spots a possible double count, it flags it and shows which sheet the item is being counted in, so your dossier stays clean and defensible.

## Step 7 — Back up your work (do this often!)

Click **Download backup**. You'll get a small `.json` file. Keep it safe — email it to yourself or save it to cloud storage.

- To **continue later** on the same or another computer, open the app and click **Restore from backup**, then choose your `.json` file.
- Backups made in **older versions** of the app still import correctly.

Make a backup after every session you complete. It takes five seconds and protects hours of work.

## Step 8 — Print your dossier (Parts A–D)

When your entries are complete, click **Print**. The app assembles the full proforma:

- **Part A** — General information.
- **Part B** — Category I & II API sheets (one per session) and the Category III cumulative sheet.
- **Part C** — For the Screening-cum-Evaluation Committee.
- **Part D** — For the Governing Body.

In the print dialog, choose **"Save as PDF"** to get a file you can submit or print. Sign and seal where the form asks (there are Date / Seal lines).

## Step 9 — Attach your evidence (annexures)

The dossier lists the annexures you should attach, including:

- Academic qualifications; appointment & pay-fixation memos (countersigned); year-wise leave statement (countersigned).
- Orientation and Refresher Course certificates.
- Teaching evidence — session routines, ICT/PPT materials, remedial/mentoring records.
- Committee and professional memberships; seminars attended; paper presentations; university examination duties.
- Publications with ISSN/ISBN evidence; reference books consulted and prescribed.

Gather these in the order listed and attach them behind the printed dossier.

---

## Troubleshooting

**The page looks empty when I open it.**
That's normal on a fresh start — there's no data yet. Follow Step 2 to add a session, and the sheets appear.

**My data disappeared.**
Local-storage data is cleared by clearing browser history, using private/incognito mode, or switching browser or computer. Restore from your most recent backup (Step 7). Going forward, back up after every session.

**A "Save failed — edit to retry" message appears.**
Make a small edit to the entry and it will re-save. If it persists, download a backup so nothing is lost, then reload the page.

**Numbers look different from my hand calculation.**
The app applies the official caps and the count-once rule automatically. Check the double-count watchers — an item you counted twice by hand is counted once here.

**Is this official?**
No — it's a helper tool that follows the published rules. Your college's Screening-cum-Evaluation Committee and Governing Body certify the final score.

---

*Created by Ritwik Balo. Based on G.O. 1373-Edn(CS) dt. 07.12.2017 and UGC Regulations 2016 (4th Amendment).*
