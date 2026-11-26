# Run Plan — changelog

Live app: https://claude.ai/artifact/BAHfgZZvL2AH5QfPQJz9WJ
Screen mockups: https://claude.ai/artifact/S5p57ry44jdetwkGycWCR4

Version numbers: MAJOR.MINOR.PATCH. New features bump MINOR, fixes bump PATCH. The current version shows at the bottom of the Progress tab.

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
