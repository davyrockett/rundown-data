# rundown-data

Data for Rundown (https://www.davyrockett.com/rundown/). Public, but the link isn't shared. Backup-only on the Mac:
don't edit here. Resounding Joy entries are saved without client codes or addresses.

- `data.json`: written every hour by `.github/workflows/update.yml` (calendars, The Crossing, RJ sessions, autocross).
  The script is `tools/build_data.py` in the public `davyrockett/rundown` repo; the secrets it needs are listed
  in that repo's README.
- `ticks.json`: RJ session ticks (Documented / Billed / Not a session), saved by the app.
