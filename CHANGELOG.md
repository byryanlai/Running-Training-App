# Run Plan — changelog

Live app: https://ryryououk-droid.github.io/Running-Training-App/ (hosted on GitHub Pages; the claude.ai copy was retired on 27 Nov 2026)
Screen mockups: https://claude.ai/artifact/S5p57ry44jdetwkGycWCR4

Version numbers: MAJOR.MINOR.PATCH. New features bump MINOR, fixes bump PATCH. The current version shows in Settings.

## 1.3.0 — 27 Nov 2026
- Progress tiles: "Avg km/week" now includes the current week (from your first logged run), and "This week" shows runs and km including unscheduled runs. Replaces the old 4-week average and planned-runs count, which showed 0 and — in your first week.
- Mode badge (e.g. "Mode: Fast") at the top of Today and Plan. Tap it to go to the mode switch in Progress.
- New Settings screen (gear icon on Today and Plan, or Progress › Settings and data): appearance Auto, Light or Dark, plus export, import, best times, redo setup and reset.
- Dark mode across all screens, including the chart.

## 1.2.1 — 26 Nov 2026
- Ready for sharing by link: people who can't save to their Claude account (signed out, or outside your organisation) now save in their own browser instead of seeing a sync error. Everyone's data stays private to them.

## 1.2.0 — 26 Nov 2026
- Setup asks for your current weekly distance instead of a week-by-week log, then your race and time-trial times. Existing week-by-week entries are converted to a weekly figure.
- Time fields work with the iPhone number pad: type 2000 and it becomes 20:00 as you type (130000 → 1:30:00).
- Times and distances that can't be right (pace faster than 2:30/km or slower than 15:00/km) are rejected with a message.
- Entries like that already saved are left out of predictions. Bad best times are removed, and Today shows a note with a link to fix them.
- Redo setup (Progress › Your data) re-runs setup and keeps your logged runs.
- Edit goal now includes your current weekly distance.
- Fixed trend and review figures showing hours as huge minute counts (e.g. +7354:49).

## 1.1.0 — 26 Nov 2026
- Default run days are now Mon, Wed, Fri, Sat (long run on Saturday).
- Run days setting on the Plan tab: standard (Mon Wed Fri Sat) or shifted a day later (Tue Thu Sat Sun). Light mode: Mon Wed Fri or Tue Thu Sat.
- Adjust week: shift just this week or next week by a day.
- Edit logged runs (Recent runs › Edit).
- Version number shown on the Progress tab.

## 1.0.0 — 26 Nov 2026
- First working version: setup and catch-up, Today, Log, Progress, Plan and Adjust week.
- Adaptive plan engine: missed runs dropped, low weeks repeat or step back, overrun weeks halve the next increase, recovery week every 4th week, phases and taper for a race date, time trial every 6 weeks.
- Modes: Light (3 runs), Relaxed, Medium, Fast.
- Predicted times for 5k, 10k, half and marathon with trend chart; best times.
- Unscheduled runs, with offer to replace a matching planned session.
- Data synced to your Claude account, plus export and import.
