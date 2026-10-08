# Local review — 8 October 2026

The compact static guide has been rendered in the Codex browser at 1280px, 390px and 320px. The table caption initially collapsed into a narrow column on mobile; its mobile display was corrected and rechecked. Mobile table headers remain available in the accessibility tree. The page has no horizontal scroll at the reviewed widths.

Verified native section links, a visible keyboard-focus outline, the skip link moving focus to main, and a real download of coverage-plan.md whose bytes match source. Browser logs contain no warnings or errors on the local guide. One visible author credit appears on the page.

Source checks confirm the exact same 19 outbound anchor destinations as Website Chatbot Workshop, valid internal anchors and files, one H1 per HTML page, title/description/author metadata, no visible BLURSOR text and no JavaScript. Fonts and stylesheet load locally. The Markdown download is for editing; no printable worksheet is advertised.

Evidence: C:/Work/reports/after-hours-support-2026-10-08/. The Railway CLI binary is blocked by Windows Application Control; the GitHub deployment route was used without changing that policy.

## Live review

Published at https://after-hours-support-production.up.railway.app/. Actual desktop, 390px and 320px browser checks pass, including section navigation and the real Markdown download. Download bytes match source and live browser logs have no warnings/errors. The live caption and resource sections remain readable on mobile.

Anonymous HTTP checks confirm all eight public files match source exactly. Local text line endings were aligned with Git's LF source to make that comparison exact. Canonical/og:url and the one-page absolute sitemap use the confirmed origin. robots.txt permits crawling; the homepage has no noindex meta or response header. Both top-level and nested missing routes return HTTP 404 and the exact styled error page. /health returns 200 and “ok”. This verifies the real Caddy routing. Indexing and experiment outcomes remain unmeasured.

Reviewed publication commit: 6a8684a. Railway deployment 6e96f1e6-41da-4f13-9723-6cc6f1568d46 reported ACTIVE / Deployment successful, with the health check and idle-sleep settings applied. Later documentation-only commits do not change the reviewed public files.
