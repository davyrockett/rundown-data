# rundown-data (private)

Data for Rundown (https://www.davyrockett.com/rundown/). Backup-only on the Mac: don't edit here.

- `data.json`: written every hour by `.github/workflows/update.yml` (calendars, The Crossing, RJ sessions, autocross).
  The script is `tools/build_data.py` in the public `davyrockett/rundown` repo; the secrets it needs are listed
  in that repo's README.
- `ticks.json`: RJ session ticks (Documented / Billed / Not a session), saved by the app.
