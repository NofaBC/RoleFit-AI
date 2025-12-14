# RoleFit AI™ – Smart Hiring Copilot (MVP – Single-File SaaS™)

**RoleFit AI™** is a Single-File SaaS™ concept that helps small and mid-size businesses hire smarter without replacing human judgment. It guides you through defining a role, generating job ads for multiple platforms, reviewing resumes, and summarizing interview notes — all from a single `index.html`.

> **Tagline:** *Write the job. Read the resumes. Advise the decision.*

---

## 🎯 What This MVP Does

This MVP is a **front-end only** prototype that shows the end-to-end flow of the RoleFit AI™ experience:

1. **Role Profile Builder**  
   Define the role once (title, mission, responsibilities, must-have & nice-to-have skills, work type, location, company culture).  
   This becomes the single source of truth powering everything else.

2. **JobMagnet Lite™ – Ad Generator**  
   From the Role Profile, the app generates three ad styles:
   - **LinkedIn-style job ad** – long form, keyword-rich.
   - **Generic job board ad** – structured and clear for sites like Indeed/ZipRecruiter.
   - **Social & referral snippets** – short posts for LinkedIn/Facebook/Alignable plus a referral DM.

3. **Resume Fit Analyzer (Simulated)**  
   Paste a candidate’s resume text and RoleFit AI™ simulates:
   - Fit Score (heuristic) + simple label: *Strong Hire / Consider / Longshot*.
   - Strengths and potential gaps.
   - 3–5 suggested interview questions aligned with the Role Profile.

4. **Interview Notes → Advisory Recommendation (Simulated)**  
   Paste your interview notes and the app:
   - Summarizes the candidate based on your notes.
   - Aligns them with the Role Profile’s mission and responsibilities.
   - Generates an **advisory** recommendation: *Hire / Maybe / No* with reasoning and follow-up question prompts.

> All recommendations are **advisory only**. The app is designed explicitly **not** to auto-reject candidates or replace human decisions.

---

## 🧱 Tech Stack

- **HTML5** – Single-page layout
- **CSS** – Custom styling, colorful gradient background, responsive grid
- **Vanilla JavaScript** – Front-end only; no build tools, libraries, or frameworks

There are **no external dependencies** beyond:
- Google Fonts (Inter)
- A sample hero image (Pexels URL you can replace)

---

## 📁 Project Structure

Single-File SaaS™ means everything lives in one file:

```text
.
└── index.html   # UI, styles, and simple JS stubs for RoleFit AI™ MVP
Version & Status

Concept date: 2025-12-02

Status: Front-end MVP mock (no real AI calls)

Architecture: Single-File SaaS™ (index.html only)

📝 License

TBD – choose and add a license file (MIT, Commercial, etc.) depending on how you plan to use and distribute RoleFit AI™.
