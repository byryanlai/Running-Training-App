# Running-Training-App

**Run Plan**: an adaptive running training plan you add to your iPhone home screen as a web app.

- Live app: https://claude.ai/artifact/BAHfgZZvL2AH5QfPQJz9WJ
- Screen mockups: https://claude.ai/artifact/S5p57ry44jdetwkGycWCR4
- Changes by version: [CHANGELOG.md](CHANGELOG.md)

## What it does
- Goals for 5k, 10k, half or full marathon, with an optional race date
- Adapts the plan to what you actually run: missed runs are dropped, low weeks repeat or step back, and recovery weeks and tapers are built in
- Four modes: Light, Relaxed, Medium, Fast
- Reschedule sessions, cut a week to 3 or 2 runs, or shift run days by one day
- Log, edit and delete runs, including unscheduled ones
- Predicted times and trend for every distance, plus best times

## Files
- `index.html`: the whole app in one file (HTML, CSS and JavaScript, no build step)
- `CHANGELOG.md`: what changed in each version

## Versions
Each release is a commit tagged `vX.Y.Z`. To see an older version, check out its tag, e.g. `git checkout v1.0.0`.

Training data is not stored in this repo. It's saved privately to the owner's Claude account.
