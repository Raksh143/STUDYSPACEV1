# StudySpace — Personal Study Tracker

A personal, no-subscription study tracker made as a static website. It does not require an account, AI service, external API, database, or third-party JavaScript library.

## Quick start

1. Open `index.html` in a modern browser to try the tracker locally.
2. To publish it, create a **public** GitHub repository (for example, `studyspace`).
3. Upload `index.html` to the top level of that repository and commit the change. You can also upload this README and `.nojekyll` file.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/(root)` folder, then save.
7. Open the Pages URL shown by GitHub, usually `https://YOUR-USERNAME.github.io/studyspace/`.

No source-code editing is needed for the normal setup. The only file required for the site itself is `index.html`.

## What's included

- Bento-style dashboard with syllabus completion, study time, streaks, upcoming dates, weekly activity and a consistency heatmap.
- Subject-wise syllabus checklists preloaded with the chapter/unit list supplied for Science, Mathematics, Social Science, English, Hindi and Artificial Intelligence.
- Independent checklist fields for each subject. Science, Mathematics and Social Science include Status and Confidence fields; English, Hindi and AI use their own learning checkboxes.
- 16 sample-paper slots each for Science, Mathematics, Social Science and English, with completion, date, marks and notes.
- Daily study tasks and manually logged study sessions.
- Pomodoro, stopwatch and countdown timers.
- Browser-generated brown noise, rain-style noise and soft ambient tones.
- Calendar events, exam reminders and deadlines.
- Analytics for subject completion, study time, consistency, confidence, revisions and sample papers.
- Dark/light mode and JSON export/import backups.

## Data and privacy

- Study records are saved in the browser's local storage on the device where you use the tracker.
- The app does not send study data to GitHub or another server.
- Data does not automatically sync between devices or browsers.
- Clearing browser/site data, using private browsing, or switching browsers may make locally saved progress unavailable.
- Use **Settings → Export JSON** regularly. Keep the backup somewhere private and do not commit it to your public GitHub repository.
- GitHub Pages serves the website source publicly because this setup uses a public repository. Your locally stored study records are separate from the published website source.

## Notes

- A timer keeps running while you move between sections in the open page, but its live state is not preserved after closing or reloading the page.
- Calendar dates and upcoming reminders are displayed inside the app; this version does not send push notifications while the site is closed.
- Focus sounds are generated in the browser. Audio starts only after you select a sound and may require a browser interaction.
- The syllabus data is editable through the app's Add chapter control; existing supplied chapter names and checklist structures are preloaded.

Additional controls include a custom weekly study-time goal and a Focus Mode that hides navigation and surrounding cards while you work.

The dashboard also supports a custom weekly study goal, and the Focus Room includes an optional Focus Mode that hides the navigation and non-timer cards.
