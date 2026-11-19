# Transfer Planner

A single-file web app for planning the road to a California State University (CSU) or University of California (UC) campus. It works for two kinds of students:

- **Community college transfer students** (built around Modesto Junior College)
- **High school students applying straight to a 4-year university** (first-year applicants)

Everything runs in the browser. There's no server and no account, and nothing a student enters leaves their device.

**Live app:** https://cursedgrove.github.io/transfer-planner/

## Transfer mode (community college → CSU/UC)

- Pick any of MJC's AA-T / AS-T transfer degrees and see its major requirements and Cal-GETC areas
- Import an MJC unofficial transcript (PDF or pasted text)
- Semester planner with drag-and-drop, GPA calculator and academic standing
- **Campus Requirements:** CSU and UC major preparation from ASSIST.org, compared against your MJC courses, for 32 campuses and thousands of majors
- Target campuses, deadlines, checklist, academic calendar (with .ics export), counselor meeting notes, and an education plan

## High school mode (first-year applicants)

- Track classes 9th–12th with A–G areas, honors/AP/IB levels and semester grades
- **Import an unofficial high school transcript** (PDF, including 3-column Aeries layouts, or pasted text) and review every class before saving
- Official **UC A–G course lists built in** for Thomas Downey, Grace M. Davis, Joseph A. Gregori and Modesto High (2021-22 through 2026-27). Classes are matched by their exact transcript abbreviations and school year.
- A–G progress, including the 11-by-end-of-junior-year rule and D/F flags
- UC GPA (unweighted, weighted-capped, fully weighted) and CSU GPA
- UC and CSU minimum-eligibility check, application deadlines by class year
- UC Personal Insight Questions drafts (4 of 8, 350-word counter) and an activities/awards list

## Using it

Open `index.html` in any modern browser, or use the GitHub Pages link. Data saves in that browser's local storage. Use **Settings → Backup** to export a copy or move it to another device.

## Data sources

- Major preparation: [ASSIST.org](https://assist.org) articulation agreements
- A–G course lists: [UC A–G Course List](https://hs-articulation.ucop.edu/agcourselist)
- Admission rules and dates: UC Admissions and Cal State Apply

The data is a snapshot from November 2026. ASSIST agreements and A–G lists are updated every year.

## Disclaimer

This is a personal project. It is **not** an official tool of Modesto Junior College, YCCD, Modesto City Schools, the University of California or the California State University. Always confirm your plan with a counselor, ASSIST.org and your school's official A–G course list.
