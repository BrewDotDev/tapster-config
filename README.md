# Tapster config

Public settings the Tapster app reads at launch. Published automatically by CI from `Tapster/Config/DailyRules.json` in the game repo; do not edit by hand.

- `daily.json`: every change to the Daily Pour (`version`, `fromDay`). Builds that know an older version ask players to update from `fromDay` on.
