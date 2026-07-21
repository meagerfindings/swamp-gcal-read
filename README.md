# swamp-gcal-read

[swamp](https://swamp.club) extension `@mgreten/gcal-read` — a read-only
Google Calendar reader. Lists a single day's events (default: today) for a
configured calendar.

📖 **Extension documentation:** [extensions/models/README.md](extensions/models/README.md)

📦 **Install:** `swamp extension pull @mgreten/gcal-read`

## Repository layout

This repository is a swamp workspace (its own `.swamp.yaml` repo). The
publishable extension lives under [extensions/models/](extensions/models/):

```
swamp-gcal-read/
  extensions/
    models/
      gcal_read.ts        # model implementation
      gcal_read_test.ts   # unit tests
      manifest.yaml        # swamp extension manifest
      README.md             # extension documentation
      LICENSE.txt           # MIT license
  README.md                 # this file
```

## License

MIT — see [extensions/models/LICENSE.txt](extensions/models/LICENSE.txt).
