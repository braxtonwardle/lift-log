# Weight For Me

A small workout tracker: build reusable workout templates (e.g. "Workout A"), start a session, and log weight/reps per set with distinct input boxes — no spreadsheet cell-tapping.

- Auto-loads last session's numbers for each exercise as a starting point.
- Big lifts can be tagged **Primary** or **Secondary** per session, tracked as separate history so a lift done heavy one day and light the next doesn't cross-contaminate the numbers it recalls.
- Primary lifts get a simple grade after logging — Increase / Same / Decrease — shown as a note next time, not used to auto-calculate anything.
- Custom workout builder — add/edit/remove exercises and set counts freely.
- All data stays local (`localStorage`) — no accounts, no server. Export to CSV or a JSON backup file from the home screen.

Single static file, no build step. Open `index.html` directly or serve it (e.g. via GitHub Pages).
