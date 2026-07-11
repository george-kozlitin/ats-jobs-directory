# ATS Jobs — Live Coverage & Freshness Directory

Public, verifiable coverage data behind the **ATS Jobs API** Apify actor:
every company board we track, with its live/dead status and the exact timestamp
of the last validation probe.

- `index.html` — human-readable coverage & freshness dashboard
- `directory-greenhouse.json` / `directory-lever.json` / `directory-ashby.json` —
  machine-readable directories: `{slug, company, status, jobs, last_validated_at}`
  for every live board (UTC timestamps)

Regenerated daily by an automated validation pipeline that probes each ATS's
public job-board JSON endpoint with polite per-host rate limits.

Why publish this? Every jobs-data vendor claims freshness; none lets you check.
This directory is the check. If a company you need is missing or stale, open an
issue.
