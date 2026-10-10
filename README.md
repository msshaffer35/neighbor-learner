# Neighbor Learner

Single-file, mobile-first web app for remembering neighbors. Open `index.html` in a browser.

- Quick-add (only name is required) with optional house number, street, pronunciation, how/when met, shared detail, follow-up question, last-seen date
- Search by name or house number
- Refresh list: oldest last-seen first, one-tap "Seen today"
- Quiz: shows a house number, you recall the name; misses come up more often
- Data lives only in this browser's localStorage; JSON export/import (merge or replace)
- No network access: a Content-Security-Policy blocks all outgoing requests
