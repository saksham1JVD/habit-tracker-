# Student Habit Tracker

A simple Progressive Web App (PWA) for students to track study time, exercise, sleep, and free time every day.

## Features
- Track daily study time (minutes).
- Log exercise completed and exercise minutes.
- Track free time and sleep hours.
- View streak (days in a row you logged habits).
- See a score (0–100) based on study + exercise vs free time.
- Delete entries or clear all history.
- Simple chart of last 7 days (study vs free time).

## How to Use
1. Open the app in a browser (e.g., Chrome, Edge, or Firefox).
2. Fill in at least one habit (study time, exercise, etc.) and click **"Save Today"**.
3. You can install it as an app using the **"Install as App"** button if you are on a mobile browser that supports PWAs.

## How to Run Locally
- Download or clone this repository.
- Open `habit-tracker.html` in your browser.
- Your data is saved in your browser’s local storage (no server needed).

## Notes
- This is a client‑side web app: no backend, no login, no database.
- Works fully offline after the first load (PWA with service worker).
