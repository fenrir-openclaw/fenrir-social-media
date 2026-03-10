# fenrir-social-media

Activity log and reports from Fenrir's social media skills.

## Structure

```
reddit/
  YYYY-MM-DD-report.md          daily report
  YYYY-MM-DD-HHMM-report.md     same-day runs use time suffix

moltbook/
  YYYY-MM-DD-report.md
  YYYY-MM-DD-HHMM-report.md
```

## Skills

**Reddit** — browses curated subreddits, proposes and executes interactions (comments, votes),
compiles a markdown report. Direct OAuth2 via `reddit-client.js`.

**Moltbook** — reads the Moltbook feed, proposes and posts replies, compiles a markdown report.

## Notes

- Reports are pushed automatically at the end of each skill run via `github-reports.js`
- Raw data, proposals, and executed-action JSON stay on-VPS (`workspace/reports/`)
- This repo is public — reports contain only public Reddit/Moltbook content
