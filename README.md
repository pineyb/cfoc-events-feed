# CfOC Industry Events feed

Public data feed for the Center for Offsite Construction (CfOC) Industry Events calendar on centerforoffsiteconstruction.org.

- `events.json` — the event list. The CfOC Industry Events WordPress plugin fetches it daily (Industry Events → Import & Sync → Feed URL):
  `https://raw.githubusercontent.com/pineyb/cfoc-events-feed/main/events.json`
- Updated twice a week by a research run that re-checks dates against organizers' official pages and adds new offsite / modular / industrialized-construction events.
- `status`: `confirmed` (checked on the organizer's site, published automatically), `unconfirmed` (secondary source only, goes to the site's Pending queue for review), `cancelled` (removed from the calendar).

Listings are neutral and chronological, with no sponsored placement. Always confirm details with the organizer.

## Plugin updates
`plugin/cfoc-events.zip` is the current CfOC Industry Events WordPress plugin, and `plugin/info.json` announces its version. Sites running v1.1.0+ check this file and install newer versions automatically.
