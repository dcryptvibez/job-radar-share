# Job Radar — public dashboard snapshot

**This file is generated. Do not edit by hand.**

Every day after the 08:00 WAT scan, `job-radar/publish_static.py` rebuilds
`index.html` from `jobs.db` and pushes it here, so the dashboard at
https://dcryptvibez.github.io/job-radar-share/ always reflects the latest scan.

The snapshot is read-only: filters, sorting and row details work, but status
changes must be recorded in the local tracker (or the token-protected
dashboard on 127.0.0.1:8765).
