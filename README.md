# wx-radar-data

Auto-generated radar GIF archive for [wx-radar](https://github.com/zazaalaza/wx-radar).

Captured every 30 minutes from weather.com `satradFcst` (satellite + radar forecast)
by a GitHub Actions workflow. Do not edit by hand.

## Layout

```
index.json                                   # manifest: latest capture per station
stations/
  <folder>/<ICAO>/
    latest.json                              # change-detection pointer
    <YYYYMMDD>/
      meta.json                              # capture metadata
      gif/<YYYYMMDDTHHMMSSZ>.gif             # ~2s radar loop
```

GIFs are served directly via `raw.githubusercontent.com`.
