# watch-fitbit-hr
Personal live tracking of Fitbit Charge HR

Target platform: Android

The intention is to have a small app that gives live review of the heaqrtrate monitored by a Fitbit Charge HR.
The main steps are:
- Authenticate: This I will recreate from the very helpful Google Sheets scripts in https://github.com/simonbromberg/googlefitbit
- Display timeframe: Show data for the last 6 hours in min 15 sec intervals (1440 data points)
- Allow user to zoom in innteresting parts
  - if necessary get more data
- Optionally: Alerts for unforeseen spikes
