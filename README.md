# After-Hours Support

Compact static guide for deciding what a website chatbot can answer while staff are away and who handles the rest. One content page, clearly fictional conversation examples and an editable Markdown coverage plan. Author: Alex Rostovtsev.

## Local preview

From this folder: `python -m http.server 4195 --bind 127.0.0.1 --directory public`.

Open http://127.0.0.1:4195/. There is no framework, build step, JavaScript, form, analytics or external asset request. The local heading font retains its OFL licence.

## Publication

Approved host: Railway. Dockerfile serves public/ with Caddy; PORT comes from the hosting environment, defaulting to 8080. /health responds with 200. Missing files use 404.html with the original error status. No SPA fallback is configured.

Live: https://after-hours-support-production.up.railway.app/. Source repository: https://github.com/bdod-prod/after-hours-support (main), connected for automatic deployments. Local and live review passed; see QA.md.

Canonical URL, og:url, absolute sitemap and robots reference use the confirmed production origin. All eight public files match source; crawling is allowed and top-level/nested missing pages return the styled 404 with noindex metadata.

Railway project: After-Hours Support (31d6a8ce-e424-49fb-a532-3af2faa608b7), service b709de21-fb10-4677-8cd9-8dee2a2dd25f, production environment b3dfe5e2-a78c-40bf-9ea5-fbcc29bdc8ef. Public HTTP targets port 8080. Healthcheck: /health. Idle sleep is enabled to reduce usage; the first request after sleep can take longer.

Launched on 8 October 2026 using the account's trial: up to 30 days or $5 credit. No paid plan was purchased. Actual ongoing cost after the trial remains unmeasured; the documented Free plan has $1 monthly credit and Hobby starts at $5/month with $5 usage included. Do not buy or upgrade automatically. See ../NEXT-PUBLICATIONS.md for the approved queue.

The official Windows CLI executable is blocked by Application Control; the dashboard/GitHub route works without changing that policy. Alex completed sign-in and confirmed installing the Railway App for this repository only. The Railway management project remains private while its static website is public.

Existing outbound destinations are retained as ordinary direct HTML anchors. Product links outside the core support topic are grouped in a clearly separate resources section. No visible BLURSOR branding appears in the copy.

Edit index.html, styles.css and resources/coverage-plan.md directly. Keep example coverage assumptions visible and distinguish a request from a completed action.
