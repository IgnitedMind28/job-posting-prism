# Job Posting Prism

Paste a job description, pick a CV, and see the role refracted into the dimensions
it actually emphasizes — how your background maps to each, what the day-to-day
likely looks like, and a tailored, non-fabricated CV draft you can drop into a
Google Doc.

**Live:** https://ignitedmind28.github.io/job-posting-prism/

## How it works

- A single static page (`index.html`) — no build step, no framework.
- Your CV is stored only in your own browser (local storage) and is sent to the
  AI model only when you run an analysis; it is never stored on a server.
- The AI analysis runs through a small private backend, so the page holds no API
  keys and no model details.

## Notes

Every result is a **likely inference, labelled as such** — the tool deliberately
leaves things blank rather than inventing them (an unscored axis, a blank
day-to-day, an honest "gap" in the CV tailoring). Verify before you rely on it.
