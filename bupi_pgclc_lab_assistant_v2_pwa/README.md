# Bupi PGCLC Lab Assistant v2

Mobile-first PWA prototype for REV1-dTAG PGCLC workflow.

## Features
- Batch ID tracking
- Timeline calculator:
  Day 0 iPSC seeding → +6 days iMeLC → +54 hr PGCLC induction for female REV1 line → +6 days FACS
- Bupi Shortcut™ cell counting:
  cells 7 µL + Trypan Blue 7 µL, 2 quadrants, cells/mL = (Q1+Q2) × 10^4
- PGCLC / differentiation seeding calculator
- Dilution split event calculator
- FACS culture-day tracking using c-day, not passage as primary axis
- Local browser database
- Export CSV and JSON backup

## Deploy
Upload all files in this folder to GitHub Pages, Netlify, or any static web host.
Then open the URL in Safari and choose:
Share → Add to Home Screen.

## Data note
Data are stored locally in the browser using localStorage.
Export CSV/JSON frequently for backup.
