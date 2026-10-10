# Neighbor Learner

Single-file, mobile-first web app for remembering neighbors. Open `index.html` in a browser.

- Quick-add (only name is required) with optional house number, street, pronunciation, how/when met, shared detail, follow-up question, last-seen date
- Link related neighbors (two-way, optional relationship label); "Save + add someone with them" for couples/households
- Search by name or house number
- Refresh list: oldest last-seen first, one-tap "Seen today"
- Data lives only in this browser's localStorage; JSON export/import (merge or replace)
- No network access: a Content-Security-Policy blocks all outgoing requests
