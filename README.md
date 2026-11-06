# danity-framework-meta

Holds `version.json`, which the Danity Framework reads once per game session to tell players when a newer version is available.

- `version`: latest released version
- `notify_below`: players on a version lower than this get the update popup (raise it only for hotfixes that matter)
- `url`: page opened when the player clicks OK
