# Workout Tracker

This is a simple static workout tracker designed for GitHub Pages.

## Files
- `index.html` — the app itself
- `README.md` — setup instructions

## What it does
- Shows a weekly workout plan
- Lets you switch days with a dropdown
- Shows day-specific stretching
- Includes a 30-minute timer
- Lets you log exercises, sets, reps, load, and notes
- Can draft an email or text message with your workout log

## How to use it locally
1. Download or clone this repo.
2. Open `index.html` in your browser.
3. Use the dropdowns and tabs.

## How to publish on GitHub Pages
1. Put `index.html` in the root of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/root`.
5. Save.
6. Wait for GitHub Pages to generate your public URL.

## Notes
- This is a static site, so no server is required.
- The dropdowns and buttons work because of JavaScript inside `index.html`.
- If you want to edit the workout plan, change the `plan` array inside the script.
