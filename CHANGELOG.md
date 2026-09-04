# Changelog

## 2026-09-04 — Cookie consent banner + privacy policy

**What was added:**
- A cookie consent banner shown at the bottom of every page on first visit,
  with "Accept" / "Decline" buttons (`src/components/CookieConsent.astro`).
  The visitor's choice is remembered in the browser so the banner doesn't
  reappear.
- A basic privacy policy page at `/privacy-policy` (`src/pages/privacy-policy.astro`).
  It is not linked from the site navigation or footer — it's only linked
  from the cookie banner itself.

**Why:** General-purpose legal notice/compliance for a California-based
business, covering cookie use and basic CCPA disclosures.

**To undo / roll back:**
The site immediately before this change is saved at git commit
`938e48113dbda344350f9d5cf28c518532bda7da` ("Polish homepage gallery and
careers content"). To fully remove the cookie banner and privacy policy
and restore the site to that exact state, revert to that commit (ask
Claude, or run `git revert 85d8fed` / `git reset --hard 938e481` and push).
